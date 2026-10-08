---
title: C语言-HelloWorld
banner: >-
  https://cdn.jsdelivr.net/gh/DimMeteor/Dim-picture/picgo/Minecraft_Fall_Drop_Campaign_Key_Art_DotNet_Downloadable_Wallpaper_414x414.png
sticky: false
comment: false
date: 2026-10-09 00:06:15
tags:
categories: C语言
excerpt: 实现在cmd打印HelloWorld的代码
---

## 总代码
``` bash
#include <stdio.h>

int main()
{
	printf("Hello World!\n");
	
	return 0; 
}
```
注解：
#include <stdio.h>
表示该代码内引用头文件stdio.h的内容(相当于import package)
int main(){}
该代码的主窗口，让机器知道从这个地方开始读取与执行
printf("Hello World!\n");
打印内容
return 0; 
返回0，如果是0,那么返回值为true，如果是1，那么返回值为false
