# 在Genymotion安装QPython

## 一、安装Genymotion

1.注册账号

首先打开[https://www.genymotion.com/account/login](https://www.genymotion.com/account/login),点击<b> sign in</b>，注册一个账号。

![](images/5.jpg)

2.下载并安装应用

注册好以后，点击[https://www.genymotion.com/download](https://www.genymotion.com/download),注意要下载<b> with VirtualBox</b>。下载好之后就一步一步地安装应用，还要记得安装VirtualBox。

![](images/1.jpg)

3.打开应用

打开安装好的genymotion,点击<b> Settings</b>,再点击<b>Sign in</b>,把刚刚注册的信息填上。

![](images/2.jpg)

![](images/3.jpg)

4.设置信息

打开<b>Setting</b>，点击<b>ADB</b>，在<b>Browse</b>里选择安装adb的文件。

![](images/7.jpg)

5.添加虚拟机

在<b>Add</b>里面找到你喜欢的一款虚拟机，然后双击它，就可以添加属于你的一台虚拟机了。

![](images/8.jpg)

![](images/9.jpg)

## 二、在虚拟机安装qpthon

* 虚拟机上方有个IP地址，复制下来

![](images/13.jpg)

* 用adb连接这个IP地址，```adb connect 192.168.185.101``` 

![](images/10.jpg)

* 查看QPython目录的文件

![](images/11.jpg)

* 安装QPython3L_135.apk，```adb install QPython3L_135.apk```

![](images/12.jpg)

![](images/14.jpg)

至此就已经安装成功了。
