---
layout: post
title: Atom 报错 Cannot load the system dictionary for zh-CN
category: Dev
tags: [Atom, macOS]
---
前两天把MacBook重装了一遍系统，安装了Atom后发现一个报错，报错内容为“Cannot load the system dictionary for zh-CN”，让去后面给的路径看看。
<!--more-->
![18062301](http://source.yaoguaixing.com/18062301.jpg)

本想着去路径看了下，结果发现没有文件啊！

看了下报错中的路径，既然提到了spellchecker，感觉可能是拼写检查的问题，于是试着在Packages中搜索spell，发现一个叫做spell-check的插件；

![18062303](http://source.yaoguaixing.com/18062303.jpg)

点开Settings，看到Use Locales前面打着勾，但是下面Locales内没有填写任何内容，于是把Use Locales前面的勾去掉，发现不报错了；又试着在Locales下面填上en-US，也不报错了。

![18062307](http://source.yaoguaixing.com/18062307.jpg)

额，不清楚这到底是bug还是什么，解决方法倒是不麻烦，也不知道以后会不会产生其他影响。
