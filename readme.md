# Re:从零开始vivado安装

# Before

vivado支持的系统一览

![1567997740171](readme.assets/1567997740171.png)

[官方文档](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2018_3/ug973-vivado-release-notes-install-license.pdf)

# 开始安装

## 第一步：

打开[xilinx官网](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools/2019-1.html)

## 第二步：

选择你要装的版本，比如我要装的是2019.1版本的windows版，选择webpack进行安装，就是我框起来大的红框框。其他版本比如2018、2017版本类似，都选择适合自己电脑的webpack进行安装。

![1567868370105](readme.assets/1567868370105.png)

**有需求的用户可以下载linux版本的，目前并没有Mac版本的。**（可以尝试虚拟机或者wine解决）

Linux安装参考[这里](https://github.com/gpzlx1/HowToInstallVivado/blob/master/How_to_Install_vivado_for_linux.md)，不过还是推荐先看完这篇文章，了解大概流程。

## 第三步：

点击下载链接，就是要求你登录，这里我很久之前就注册过了，所以直接登录了。

![1567868646789](readme.assets/1567868646789.png)

如果没有账号就先注册一个。

注册链接：[https://www.xilinx.com/registration/create-account.html](https://www.xilinx.com/registration/create-account.html)

按照真实信息进行填写就可以了。**（注意用英文填写。）**

登录之后，又会要你填一个蛮复杂的表格的，这个是为了身份验证用。

![1567868844454](readme.assets/1567868844454.png)



**也是如实填写，注意这里也全部都要用英文填写。**

点击download就会弹出webpack的下载包。

下载完成后，双击打开webpack

![1567869043012](readme.assets/1567869043012.png)

##	第四步：

我们下载好webpack，就双击打开，等待一会，就会开启。

![1567869203526](readme.assets/1567869203526.png)

直接就**Next（如果要加快安装速度，推荐先暂时关闭杀毒软件什么，我电脑上没有杀毒软件，所以就不管了）**

后面会叫你登录，直接用刚才的注册的帐号登录就可以。

![1567869288069](readme.assets/1567869288069.png)

下一步就无脑agree就行了

![1567869409286](readme.assets/1567869409286.png)

**其次就是最重要的一步，请选择第一个选项，只有这个是免费的。**

![1567869434005](readme.assets/1567869434005.png)

Next之后就是下载包的选择了，保持默认不动，参考下面的选择，去除一些选项

这里简单提下，DocNac是一些文档，SDK是软件开发工具，我们应该用不到。

![1567870028535](readme.assets/1567870028535.png)

随后Next就是开始下载了。**这样要强调，安装路径不要有中文，不然会安装失败的，求你们了，一定要看到这句话。**

![1567870052166](readme.assets/1567870052166.png)

随后install，就可以下载了，推荐到网比较好的地方下载。


![1567870125046](readme.assets/1567870125046.png)


耐心等吧，如果你选择装在机械硬盘里，第三步Final processing 可能会比较慢。

（如果下到一半，突然没有下载速度了，可能是你网不好，或者你杀毒软件没有关，当前正在对已经下载的包进行校验和扫描，反正**没有报错就耐心等等**。）（等等党终将胜利）

这里结束，软件应该是安装好了。

这里我是装在我的nvme固态上，所以除了下载慢一点，其他几步都蛮快的。

![1567988836595](readme.assets/1567988836595.png)

## 第五步 打开软件

![1567988995311](readme.assets/1567988995311.png)

点击这个图标，打开软件是这样子的。

![1567988948060](readme.assets/1567988948060.png)



# 写在最后

注意：verilog是硬件开发语言和C有很大的不同，当讲到verilog语法和上前几次实验时，请认真听讲，可以避免好多坑。祝各位以后实验开心。：-)

张老师班vivado参考资料：https://www.bb.ustc.edu.cn/webapps/blackboard/content/listContent.jsp?course_id=_257_1&content_id=_11422_1&mode=reset

另外推荐大家阅读[提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md)