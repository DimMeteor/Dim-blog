---
title: C语言-IDE的使用与疑难
banner: >-
  https://cdn.jsdelivr.net/gh/DimMeteor/Dim-picture/picgo/Minecraft_Fall_Drop_Campaign_Key_Art_DotNet_Downloadable_Wallpaper_414x414.png
sticky: false
comment: false
date: 2026-10-09 00:13:23
tags:
categories: [C语言,工具]
excerpt: 陈列了多个支持编写C语言程序的集成工具，并展示了环境配置方法与遇到的问题解决
---
## Dev-C++
作为老牌的且专属于C++集成工具,常见于竞赛项目的代码编写,但如果Win11系统对软件进行了缩放处理,该软件的UI将会模糊.
### UI模糊
#### 方法一
我们可以直接将系统的缩放改回正常的100%缩放↓
**右键桌面空白处→显示设置→缩放与布局→缩放**
#### 方法二(推荐)
我们可以通过启动程序时的兼容性设置，使得系统在**保留缩放设置**的前提下修复软件UI界面模糊的问题↓
**右键桌面的快捷方式→打开文件位置→找到应用程序本体→右键.exe文件→属性→兼容性→设置内的更改高DPI设置→勾选“程序DPI”内的“使用此设置修复此程序的缩放问题······”以及将“程序DPI”内的“执行以下操作时使用为我的······”切换为打开此程序→勾选“高PDI缩放替代”内的“替代高DPI缩放行为”,将“缩放执行”设置为“应用程序”**
以下是示例图片
![示例图片](https://cdn.jsdelivr.net/gh/DimMeteor/Dim-picture/picgo/Dev-C%2B%2B_compressed%20(2).png "Dev-C++")
### 编译+运行代码快捷键
``` bash
Ctrl+F5
```

## VS code
这是一个文本编辑器,是蓝色图标的,{% img [vscode图标] https://cdn.jsdelivr.net/gh/DimMeteor/Dim-picture/picgo/vscode.ico 30 30 %}
### C语言环境配置
正常来讲，他只是一个**高级版的记事本**,不支持直接进行代码编译与程序运行，但是我们可以通过安装社区内的插件，来让我们的VScode成为支持C语言编程的集成工具↓
**直接在VScode的扩展管理搜索"C/C++"**
以下是该扩展的链接↓
``` bash
https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools
```
### 编译+运行代码快捷键
``` bash
Ctrl+F5
```

## CLion
这是从IntelliJ IDEA中分割出来的独立的C语言集成工具,是IntelliJ家的
他适用于编写大型项目,目前本人还没到那个程度:\)
### 免费激活使用
另外附上IntelliJ全系列软件激活密钥免费获取网站↓
``` bash
https://ckey.run/
```


## 鸣谢
[CSDN:Dev-C++ 代码编辑区字体模糊、界面显示不清晰怎么办？](https://ask.csdn.net/questions/9781534)
[Icon Viewer,提取exe程序图标的软件](https://www.botproductions.com/iconview/download.html)
[VScode C/C++扩展](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
[IntelliJ全系列软件激活密钥免费获取网站](https://ckey.run/)