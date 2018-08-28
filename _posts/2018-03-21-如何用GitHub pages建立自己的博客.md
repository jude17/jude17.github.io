---
layout: post
title: 如何使用GitHub建一个自己的博客
category: Dev
tags: [GitHub,博客]
---
## 0 - 写在前面
我曾经用wordpress建了一个博客，但是苦于自己没有太多钱付主机费，所以尝试之后就放弃了。后来搜寻了很多资料，虽说走了很多弯路，但是也成功使用GitHub pages建立现在的博客，所以把自己的经验写出来，希望让小白用户少走弯路。
<!--more-->
## 1 - 注册GitHub
进入GitHub网址[https://github.com](https://github.com)注册一个账号。

![1](http://source.yaoguaixing.com/1.png)

**注册后会让你选择一个方案，选择最下面的free就可以了。**

## 2 - 创建仓库
有两种方法可以创建仓库：

第1种：登录后点击右上方头像左侧的加号，在弹出框中选择“New repository”；
 
![2](http://source.yaoguaixing.com/2.png)

第2种：点击[https://github.com/new](https://github.com/new)

创建仓库页面如下：

![3](http://source.yaoguaixing.com/3.png)

## 3 - 设置仓库
点击仓库上方的Settings进入仓库设置。

![4](http://source.yaoguaixing.com/4.png)

滑动页面，找到GitHub Pages，按图设置：

![5](http://source.yaoguaixing.com/5.png)

选择好主题后，就有一个自己的博客了，这时候进入你刚刚设置的地址（你的用户名.github.io）就能看到页面了。但是，现在这个页面你还只能看看，还需要继续配置。

## 4 - 下载GitHub桌面版并安装
Mac版本
>[https://mac.github.com/](https://mac.github.com/)

Windows版本
>[https://windows.github.com/](https://windows.github.com/)

我用的是MacOS，所以后面的方法就按照Mac版本介绍，Windows下同理。

## 5 - GitHub桌面版配置
首先你需要登录桌面版，然后依次点击点击File - Clone Repository。

![6](http://source.yaoguaixing.com/6.png)

在Filter框中填写刚刚你设置的地址（你的用户名.github.io）

![7](http://source.yaoguaixing.com/7.png)

Clone之后就会在文稿中生成一个GitHub文件夹，文件夹的名字就是你的用户名.github.io。

## 6 - 选择主题并配置
在下面网站中选择一个你喜欢的主题，下载下来。
>[http://jekyllthemes.org/](http://jekyllthemes.org/)

打开刚刚生成的GitHub文件夹，把里面除.git（这个文件夹是个隐藏文件夹）的文件都删掉，然后把你下载好的主题Copy到GitHub文件夹中。

## 7 - 写博文
如果你下载的主题中含有_posts文件夹，那么把你写的文章（注意要用Markdown写）放在该文件夹内；如果没有该文件夹，那就在GitHub文件夹根目录下创建一个。

然后按下面步骤操作。

![8](http://source.yaoguaixing.com/8.png)

## 8 - 结束
按照上面的步骤就可以创建一个自己的博客并在上面更新博文了，如果你想要更多的功能或者更美观的页面，就需要继续学习其他知识了。

