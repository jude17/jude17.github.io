---
layout: post
title: 如何使用Shadowsocks翻墙
category: Dev
tags: [翻墙,SS]
---
## 科学上网注意事项
科学上网是为了让大家能更好地了解这个世界，虽然不得不科学上网这件事很让人蛋疼，但是不要把这件事情带到某种立场上面，一定不要！

**科学上网的途径很多，SS只是其中一种，本文介绍的是如何使用SS/SSR科学上网。**

<!--more-->

## 0 - SS是什么

SS是Shadowsocks的简称，至于他究竟是什么，现在可以不用知道，SS还有个兄弟叫SSR，至于他们之间的区别，这里也先不说；通过SS和SSR可以实现科学上网，方法也很简单，只需要三步：

>1 - 下载对应操作系统的SS/SSR客户端，建议使用SSR的客户端，兼容SS，SS客户端不兼容SSR，可能会导致扫描二维码失败。
>
>2 - 获取SS/SSR节点信息。
>
>3 - 在客户端中设置后科学上网。

## 1 - 下载对应操作系统的SS/SSR客户端

不同平台的下载地址如下：

MacOS
> [https://github.com/qinyuhang/ShadowsocksX-NG-R/releases](https://github.com/qinyuhang/ShadowsocksX-NG-R/releases)
> 
> [https://github.com/shadowsocks/ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG)

Windows
>[https://github.com/tarolabs/sscap](https://github.com/tarolabs/sscap)
>
>[https://github.com/shadowsocks/shadowsocks-windows/releases](https://github.com/shadowsocks/shadowsocks-windows/releases)

跨平台（支持Windows、MacOS、Linux）
>[https://github.com/erguotou520/electron-ssr](https://github.com/erguotou520/electron-ssr)

安卓
>[https://github.com/shadowsocks/shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android)

苹果
>请在pp助手或爱思助手里搜索shadowrocket安装；国区App Store该软件已下架，无法下载，有美区账号的也可以去美区的App Store下载。

## 2 - 获取节点信息

在“妖怪行”公众号内回复SS即可获取节点二维码；或进入公众号，点击福利按钮获取节点二维码。

如果成功科学上网，建议购买节点或者自建服务器，以保证长期稳定使用。

## 3 - 在客户端设置

**以下以Mac端和iOS端为例**

>MacOS
>>打开已经获取的节点二维码，让其能在屏幕中央位置显示出来，然后打开客户端，选择扫描屏幕上的二维码（有些客户端是依次选择服务器-扫描屏幕上的二维码），会提示“添加新shadowsocks服务器配置”，此时代表添加成功，接着在服务器里选择你刚刚添加的节点，确保客户端的开关已打开，即可科学上网。

>iOS
>>打开shadowrocket，点击左上角“扫描二维码”按钮，扫描已获取的节点二维码，点击刚刚添加的节点，打开shadowrocket开关后即可科学上网。

**Mac端扫描可参考这个动图**

 ![01](http://source.yaoguaixing.com/01.gif)

**其他客户端扫描方法类似。**

**客户端中也可以通过手动添加地址、端口、加密和密码等信息进行配置，在服务器设定中依次添加即可。**
![Screenshot 2018-01-30 14.22.06](http://source.yaoguaixing.com/Screenshot 2018-01-30 14.22.06.png)



