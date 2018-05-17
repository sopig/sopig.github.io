---
layout: page
title: About
description: 打码改变世界
keywords: Zhuang Ma, 马壮
comments: true
menu: 关于
permalink: /about/
---

Hi，我是sopig，89年生于湖北仙桃，毕业于北京联合大学，程序员，喜欢做东西。

经常上新浪微博，有时用Instagram拍照，会去豆瓣找书和电影，偶尔上twitter。


欢迎Email交流： chay0103@gmail.com chay0103@gmail.com 或者在这里留言。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
