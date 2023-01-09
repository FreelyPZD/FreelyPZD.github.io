---
title: eclipse下载太慢怎么办
date: 2022-12-22 17:01:59
cover: https://s2.loli.net/2022/12/22/RIq2VOepBCPQ81H.png
tags: Java
categories: Java
---

## 为什么下载慢

由于[eclipse](https://www.eclipse.org/)是国外的软件，下载服务器自然也是在国外，国内访问国外服务器速度是非常慢的，有时候还会访问失败，所以就造成了下载速度非常慢

## 高速下载实现思路

本机 —— [eclipse](https://www.eclipse.org/)官方服务器（国外，非常慢）

本机 —— 国内节点（速度恢复正常）

如果下载源在国内，下载速度不就提上来了吗

## 解决方法

> 使用国内下载源，其实官网上面有提供国内的下载源

### 1.打开官网下载界面

![image-20221222183444167](https://s2.loli.net/2022/12/22/rmZhjVSuMFv5NTi.png)

### 2.点击下载软件包

![img](https://s2.loli.net/2022/12/22/2MVkyAfiKWu9Iq8.png)

### 3.选择需要下载的包

[![image-20221222183928078](https://s2.loli.net/2022/12/22/AJ43eo6scvmPFLd.png)](https://s2.loli.net/2022/12/22/AJ43eo6scvmPFLd.png)

[![image-20221222184211302](https://s2.loli.net/2022/12/22/aoEYnQXiDK6tyMm.png)](https://s2.loli.net/2022/12/22/aoEYnQXiDK6tyMm.png)

> 点进去之后我们发现默认选择的是一个国外的节点，这个时候点击下载的话是会非常的慢

### 4.更换China节点下载

[![image-20221222184351001](https://s2.loli.net/2022/12/22/bcsYemhUxCNfuiA.png)](https://s2.loli.net/2022/12/22/bcsYemhUxCNfuiA.png)

[![image-20221222184438700](https://s2.loli.net/2022/12/22/jpQP3yMTfHrzv7n.png)](https://s2.loli.net/2022/12/22/jpQP3yMTfHrzv7n.png)

> 点击显示更多，选择China开头的节点最后点击download即可实现高速下载
> 本篇文章内容不是很多，根据图片操作即可