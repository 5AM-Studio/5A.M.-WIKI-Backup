---
title: srs使用手册
description: 直播服务器的使用手册，安装及编译请看http://bili33.top/2019/09/19/srs/
published: true
date: 2019-12-13T23:30:37.544Z
tags: Tech
---

# srs使用手册
srs是我（[@GamerNoTitle](http://bili33.top)）搭建的内网直播服务器，源码在Github上有，地址在这里：https://github.com/ossrs/srs
如何编译请看这里：http://bili33.top/2019/09/19/srs/
服务器的打开方式如下：
1、进入到程序目录
2、打开程序
当然这些要在命令行里面进行，使用Ctrl+Alt+T可以快速打开命令行
```bash
$ cd ~/Github/srs/trunk
$ sudo ./objs/srs -c conf/srs.conf
```
打开后如果需要看日志就不要关闭命令行，或者你可以在srs.conf里面更改设置将日志写入文件。
更改配置后，使用
```bash
$ taskall -1 srs
```
来重启服务！