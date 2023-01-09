---
title: Unturned未转变者 Windows SteamCMD 2023最新开服教程-全网最全
date: 2023-1-1 17:01:59
cover: https://s2.loli.net/2023/01/01/HdumsMbn8i3JVpZ.jpg
tags: Unturned
categories: 游戏开服教程
---

## 服务器开服要求

- 内存：最少2G，内存越高，可容纳游戏人数越多，根据实际需求增加。
- 网络：最低2M，根据实际用户量适当增加，可适当配置网络防御
- 端口：默认TCP 27015 在服务器后台防火墙开启对应端口

> 如果没有服务器可以使用本地电脑进行搭建有公网ip可以外网联机，没有公网ip就只能局域网小伙伴一起玩耍了。

## 准备工具

[点击下载](https://steamcdn-a.akamaihd.net/client/installer/steamcmd.zip) SteamCMD （如果访问不了就需要使用魔法了)

[点击下载](https://gsf-fl.softonic.com/3a8/2ff/6c396563e808aef56baa9e1ac9b34960d3/npp.8.1.9.Installer.exe?Expires=1637759025&Signature=f8fb1aaa36e1203e3d7094c455eea099b751b5c2&url=https://notepad-plus.en.softonic.com&Filename=npp.8.1.9.Installer.exe)Notepad++ （普通编辑器也不是不行，只要编码不搞错就可以）

## 安装SteamCMD

创建一个SteamCMD文件夹（文件夹的位置根据自己需求创建），将下载好的SteamCMD.exe文件放置文件夹内，

双击SteamCMD.exe启动，等待安装完毕

代码跑完，显示steam> 这时说明SteamCMD已经安装完毕了，文件夹内也会多出很多文件

此时输入以下命令进行匿名登录

```
PLAINTEXT
login anonymous
```

## 安装UNturned服务端

只需在命令行输入以下命令，然后回车

```
PLAINTEXT
app_update 1110390 validate
```

然后就开始下载了，我们默默等待下载完成即可

## 启动服务端

下载完成之后在SteamCMD\steamapps\common\U3DS\找到服务端启动Unturned.exe双击启动

运行一遍之后输入shutdown关闭服务器

启动一次服务器是为了让服务端生成地图和相应的配置文件

## 配置相应文件

在U3DS目录找到Servers文件夹，打开默认服务器文件夹Default

打开服务器文件夹之后，打开server文件夹，里面有一个commands.dat文件

右键使用Notepad++打开编辑文件，按实际需求填入以下指令

| 配置代码    | 功能           | 备注                         |
| ----------- | -------------- | ---------------------------- |
| Name        | 服务器名称     |                              |
| Map         | 地图类型       | 默认PEI                      |
| Password    | 服务器密码     | 公开不填                     |
| Welcome     | 服务器欢迎语   |                              |
| Maxplayer   | 服务器人数     | 根据服务器配置填             |
| Mode        | 服务器难度     | 可填Eazy,Normal,Hard         |
| Perspective | 服务器视角限制 | 可填First,Third,Both,Vehicle |
| PVE         | 开启PVE模式    | 留空为PVP                    |
| Cheats      | 服务器作弊模式 | 开True关False                |
| Port        | 服务器端口     | 默认27015,更改需要开放端口   |

示例

```DART
Name 测试服务器
Map PEI
Password 
Welcome 欢迎加入测试服务器，看到此提示说明可以进入
Maxplayer 10
Mode Eazy
Perspective Both
PVE
Cheats True
Port
```

> 完成之后不要着急开服

## 申请&配置Steam秘钥

> 老版本的话是没有这一步骤的，新版本加入了Steam秘钥，不添加Steam秘钥开服是可以开的，但是玩家进入不了游戏，新版本这一步骤也成为了必要

直接上链接

Steam 游戏服务器账户管理 [点击打开](https://steamcommunity.com/dev/managegameservers)

> 访问不了的话就需要使用魔法了

### 申请条件：

- 账号无违规
- 已绑定手机号
- 账号仓库内有这款游戏

### 配置服务端

申请完之后复制秘钥

找到U3DS\Servers\Default文件夹下的Config.dat文件

使用Notepad++编辑该文件

找到 Login_Token 填入复制好的秘钥

[![image-20230101212732863](https://s2.loli.net/2023/01/01/kVA9q2zBYwdonJ3.png)](https://s2.loli.net/2023/01/01/kVA9q2zBYwdonJ3.png)

配置完成之后双击U3DS文件夹下的Unturned.exe文件即可开服

尽情享受联机带来的乐趣

## 注意事项

使用 Notepad++ 编辑完不要忘记保

开服之后使用ip找不到，检查防火墙，端口有无被占用，实在不行重新安装，重新配置！
