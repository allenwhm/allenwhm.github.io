---
layout:       post
title:        "拉勾职位分析 - 大数据开发"
date:         2020-07-03
author:       "Allen"
header-mask:  0.3
catalog:      false
multilingual: false
tags:
    - Data Analysis
    - 大数据
---

每个人都期望进步，想要提升自己到一个新的职业高度，或者拥有一份理想的工作。

但是，往往又没有一个明确的目标，以及为了达成这个目标，自己需要培养什么样的能力。

俗话说，`知彼知己，才能百战不殆`。只有我们对目标有清晰的认知，才能找准努力的方向。

而了解一个岗位最简单最直接的方式，就是去看那些在招的职位。

对于自己而言，期望从事 `大数据` 方向的 `数据分析` 工作。在思考了一番之后，做出了如下的总结：  
- 数据源 
    - 招聘网站是否有现在的API可供使用
    - 是否有相应的数据集
    - 从招聘网站爬虫
- 岗位
    - 大数据开发
    - 数据分析
- 工作地点
    - 广州
    - 深圳 / 上海 / 杭州 / 北京    
- 技能
    - 职位描述/任职要求
    - 分析
        - 词云
        - 对技能的要求程度
- 工作经验
    - 经验要求
    - 不同经验区间的差异
- 薪资
    - 薪资整体情况
    - 不同职级/地区薪资的差异
    - 平均数 / 中位数
 - 学历
    - 学历要求
- 工作地点
    - 不同城市的薪资差异
    - 以地图的形式呈现

拉勾作为一个专注于IT方向的招聘平台, 很适合去获取这方面工作的详细的情况。而且，已经有很多人对拉勾上的职位进行了分析，并且提供了详细的教程。非常详细地指导我们如何从拉勾上爬取数据，如何规避拉勾网的反爬虫，以及对拿到所需的数据进行分析。

接下来的尝试都是基于[这篇](https://junstat.github.io/2018/03/15/lagou-spider/)
教程。在实践的过程中，发现拉勾对反爬虫也做了更多的努力，例如在Chrome中打开console的情况下就不能正常加载页面。
用到的技术如下：
- Python 3
- MongoDB
- Jupyter Notebook

在爬取拉勾网1500条 `大数据` 岗位的数据之后，有了如下的一些发现。

- Java / Hadoop / Spark / Hive 是大数据岗位的核心技能  
![skill](/img/in-post/lagou_skill.png)

- 工作地点主要集中在*北上深杭广*  
![city](/img/in-post/lagou_city.png)

- 学历要求本科的岗位最多  
![education](/img/in-post/lagou_education.png)

- 3-5 年的中级开发和 5-10 年的高级开发最吃香  
![experience](/img/in-post/lagou_experience.png)

- 月薪集中在 15K-40K 之间  
    由于薪资一般是一个区间，如果每个岗位薪资取最高和最低值的平均值的话：  
    ![salary](/img/in-post/lagou_salary_average.png)

    如果把薪资区间的每一个数值都计1个单位，所有岗位累加呈现的整体形式如下：  
    ![salary](/img/in-post/lagou_salary.png)

- 福利待遇  
![benefit](/img/in-post/lagou_benefit.png)


