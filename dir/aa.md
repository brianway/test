# 【太阁X】第十期：聊聊技术博客的那些事儿

标签： 随笔

---
[TOC]

---

## 嘉宾介绍

【董飞】

热爱技术，相信使命，追求极致。先后创业公司酷迅，百度基础架构组，Amazon云计算部门，Linkedin担任高级工程师，负责过垂直搜索，百度云计算平台研发和广告系统的架构。目前就职于在线教育创业公司Coursera。

- 微信公众号：董老师在硅谷 donglaoshi-123
- 知乎专栏：董老师在硅谷 http://zhuanlan.zhihu.com/donglaoshi
- 百度百家专栏：http://dongfei.baijia.baidu.com/
- Facebook Page：董老师说码工的那点事儿 https://www.facebook.com/donglaoshi123
- LinkedIn: https://www.linkedin.com/in/dongfei


【杨卓荦】

曾任阿里巴巴高级软件工程师，曾在单个集群内搭建10,000个Hadoop节点，出版过Hadoop领域相关的个人著作，现在TangoMe任职高级软件工程师。

- LinkedIn: https://www.linkedin.com/in/yangzhuoluo

【魏楚阳】 

电信专业，华科研一。目前的方向是web开发和网络爬虫。很喜欢BitTiger大家庭的氛围，技术视野变宽了，同时认识了很多优秀的小伙伴。虽然目前还是小白，但对技术有追求，对学习有热情，希望可以快速成长为和大家一样优秀的ITer！

- LinkedIn： https://cn.linkedin.com/in/weichuyang/en
- 个人网站：http://brianway.github.io
- CSDN：http://blog.csdn.net/h3243212
- oschina：http://my.oschina.net/brianway

【王思唯】

本科金融，目前在Emory读计算机硕士。优秀脱口秀主持人。计算机知识全靠自学。自从加入了BitTiger大家庭，简历好看了，面试轻松拿到了，技能学会了，更重要的是认识了一大帮子超级优秀的人。只有人比人才能督（qi）促( si)人。所以欢迎各位加入BitTiger，让我们一起愉(zuo)快(si)的学习新知识吧。个人暂时能拿出手的是机器学习技术，目标是成为一名全栈工程师。

- LinkedIn: https://www.linkedin.com/in/siwei-wang-5289a6a4/en


## 主要内容

### 董老师之论技术博客的姿势(董飞)

这部分主要是按照不同的类别，推介一些优秀的博文。包括列表类，创业类，翻译类，等等。

**列表类** 

[董老师微信公众号分类列表][1]

董老师整理了[《100家硅谷IT公司技术博客》][2]其中涵盖了很多大公司

- 知名大厂，如：LinkedIn,Netflix，AWS，Baidu Research，Yahoo，Twitter.
    - [《首席工程师揭秘：LinkedIn大数据后台是如何运作的》](http://mp.weixin.qq.com/s?__biz=MzA3NTM4NDE2Mw==&mid=401350558&idx=3&sn=f84a1335a3dc31753f3ea496fc2a87b6&scene=21#wechat_redirect)([英文原文](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying))。图文并茂，对数据库、分布式、系统设计都有涉及，非常值得大家阅读。
    - AWS,在云计算方面比较有名，[AWS Blog](https://aws.amazon.com/cn/blogs/aws/)
    - Twitter,open source比较有名，[Open Source at Twitter](https://engineering.twitter.com/opensource)

- 热门创业公司,如：Uber,AirBnB,Pinterest,Slack,Databricks,Confluent
  - AirBnB,其[Tech Talks](http://nerds.airbnb.com/tech-talks/)比较有名,有自己的视频，可以听一听博客。
  - Pinterest是做图片兴趣社交的，[Open Sources - Pinterest Engineering](https://engineering.pinterest.com/open-source)
  - Databricks,Spark的主要作者成立的公司。主要产品是Databricks Cloud。[Databricks blog](https://databricks.com/blog)
  - Confluent,Apache Kafka的几个主要开发者出来做的公司。[Confluent Blog](http://www.confluent.io/blog)
- 大数据相关，如：H2O.AI，MapR，Sumo logic
   - H2O.AI，涉及AI的算法和机器学习，开源的。
   - MemSQL，号称最快的内存数据库。

**创业类** 

[2015年斯坦福创业课程](https://github.com/dongfeiwww/blitzscaling)

**翻译类** 

[2015年科技阅读列表600篇](http://zhuanlan.zhihu.com/p/20386800)

**技术类** 

[High Scalability](http://highscalability.com/),介绍各个公司的架构


### 闲扯技术博客(by杨卓荦)

**写博客的四个境界**

- 自身价值：找到好工作，开阔自身视野
- 积累沉淀：自身技术总结
- 融入交流：融入技术圈，与大牛交流
- 成就他人：改变行业，引领时代方向。如：雷军，傅盛

**写博客的过程**

先以笔记的形式记录

- 1.问题导向，发现问题
- 2.分析解决，持续改进
- 3.总结提升

把笔记升华为博客

- 要有**图**，一图胜千言。
- 以问题为中心(what,why,how)
- 层次段落要清晰(标题，子标题，章节)
- 突出中心(记录解决问题、如何解决而非记录解决问题花费的功夫),节约读者时间

示例：什么是Counting Bloom Filter？http://blog.csdn.net/jiaomeng/article/details/1498283

这个示例博文最大的亮点是图，纯文字的部分只有短短一两百字。但把Counting Bloom Filter清晰地用图画了出来，然后用几个公式介绍概率是如何计算的，最后把论文的链接列出来。

**博客内容**

博客应该一种分享和兴趣，把自己的事业发表出来。应该有深度的分析，关注问题之间的联系。同时，博客应该坚持原创，有自己的观点。最后，应该坚持下去。


### 小白博客之路(by魏楚阳)


**写博客的好处**

- 对技术的了解更深入
- 被约稿，能挣钱
- 技术名片，交到志同道合的朋友
- 记录自己的成长

**无谓的担心**

- 没有价值？

你面临过的问题总会有人面临过，你的工作肯定是有意义的。

- 想法幼稚，漏洞百出？

人非圣贤，一个人的想法总是会有漏洞的，被别人指出问题才可以更快地改进。

**如何选题**

从受众入手

- 新手：《hadoop体系介绍》，《tomcat入门初探》，《快速搭建LAMP》，等等，偏入门和使用的题目。
- 高手：从纵向切入，可以写某个技术的来龙去脉、发展历程，如《javaIO模型的演进》。从横向切入，可以写写某个大主题，如《Java中的24种设计模式与7大原则》。还可以从细节入手，把一个问题讲透彻，如《java字节码》

**如何展开**

根据文章类型

- 学习笔记：随性，开心就好。
   - 示例：[java&javaweb学习笔记(汇总) -  by Brian 
](http://blog.csdn.net/h3243212/article/details/50659471)
- 源码分析：代码+说明,debug结果。
  - 示例：[Java HashMap工作原理及实现 - by Yikun](http://yikun.github.io/2015/04/01/Java-HashMap%E5%B7%A5%E4%BD%9C%E5%8E%9F%E7%90%86%E5%8F%8A%E5%AE%9E%E7%8E%B0/)
- 入门教程：深入浅出，图文并茂。
   - 示例：[Git教程 - 廖雪峰的官方网站
](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
- 技术见解：旁征博引，对比归纳
   - 示例：[学习&使用技术的四种层次 - by Lucida](http://lucida.me/blog/levels-on-learning-and-using-technologies/)
   
**发布平台**

现有平台

- CSDN：号称“全球最大中文IT社区”
- oschina：开源中国。是目前中国最大的开源技术社区。
- SegmentFault：更像一个问答社区。
- github:可以直接新建一个repo，然后上传自己的博客。

搭建个站

github pages，常用博客引擎有：

- jekyll
- Octopress
- Hexo

在github上基于jekyll搭建个人博客可以参考[在github搭建个人网站 – Brian Way][6]

写作工具

格式肯定首选markdown，编辑器可以使用作业部落cmd-markdown,Mac用户可以使用mou。图片的话可以使用免费的第三方云存储“七牛云”


## 资源分享

>* 160家优秀国外技术公司博客，http://zhuanlan.zhihu.com/p/20641362
>* 好东西论坛,http://forum.memect.com/
>* 知乎：优秀的程序员博客有哪些？https://www.zhihu.com/question/19934502
>* 为什么你应该（从现在开始就）写博客？http://mindhacks.cn/2009/02/15/why-you-should-start-blogging-now/
>* 我为什么坚持写博客？- stormZhang： http://stormzhang.com/android/2016/03/04/why-i-keep-writing-blog/
>* 在github搭建个人网站 – Brian Way ：http://brianway.github.io/2016/01/07/build-blog-with-jekyll-and-github/
>* 【组会视频+ppt】
https://drive.google.com/folderview?id=0B6RF3dJtuOBna0Y3Z0VPcnRWZUk&usp=sharing



[1]: http://mp.weixin.qq.com/mp/homepage?__biz=MzA3NTM4NDE2Mw==&hid=1&sn=dfec54dc8ee4a5d76e455d90a827aec4#wechat_redirect
[2]: http://mp.weixin.qq.com/s?__biz=MzA3NTM4NDE2Mw==&mid=401398776&idx=1&sn=76a3c474ab4d3b9d3b732b9c5dffc619&scene=21#wechat_redirect
[6]: http://brianway.github.io/2016/01/07/build-blog-with-jekyll-and-github/
