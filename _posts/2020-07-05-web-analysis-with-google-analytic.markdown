---
layout:       post
title:        "利用 Google Analytics 进行网站访问分析"
date:         2020-07-05
author:       "Allen"
header-mask:  0.3
catalog:      false
multilingual: false
tags:
    - Data Analysis
    - Google Analytics
---

有一个很简单的需求，需要统计并显示 GitHub Pages 的访问数据，如 Page View (PV) 和 User View (UV) 等。而且方案需要能够应用在基于 Jekyll 构建的静态网页上。

在调研之后发现，虽然有不少解决方案，最终选择了 Google Analytics (GA)。一则 GA 是被提及最多，使用最广泛的工具，二则它强大而且免费，自己在以后肯定会更多的了解和使用它。
- [Google Analytics](https://marketingplatform.google.com/about/analytics/)
- [Google Analytics for Jekyll](https://desiredpersona.com/google-analytics-jekyll/)
- [Add Google Analytics to a Jekyll Website](https://curtisvermeeren.github.io/2016/11/18/Jekyll-Google-Analytics.html#)

GA 虽然功能强大（能够分析访问者的地区、同时在线的用户数量、访问最多的页面等等），可是自己的初衷，仅仅只是在页面上显示当前网站或者页面有多少的历史访问而已。

最后找到了一个能直接满足自己需求的工具，**不蒜子**。最初看见这个名字的时候，其实是拒绝的。可是在了解之后，发现它足够的简单和便捷，所以最终还是选用了它。

很好奇 **不蒜子** 这个名字有什么样的来源，不过这也说明了，一个好的名字对于产品是多么的重要。
- [Jekyll博客统计访问量，阅读量工具总结](https://zhang0peter.com/2020/01/19/GitHub-jekyll-view-counter/)
- [不蒜子](https://busuanzi.ibruce.info/)
- [不蒜子 文档](http://ibruce.info/2015/04/04/busuanzi/)



下面就是最终的结果。

![GA](/img/in-post/web_analysis_google_analytics.png)  
**Google Analytics** 提供了强大的分析功能。

![busuanzi](/img/in-post/web_analysis_busuanzi.png)  
**不蒜子** 以最简单的方式满足了统计并显示访问量的需求。



