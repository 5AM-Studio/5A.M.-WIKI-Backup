---
title: Ubuntu
description: 技术组的同志们请看这里哦~工作室所有的黑科技的用法都在这里哦
published: true
date: 2019-12-13T04:56:15.178Z
tags: Tech
---

# 5 A.M. Studio 技术组工作手册 - Ubuntu

***说明：本文档为5 A.M. Studio技术组的工作手册，截止至2019.11.25，工作室的黑科技的使用方式都在里面***。

***本文档内的所有账号和密码都采用了BASE64加密方式，请自己百度找解码器！！！***

**Author: GamerNoTitle | Updated Time:2019-11-30**

**Copyright © 2019 [GamerNoTitle](http://bili33.top)**

---

反正就是一台DELL Optiplex3046的电脑，里面只有一块500GB的HDD盘，但是装了Ubuntu

Ubuntu里面内置了srs（直播服务器），使用方法如下：

```bash
$ cd Github/srs/trunk
$ sudo ./objs/srs -c conf/srs.conf
```

即可打开srs服务，Ubuntu的账号及密码如下：
``Account: cGVyc2lh``
``Password: YmlsaTMzQFdQWC5HYW1lcg==``

然后至于其他的东西，反正我记得我装了git、nodejs、golang就是了，可以自己从别的地方下源码来部署
内置宝塔面板，地址是[http://172.52.5.100:8888](http://172.52.5.100:8888)，账号密码如下：
``Account: R2FtZXJOb1RpdGxl``
``Password: YmlsaTMzQFdQWC5HYW1lcg==``
装了Nginx和PHP7.3（好像是），最好不要装其他奇奇怪怪的东西，要不然服务器的网络容易爆炸。。。

Ubuntu可以使用ssh链接，推荐使用xShell

![](/img/2-1-1.png)

然后在里面直接使用Linux命令即可！
