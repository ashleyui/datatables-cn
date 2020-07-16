---
layout: daily
title: 如何定位问题（js调试基本技能） 《不定时一讲》 DataTables中文网
short: 如何定位问题（js调试基本技能）
date: 2016-4-22
group: 2016-4
caption: 《不定时一讲》
categories: blog
tags: [博客,技能]
author: DataTables中文网
redirect_from: /manual/daily/2016/04/22/how-to-find-the-questions-basic-debug-skill-of-javascript.html
---
今天不讲参数，也不讲使用方法，讲讲我们该如果去找到问题，解决问题。谁都有犯错的时候，但是我们要吸取教训，在以后的学习道路中少走弯路。 作为前端开发人员几个基本的知识是一定要知道的。
F12- 人称万能的f12，现在主流的浏览器都有，俗称开发者工具，只要浏览器开着，这个就一定开着.
<!--more-->

chrome有两个方式调出开发者工具 ，ctrl+shift+i 和 F12，在开发者工具里首先要提到的两个功能是console和network

1. **console**

当你打开了开发者工具，那么你的关注点就要放在控制台（console）上，比如我现在打开
[DataTables中文网](http://datatables.club/) 地址，控制台就会有错误提示，如图一

{% include blog/imghtml.html src='/images/daily/2016-04-22/1.png' alt='图一' %}

被标记处是重点需要关注的，对于红色的错误提示，是绝对不容忍了，但是看到这里，可以判断出没有关系，不影响Datatables的显示。
一般在使用Datatables的时候，如果没出效果或者方法执行没效果之类的，首先看控制台有没有报错，提示等等，
**一定不要忽视控制台打印的任何信息**

2. **network**

第二类问题出现在开启了服务器模式了，数据加载异常，这个问题怎么去找，大部分网友不知道怎么查看，不会的请看看下图


{% include blog/imghtml.html src='/images/daily/2016-04-22/2.png' alt='图二' %}
{% include blog/imghtml.html src='/images/daily/2016-04-22/3.png' alt='图三' %}

切换到network功能，在这里可以看到所有的资源请求，那么这里我们根据代码里定义的数据url **arrays.txt** 关键字在搜索框里过滤后找到我们的请求。
从上两个图可以在**headers**部分看到请求的url，请求的参数，在**preview**部分可以看到返回的数据，那么当你遇到问题后不知道怎么解决的时候，
就应该从这些地方检察，或者贴图在群里。切记不要空喊，为什么没效果，为什么？为什么？为什么？
**不贴代码，不贴效果图片，不贴错误提示，我们也不知道为什么。**

最后再说一点，使用**console.log()** 替换 alert() ,不说console.log()是最好用的，
但至少比alert()强百倍，在调试代码的过程中绝对是大臣。希望从这一讲中，大家在遇到问题时，
能更快速的定位到问题，即便自己不能快速定位，把这些信息都贴到群里，群友也能帮你快速定位到问题所在。
