---
layout:       post
title:        "30分钟，搭建你的个人网站 | github.io"
date:         2019-03-16
author:       "Allen"
header-img:   "img/in-post/build-personal-blog/build-personal-blog.jpg"
header-mask:  0.9
catalog:      false
multilingual: false
tags:
    - Blog
    - GitHub
---

不管懂不懂网页技术，搭建一个属于自己的个人网站总是极具诱惑力的。

这是一个完全由你自己掌控的地方，在这里，你是你自己的国王/王后。

也许这事以前做起来还有些麻烦，但是现在却十分简单，零基础，零投入，即刻拥有！

为了让你有一个直观的感受，可以先看我快速创建的 [主页](https://allenwhm.github.io)。

搭建个人网站的方式有很多种，最近发现最简单快捷的是用 [github.io](https://pages.github.com/) 。

根据 [github pages](https://pages.github.com/) 的提示，一步一步做下来，很快就可以搭建一个基本的网站。下面所做演示，也基本按照这样的流程，只是补充一些内容，搭建一个更加美观的网站。

话不多说，立马行动。Can't wait to start!

1.注册GitHub账户
[https://github.com/join](https://github.com/join)

![register](http://img.blog.csdn.net/20170812211800107?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

起一个你喜欢的名字，同时也是你的域名地址的一部分，支持字母和减号。创建成功后，登陆邮箱验证账户。

2 . 创建一个代码仓库
[https://github.com/new](https://github.com/new)

![create repository](http://img.blog.csdn.net/20170812212039453?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

注意，标识部分必须和你的用户名保持一致。假设你的用户名是 greatday, 那么代码仓库名字为greatday.github.io，也即主页域名。

3.下载代码编辑器 & Git 
IntelliJ IDEA 还是 Eclipse, 你喜欢就好。

IntelliJ IDEA ： [https://www.jetbrains.com/idea/download](https://www.jetbrains.com/idea/download)     
Eclipse ： [https://www.eclipse.org/downloads/](https://www.eclipse.org/downloads/s)         
下载之后按照要求一步步安装。

是的，如果用IDEA的话你还需要一个Git。
[https://git-for-windows.github.io/](https://git-for-windows.github.io/)

4.从服务器上拉取代码
所以，方便起见，以Eclipse为例，默认你已经把上述软件安装好并打开了。

![import](http://img.blog.csdn.net/20170812212103119?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

图1区域内右键，选择导入import.

![project from git](http://img.blog.csdn.net/20170812212122829?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

Project from Git

![clone](http://img.blog.csdn.net/20170812212135077?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

如图操作

![clone](http://img.blog.csdn.net/20170812212230947?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

![clone](http://img.blog.csdn.net/20170812212250178?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

复制你的仓库地址 https://github.com/allenwhm/allenwhm.github.io.git，或者把用户名替换为你自己的即可。

![clone](http://img.blog.csdn.net/20170812212304942?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

然后一路Next，创建好你的项目。

5.编写代码，或者借用人类智慧的结晶
从来教好不教坏，所以这个自行百度 <网页模板> 随便找第一个网站随便下载一个然后解压，应该就像下面这样。

![project](http://img.blog.csdn.net/20170812212408562?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

然后复制到你的项目目录下。嗯，1秒钟写完一个精美网站。

![copy to ide](http://img.blog.csdn.net/20170812212422111?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

修改文件内容，成为你的网站。

![edit](http://img.blog.csdn.net/20170812212458807?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

最简单的方法就是找你看的懂的地方，然后修改。

还是建议你学习一点 html, css的基础知识，别担心， 很简单的。[Runoob](http://www.runoob.com/html/html-basic.html) 

6.上传代码

![commit](http://img.blog.csdn.net/20170812212528920?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

随便写点commit message， 然后commit and push。页面因Eclipse版本而异。

![commit message](http://img.blog.csdn.net/20170812212550892?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

7.见证奇迹的时刻

![final](http://img.blog.csdn.net/20170812212617164?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

一般在代码上传完毕之后，网站自动部署完毕，打开 [https://allenwhm.github.io](https://allenwhm.github.io)， 用户名替换为你自己的用户名即可。如果暂时404, 稍等片刻。如果一直404, 少年过来，我来教你（认真脸）。

简单的几个步骤，就可以拥有属于你自己的网站，还不来试试？

任何问题，欢迎随时私信，有问必答，真的！

**Plus**

1.除了搭建个人主页，用来搭建项目主页也是不错的选择

[http://alibaba.github.io/](http://alibaba.github.io/)

![alibaba](http://img.blog.csdn.net/20170812212641630?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

2.在搭建网站的时候建议压缩图片大小，建议单张控制在100k以内，能大幅提升网站的性能和访问速度。别问我怎么压缩图片，美图秀秀你值得拥有。

文章首发于个人公众号 ： 明说 （dataintelligience），欢迎关注讨论。

![明说](http://img.blog.csdn.net/20170812104118765?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvTWVldF9N/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
