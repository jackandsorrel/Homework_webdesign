# 董阳兰的网站作业
>HTML+CSS制作的个人博客网页
## 任务
根据大作业的要求，有以下四个任务需要完成：
1. 画出计算机各门课程之间的关系图；
2. 集成计算机的参考资料；
3. 写出对计算机专业的认识；
4. 写出学业规划。

## 文件组成
* 网站`html`文件
* 网站布局文件`css`
* 内嵌学习资料(`PPT`等)
* 网站图片

## 网站介绍
### 一、头部
头部主要构成为文字`(welcome to my page)`和图片，实现方式如下：
```html
<div id="logo">
WELCOME </a><span style="font-style: italic;font-size: 16px;"><span style="color: 
white;"> TO  MY </span> PAGE</span>
</div> 
```
### 二、导航栏
导航栏中有`MOTTO, RESOURCES, VIDEOS, PLANS, THOUGHTS, GRAPH,` 点击可以实现导航功能。
```html
<li><a href="#motto">MOTTO</a></li>
<li><a href="#resource">RESOURCES</a></li>
<li><a href="#video">VIDEOS</a></li>
```
### 三、主体
主体分为左右两栏，采用`layout`文件中定义的格式进行布局，并使用`<div>`进行分块。
以第一个模块`MOTTO`为例：
```html
<div class="title">
	<h2><a id="motto">MY MOTTO</a></h2>
</div>
<div class="content" style="border: none;">
	<br>EXCELLENCY <br> PERSERVERANCE <br>
		CONTINUOUS EFFORT MAKES SUCCESS
</div>
```
>代码中使用的`title,content`等在文件`layout`中，稍后展示。

`VIDEOS,RESOURCES`实现链接：
```html
<li><a href="PPT/DS0-绪论.pptx">DS0-绪论.pptx</a></li>
```
```html
<li><a href="https://www.bilibili.com/video/BV1nJ411V7bd?from=search&seid=12320210742090248606&spm_id_from=333.337.0.0" target="_blank">数据结构</a></li>
```
>`target="_blank"`可以在新的页面中打开网页。

### 四、下框
下框的实现较为简单，此处不再进行赘述。
```html
<div id="footer">
    Copyright (c) 2022 董阳兰 2206123611
```

##css文件
定义了以下几种样式：
* **header**，定义头部的尺寸和字体；
* **body**，定义标题布局；
* **nav**，定义导航栏布局；
* **content**，定义主题内容字体样式；
* **footer**，定义下框布局。
## 最终效果
### 效果图一

![效果图一](https://github.com/jackandsorrel/Homework_webdesign/blob/main/img1.png)

### 效果图二

![效果图二](https://github.com/jackandsorrel/Homework_webdesign/blob/main/img2.png)

### 效果图三

![效果图三](https://github.com/jackandsorrel/Homework_webdesign/blob/main/img3.png)
