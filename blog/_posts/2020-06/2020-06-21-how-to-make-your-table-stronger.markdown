---
layout: daily
title: 使用DataTables"武装"你的html表格——开刊   博客 DataTables中文网
short: 使用DataTables"武装"你的html表格——开刊 
date: 2020-06-21
group: 2020-6
caption: DataTables 中文网博客
categories: blog
tags: [博客,DataTables使用经验,第二季视频]
author: DataTables中文网
toc: true
---

## 前言

三年前，[《致在使用DataTables的小伙伴》]({{ site.baseurl }}/blog/2016/06/04/to-reader.html)，看到努力的自己，我想感谢我自己。
谢谢你，谢谢一直努力的你！
<!--more-->
我还想说，我很幸运，我选择了Datatables。我也很感谢那些正在使用以及即将要使用Datatables的小伙伴，因为没有你们，就没有现在的
DataTables中文网，没有你们，Datatables中文网也走不到今天。每当看到你们从中文网上获取到答案或者思路，我都感到无比的开心。我永远都忘不了
当我使用Datatables服务器模式遇到问题解决不了的时候，有一个人帮我解决，然后我豁然开朗的感觉，我想大家每当问题得到解决的时候那种心情是多么的……


但我也要批评我自己，批评自己不够坚持，没有做到有始有终，以为这样就足够了，这是对大家不负责也是对自己不负责。从2014年到2019年，Datatables中文网
一直属于半成品状态。我高兴，因为上面的内容能够帮助大家，但我又悲伤，因为内容不够完整，不是所有人都能在上面得到答案。有的人说好，有的人说不好，
以前我会在意这些看法，但是现在不会了，人无完人，也没有完美的东西。任何事情都是在一次次修正中，逐渐趋于完美。不管怎么样我还是坚持过来了，没有放弃，
那么在接下来的时间里，不仅仅只是坚持，还要把它做得更好。

现在越来越多的IT在线教育平台，讲各种各样的知识，技术，框架等等。我也经常会去上面学习，通过看视频，对自己的知识查漏补缺，还可以系统的梳理知识。
而且对于一些质量好的视频看过之后有种醍醐灌顶，豁然开朗的感觉，如果看一次不懂还可以看第二次，三次，直到明白为止。正因为如此，我有了做视频的念头，
如果我也能把我总结的经验说出来教给别人，把知识分享给更多人，岂不也是一件快乐的事情。

所以，我做了。

## 课程目的

本次推出Datatables入门第二期 ——《使用Datatables"武装"你的html表格》，旨在给出一个系统的学习路径，解决如下问题：

- 不知道怎么学习Datatables
- 新老版本混用，不规范和不标准，阅读代码困难
- 滥用Datatables，小小需求就用插件导致项目臃肿
- 不知道怎么把Datatables的强大功能套用到自己的项目中
- 客户端模式和服务器模式什么区别，怎么使用
- 什么是正交数据，什么是渲染器
- 等等……

## 课程内容

- [开刊][zero]（即本节内容）
- [第一章，Datatables的6大特性][one]
    - 如何使用Datatables
    - DOM属性的介绍
    - DOM属性的标记语言
- [第二章，对于各种数据源该怎么使用Datatables][two]
    - Dom数据源
    - javascript数据
    - Ajax数据
    - 服务器模式
    - 客户端模式
- [第三章，复杂数据的处理-正交数据][three]
    - 什么是正交数据
    - 预定义值提供正交数据
    - 函数处理提供正交数据
    - HTML5 `data-*`和正交数据
- [第四章，复杂数据的显示-渲染器][four]
- [第五章，Ajax][five]
- [第六章，打造和自己项目贴近的表格-如何配置Datatables][six]
    - {% include href/Options.html param="ajax" %} Ajax数据源配置
    - {% include href/Options.html param="data" %} JavaScript数据源配置
    - {% include href/Options.html param="serverSide" %} 开启服务器处理
    - {% include href/Options.html param="columns.data" %}  列数据源选项
    - {% include href/Options.html param="scrollX" %}  水平滚动条
    - {% include href/Options.html param="scrollY" %}  垂直滚动条
    - [完整的选项列表][options]
- [第七章，API][seven]
    - {% include href/APIs.html param="ajax.reload()" %} 重新获取数据
    - {% include href/APIs.html param="cell().data()" %} 获取单元格数据
    - {% include href/APIs.html param="columns().data()" %} 获取列的数据
    - {% include href/APIs.html param="rows().data()" %}  获取行的数据
    - [完整的API列表][api]
- [第八章，Styling 样式][eight]
- [第九章，Events 事件][nine]
- [第十章，ServerSide 服务端处理][ten]
- [第十一章，Internationalisation 国际化处理][eleven]
- [第十二章，Security 安全][twelve]
- [第十三章，Technical notes 技术说明][thirteen]
- 第十四章，实战——制作一个具有增删改查功能的表格
    - 行内编辑
    - 弹框编辑
    
> 内容会有变动，只有视频录好后就定下内容，本目录会不断更新直到全部完结

## 课程时间安排

每周1-2次直播，周一到周五，晚上八点，如果是周六周日下午三点，每次直播时常在40分钟左右，直播前会在群里提前发出通知。如果你不想错过直播，可以加群20779435或者关注Datatables中文网官方[微博][weibo]获取每次的上课提醒。

## 课程视频

由于源码托管在GitHub上，不方便传大文件，观看视频请加群20779435，视频在群文件里可以查阅，或者查看我的[bilibili频道][bilibili]、[Youtube频道][youtube]和[微博视频][weibo]在线播放

<iframe flag="bilibili" src="//player.bilibili.com/player.html?aid=371059858&bvid=BV14Z4y1H7be&cid=204746284&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

最后，谢谢大家的支持，如有错误的地方还望指出，如果您还有其他的建议或要求，欢迎在下方留言


[youtube]: https://www.youtube.com/playlist?list=PLfl1Raz12t6s43Fb--qDoIsBPKHEme7FO
[bilibili]: https://space.bilibili.com/618644465/channel/detail?cid=133983
[weibo]: https://weibo.com/2957561617/profile?topnav=1&wvr=6&is_all=1

[zero]: {{ site.baseurl }}/blog/2020/06/21/how-to-make-your-table-stronger
[one]: {{ site.baseurl }}/blog/2020/06/23/datatables-dom-option.html
[two]: {{ site.baseurl }}/blog/2020/07/02/datatables-data-source.html
[three]: {{ site.baseurl }}/blog/2020/07/15/datatables-orthogonal-data.html
[four]: {{ site.baseurl }}/blog/2020/07/20/datatables-renderers.html
[five]: {{ site.baseurl }}/blog/2020/08/03/datatables-ajax.html
[six]: {{ site.baseurl }}/blog/2020/08/05/datatables-options.html
[seven]: {{ site.baseurl }}/blog/2020/08/10/datatables-api.html
[eight]: {{ site.baseurl }}/blog/2020/08/17/datatables-styling.html
[nine]: {{ site.baseurl }}/blog/2020/08/26/datatables-events.html
[ten]: {{ site.baseurl }}/blog/2020/09/07/datatables-server-side.html
[eleven]: {{ site.baseurl }}/blog/2020/09/10/datatables-i18n.html
[twelve]: {{ site.baseurl }}/blog/2020/09/14/datatables-security.html
[thirteen]: {{ site.baseurl }}/blog/2020/09/21/datatables-tech-notes.html
[options]: {{site.baseurl}}/reference/option
[api]: {{site.baseurl}}/reference/api