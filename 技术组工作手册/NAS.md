---
title: 群晖NAS
description: 技术组的同志们请看这里哦~工作室所有的黑科技的用法都在这里哦
published: true
date: 2019-12-07T11:41:46.382Z
tags: 
---

# 5 A.M. Studio 技术组工作手册 - 群晖NAS

***说明：本文档为5 A.M. Studio技术组的工作手册，截止至2019.11.25，工作室的黑科技的使用方式都在里面***。

***本文档内的所有账号和密码都采用了BASE64加密方式，请自己百度找解码器！！！***

**Author: GamerNoTitle | Updated Time:2019-11-30**

**Copyright © 2019 [GamerNoTitle](http://bili33.top)**

---

反正就是存储东西的地方，就你们平常用的[\\\172.52.5.6](\\172.52.5.6)和[\\\172.52.5.5](\\172.52.5.5)

登录界面请直接访问[http://172.52.5.6](http://172.52.5.6:5000)，然后可以通过我的账户登陆，但是请不要用我的管理员权限做熊孩子！
账号如下：
``Account: YmlsaTMz``
``Password: NDQ2NjY4MTRAYmlsaQ==``

在控制面板中，可以创建共享文件夹和用户账户，一般不要给Administrator权限，给members权限即可访问工作用的目录，Administrator有完全管理权！！！这点请千万记住！！！

### (1)磁盘映射

将NAS映射到本地磁盘的方式（首先请确保你有对应的权限！！！）：

![](/img/1-1-1.png)

在图中的红色地址栏中输入\\\172.52.5.6，如果你能进入像下面这样的这样的窗口的话就证明你的账号可用

![](/img/1-1-2.png)

然后在我的电脑中，使用上面的映射网络驱动器，在里面输入``\\172.52.5.6\<目录>``或者``\\172.52.5.5\<目录>``即可！

### (2)添加账户

首先访问http://172.52.5.6:5000或者http://172.52.5.5:5000，会进入如下的管理界面

![](/img/1-2-1.png)

然后登陆一个具有管理员权限的账户，登陆成功后会进入管理界面（如图）

![](/img/1-2-2.png)

然后点击管理面板，就右边这个东西![](/img/1-2-3.png)

就会看到这样的窗口

![](/img/1-2-4.png)

点击用户账号，然后点上面的新增![](/img/1-2-5.png)

就会进入下面的窗口

![](/img/1-2-6.png)

名称填写登录用的名字，密码就是密码嘛，这个不用说了

群组如图勾选

![](/img/1-2-7.png)

剩下的就直接下一步点点点就好了，这样你就成功地创建了一个账户