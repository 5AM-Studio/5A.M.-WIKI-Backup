---
title: 监控摄像头
description: 本文为监控摄像头的使用方式，详细阅读后希望你也会使用工作室的摄像头哦！
published: true
date: 2019-12-14T09:33:59.776Z
tags: Tech
---

# 摄(se)像(xiang)头(tou)的打开方式
工作室一共有两个摄像头（截止至2019.12.13），本文将详细介绍中兴摄像头和小米摄像头的使用方式
本文中所有摄像头都需要连接5 A.M. Camera这个WIFI，请确保已连接并且处于172.52.\*.*网段
## 中兴摄像头
中兴摄像头需要使用中兴智能家居APP，确保你已经下载！
首先打开APP，登录账号（已加密）
``Account: MTMyNjgyMTE4NTA=``
``Password: WFhYMjAwM2FtbTAxMzFkZA==``
然后就会进入主界面
![zte-app1.jpg](/camera/zte-app1.jpg)
点击此摄像头，就会进入管理界面
![zte-app2.jpg](/camera/zte-app2.jpg)
点击右上角的小齿轮，进入设置界面
![zte-app3.jpg](/camera/zte-app3.jpg)
点击摄像机通用，查看IP地址
![zte-app4.jpg](/camera/zte-app4.jpg)
获取到IP地址（此处为172.52.5.100）后，手机端的工作就结束了
打开电脑浏览器，输入[IP地址](http://172.52.5.100)，进入管理界面，登录账户
![zte-pc1.png](/camera/zte-pc1.png)
``Account: YWRtaW4=``
``Password: NUFNbmI2NjY=``
可以进入管理界面
![zte-pc2.png](/camera/zte-pc2.png)
点击上面的参数设置，进入设置界面
![zte-pc3.png](/camera/zte-pc3.png)
在此处可以更改摄像头的IP地址，点击左侧的应用设置，展开本地存储
![zte-pc4.png](/camera/zte-pc4.png)
将设备选择到NAS，然后点击更改
![zte-pc6.png](/camera/zte-pc6.png)
直接选择手动配置，配置如下：
``IP: 172.52.5.6``
``Account: WlRF``
``Password: NUFNbmI2NjY=``
![zte-pc7.png](/camera/zte-pc7.png)
然后进入目录视图，选择Camera确定即可！这样你就成功设置了中兴摄像头！

## 米家摄像头
米家摄像头是~~某次小米商城特价是买的~~因为视角不够买的，每一代工作室负责人交接后请重置一次摄像头！！！**（中兴的不要重置）**
**最重要的是：请给小米用户：473592795摄像头权限！！！(如果领导注册了小米账号也共享一下设备给领导）**
绑定设备谁都会，这个不讲，直接跳到进入监控视图
![mi-camera2.jpg](/camera/mi-camera2.jpg)
点击右上角的三个点，弹出菜单，选择存储管理，然后点击NAS网络存储（其中摄像头内需要有TF卡）
![mi-camera4.jpg](/camera/mi-camera4.jpg)
选择群晖服务器（里面的5AM-Synology），然后输入账号
``Account: TUktQ2FtZXJh``
``Password: NUFNbmI2NjY=``
选择Camera文件夹，保存即可
如果你看到了如下的界面，就代表你成功了！
![mi-camera7.jpg](/camera/mi-camera7.jpg)