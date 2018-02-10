# Joomla使用教程
这是针对Joomla初学者定制的初学者使用教程，这个教程旨在为Joomla学员了解Joomla的结构、获取以及安装、管理使用。
在这个教程中，无论您是Joomla初学者或是资深Joomla用户，通过本教程学习相信都能让你有所收获。尤其是对Joomla感兴趣的初学用户，本教程一定能够很好的让你成为Joomla高手，成功搭建自己的网站并做好日常管理。
## 课程设立：
1. [Joomla介绍](./Joomle介绍)
2. [整理建站规划](./整理建站规划)
3. [获取Joomla](./获取Joomla)
4. [安装Joomla](install)
5. [认识Joomla网站](frontend)
6. [认识Joomla管理后台](administration)
7. [管理Joomla文章及分类](article)
8. [管理Joomla菜单](menu)
9. [管理Joomla模块](module)
10. [管理Joomla模板](template)
11. [管理Joomla插件](plugin)
12. [管理Joomla组件](component)
13. [管理Joomla媒体文件](images)
14. [管理Joomla用户](user)
## 高级用户教程
1. Joomla多语言网站的设立
2. Joomla扩展字段管理
3. Joomla整站备份及迁移
16. Joomla邮件发送系统
17. Joomla编辑器的更换
18. Joomla扩展管理
19. Joomla版本升级
20. Joomla的全局设置
21. Joomla SEO管理
22. Joomla模板样式定制
23. T3-Framework架构模板
24. Helix-Framework架构模板
25. SP-Bulider页面构建器
26. SC短代码结构
27. 创建Joomla电商网站



# Joomla!是什么？

本章作为选学内容，你可以跳过也可以进行认真的阅读来了解Joomla!的来龙去脉。
## 初步了解Joomla
首先，在百度上面搜索Joomla您可以通过百科有简单的了解，另外如果你英文比较好可以通过[Joomla.org](http://Joomla.org)官网进行较详细的了解。当然，作为资深Joomla从业者，在这里我更喜欢从用户角度来看待Joomla!(以后的描述中Joomla!与Joomla没有区别)：

Joomla是一套开源的内容管理系统（简称CMS）。我们可以理解为它是一套免费、好用的建站系统。它本身就是一套网站，在你安装后你就立刻拥有了一套完整的网站。当然，全球有很多开源内容管理系统，比如和Joomla一样知名的Drupal和WordPress系统。但Joomla是唯一连续5年被评为最好的“开源内容管理系统”，2017年再次拨得头筹获得“开源CMS冠军”，可见它的优势并非浪得虚名。从使用角度来讲，稳定性和未来的功能扩充升级Joomla能够更好的为你所用。

从技术层面来讲：它基于PHP+HTML5代码结构组成的整站程序，以灵活的MVC结构结合Mysql数据库进行模块化内容输出管理...我想作为普通用户很不喜欢听技术层面的东西，我们在这里用比较直白的方式对Joomla的使用角度进行介绍，当然网上也有很多Joomla的相关介绍，各位有兴趣可以进一步查询了解。我想，在读这个教程的朋友更希望尽快上手使用这个神秘的Joomla系统构建自己的网站。

## Joomla应用领域：
作为内容管理系统，Joomla当然的核心优势就在于各种类型的内容发布管理，包括文字、图片、音频视频、文件等。 由于它非常安全且功能灵活的特性，Joomla非常适合做网站。

无论是企业、政府、教育、金融等各行业的官网制作，或是电商网站、个人博客或是内部资讯平台Joomla都能胜任。并且，由于它的“标准开源技术接口”有很多企业内部采用Joomla系统构建内部信息系统。一直以来，Joomla被誉为“IT专业人士推荐的建站系统”。

现在Joomla在全球网站系统的占有量约6%，诸多大型机构官网及政府组织网站使用Joomla构建。

## Joomla版本演变：

Joomla系统诞生于2005年当时是1.0版本，经过不断的完善与更新，到2008年1月22日由1.0.3版本演变成了Joomla1.5版本，也就真正形成了系统的内容管理模式，直至4年以后推出了1.5.26版本。这还远远不够后续有出现了1.6、1.7等版本的版本的出现是更改了用户管理界面和内容存储方式，也是未来2.x版本的推出做了铺垫。

直至2012年推出了Joomla2.5版。2.5版本的推出不仅从核心优化更加从使用逻辑上改变了Joomla的内容管理模式，已经颠覆了1.x时代的内容管理方式。并且在同年，Joomla首次获得了“最好的开源CMS”称号。2.5版本经过2年半的发展，最后于2014年10月止步于2.5.28版本。

2012年与2.5.x版本同时发展，更加优秀的Joomla3.0时代在2012年9月27日同步产生。3.0版本在用户管理方式、计算优化、安全性方面做的很大改进。本并且后续提速陆续进行3.1、3.2、3.3、3.4...版本的推出。2016年3月份推出了3.5版本,从此无论从运行效能及安全性方面完全到达一个新的阶段，与PHP7的全面结合，使数据处理缩短了50%以上,并全面融合了HTML5及Bootstrap3前端技术，这是真正意义上的为移动端而生的技术，直至现在的Joomla3.8.3版本。

随着技术优化和产品完善、功能增加等不断变化，自Joomla3.x推出以来直至现在（3.8.3版本）几乎每月都会有新的版本更新。与此同时，Joomla4.0版本已经于2017年12月发布公测，并计划于2018年4月份推出正式版本，各位可以通过官网了解Joomla4.0的更新特性。
![fazhan](https://www.joomlass.com/images/blog/jiaocheng/chuji/01/joomlafazhan2.jpg)
也许你不知道，Joomla是最早进行响应式（Responsive）应用的系统，早在2009年响应式技术概念刚刚明确，就有很多团队在Joomla上面进行模板产品测试开发。在国内2014年开始流行响应式技术时Joomla已经发展了这个技术5年多时间。国内很少有“响应式”的技术称呼，更多的人称之为“H5”或“三站合一”，无论怎样称呼，这个技术目的是为了适应移动互联网展现形式。

## Joomla整体优势：
- Joomla人性化的架构设计，方便用户使用管理。
- Joomla安全且运行高效。
- Joomla无限延伸的功能特性，可用于各种场合。
- Joomla的多语言机制，支持近百种语言，能够让你迅速搭建一个多语言网站。
- Joomla可以做到真正不用投入费用的实现网站建设。
- Joomla不受任何团队的技术封锁，完全开源且容易获得技术帮助。
- Joomla可以随着版本更新一直优化自身性能及功能。

## 发展环境：
与时俱进的产品变革、创新技术的不断融入这就是Joomla作为成熟系统的魅力所在。Joomla.org是由约30人的Joomla核心成员与分布在全球的3000多名志愿者构成的庞大技术社群。不仅如此，Joomla作为一套标准的开源产品，全球有大约800多个团队围绕它开展研发与开展扩展制作。有超过20000人的爱好者及从业人员参与了Joomla的产品应用，这是一个庞大的生态体系。

Joomla在中国也受到越来越多人的关注与接触。但受到版权保护的法律短板国内很少有团队分享Joomla扩展产品。由于语言沟通及市场制约限制，也很少有团队制作模板进行销售。国内专业的服务团队更多的是基于客户需求提供Joomla定制或技术支持服务。所以，很多人会认为Joomla在国内的社区环境不够丰富，缺少分享精神。在我看来，Joomla作为优秀的建站系统的安全灵活特性，以及对于新版本的方便管理，会被更多的国内爱好者所熟悉推崇。

本教程也是作为Joomla多年从业者的角度，带领大家全面深入的了解Joomla并熟练的掌握Joomla管理使用，从而自己能够独立完成一个满意的网站作品。再此之前我建议大家抛弃一切悲观想法，因为我们接下来的教程中，即便你不懂PHP或HTML代码，不懂编程或前端CSS编写都无关紧要，最终你都会成为一个专业的Joomla用户。

[foo]: http://example.com/  "Optional Title Here"
