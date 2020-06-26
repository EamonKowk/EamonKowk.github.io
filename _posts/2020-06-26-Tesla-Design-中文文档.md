---
layout:     post
title:      Tesla Design中文文档
subtitle:   Tesla中Linux系统的设计规范
date:       2020-06-26
author:     EamonKowk
header-img: img/tag-bg-o.jpg
catalog: true
tags:
    - 设计
---

# Tesla Design 中文文档（非官方）

![](https://asset.mozhua.org:444/Media?name=AE8D2A0127DC9FC6377378CB53B7861F.png)

**由EamonKowk撰写，未经授权禁止转载。**

# 1.介绍

Tesla Design（简称TD），是Tesla汽车系统的设计规范。

它以简单，优雅，易用著称。

没有过于复杂的概念，一般人都可学会。

# 2.基础项

## 2.1 字体

目前我所寻找到的与Tesla系统最相像的字体为**汉仪正圆**。

![](https://asset.mozhua.org:444/Media?name=41A817E263C17CE459C068034FD75EC8.png)

TD中所有字体为**汉仪正圆65W**。

## 2.2 颜色

### 2.2.1 基本色

TD中有四种基本色：

|  颜色16进制代码   | 用途  |
|  ----  | ----  |
| #FFFFFF（白色）  | 底色 |
| #000000（黑色）  | 底色，字体色 |
| #F4F4F4（浅灰）  | 应用底色 |
| #DDDDDD（深灰）  | 元素底色 |

![](https://asset.mozhua.org:444/Media?name=16BF3460ABA80BF38B092C4AD43CC85B.png)

### 2.2.2 其他颜色

绿色：#05E256

蓝色：#3D6CDC

红色：#EE5239

橙色：#D99453

棕色：#56483B

## 2.3.圆角

TD中有两种圆角度：

在宽116px，高28.4px的按钮中，圆角度：

![](https://asset.mozhua.org:444/Media?name=B0D874EC3034186D3F84807BE31F8563.png)

**在大小不一的元素中，可酌情调整圆角度。**

# 3.元素

## 3.1 按钮

### 3.1.1 普通按钮

![](https://asset.mozhua.org:444/Media?name=3419B3323C471739464DCB6D06812C76.png)

### 3.1.2 长型按钮

长型按钮指的是长度≥150px的按钮。

![](https://asset.mozhua.org:444/Media?name=8106E627D4BF263622A77E85B9F03F09.png)

### 3.1.3 TF按钮

TF按钮指的是有“按下”和“松开”两种状态的按钮。

松开：

![](https://asset.mozhua.org:444/Media?name=D974D48591459106C9489B7C3BDF4EE7.png)

按下：

![](https://asset.mozhua.org:444/Media?name=E1387C9F4E8785E093E33E48EAF57F3A.png)

## 3.2 侧边栏

![](https://asset.mozhua.org:444/Media?name=47718A96AB2527C09E8F7BA2BBE6F922.png)

## 3.3 滑杆

![](https://asset.mozhua.org:444/Media?name=77ABE2FB9C1222DE574058C36AC19A58.png)
