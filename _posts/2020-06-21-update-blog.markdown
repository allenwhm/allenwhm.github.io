---
layout:       post
title:        "重拾博客"
date:         2020-06-21
author:       "Allen"
header-mask:  0.3
catalog:      false
multilingual: false
tags:
    - Blog
---

很久没有写博客了，自从把GitHub Pages使用Jekyll搭建好之后，似乎就把这事遗忘了。

除了去年的时候把CSDN上的博客转载过来，大概就是GitHub提示仓库存在漏洞，
需要升级插件的时候更新过这个repo。如果不是最近又有一个新的漏洞，
大概也不会有想法把这个博客收拾整理一番。
这次更新之后，重拾被遗忘的博客，记录自己最近所学的东西。  

这次更新的内容如下：

- 删除本地仓库中错误复制的文件 : [移除git下的untracked files](https://www.jianshu.com/p/76c93dd3eaad)  
`git clean -f -n` 

- 升级存在漏洞的插件  
    由于淘宝仓库不支持 `npm audit`, 需要先在 `~/.npmrc` 中把 `registry=https://registry.npm.taobao.org/` 注释掉。    
    ``` shell
    # show the vulnerabilities in details
    npm audit
    
    # fix the vulnerabilities
    npm audit fix
    
    # fix the vulnerabilities in force mode
    npm audit fix --force
    ``` 
    至于 `npm aduit fix` 没有更新的 websocket-extensions, 
    直接merge GitHub dependabot 提起的 [PR](https://github.com/allenwhm/allenwhm.github.io/pull/2)。

- 更正了一些单词的拼写错误

- 修改页面内容更新后自动刷新

- 使用Imgbot无损压缩图片  
    教程 : [使用 ImgBot 无损压缩博客中的图片](https://mogeko.me/2019/066/)  
    Imgbot : [Imgbot](https://imgbot.net/)  
    ![imgbot_pr](/img/in-post/imgbot_pr.png)  
    
- 删除背景图片加快访问速度  
    由于 GitHub page 有时加载还是挺慢的，而图片又比较大，虽然使用了压缩的工具, 
    把图片的大小控制在 500KB 以内，不过有时候还是不令人满意。
    那就干脆不要图片了，直接使用 CSS 的渐变色也能达到一个不错的效果。  
    [color.oulu.me](http://color.oulu.me/deta3.html)  
    [码力全开](https://design.maliquankai.com/)

- 更新了博客的图标  
    [designevo.com](https://www.designevo.com/cn/logo-maker/)