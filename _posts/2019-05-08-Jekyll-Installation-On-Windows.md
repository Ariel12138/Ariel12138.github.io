---
layout: post
title:  在 Windows 系统安装jekyll
date:   2019-05-08 00:00:00 +0800
categories: Jekyll的安装
tag: Jekyll
---

* content
{:toc}




## 安装jekyll
在windows上安装jekyll  


### test right sidebar
测试页面导航



## 卸载jekyll

### right sidebar test success

#### this is h4
balabalabal  
balabalabal  

```html
<html>
    <div class="navbar">
    </div>
</html>
```
- 将左导航 内容页 和右导航整合
- **测试加粗**

> 虽然设计好看的主题很多。但是真正适合拿来做博客的却不多。中间一直没有找到合适的主题。直到有一天看到Less官网的主题之后，豁然觉得这就是我的博客想要的样子。简单而又不平凡。所以就决定了要把博客迁移到这个主题，然后拿了两天晚上来把这个主题做出来。

>> 在LessOrMore/_posts目录下新建一个文件，可以创建文件夹并在文件夹中添加文件，方便维护。在新建文件中粘贴如下信息，并修改以下的titile,date,categories,tag的相关信息，添加* content {:toc}为目录相关信息，在进行正文书写前需要在目录和正文之间输入至少2行空行。然后按照正常的Markdown语法书写正文。

## liquid介绍

liquid语言可以分为三类，objects，tags，和filters

objects，即标记在页面上显示内容的区域，用两个花括号如 `{{content}}`

tags，为模版创建逻辑和控制流时使用，用{ 和 %围住，可以用tags写条件和循环，tags按照功能可以分为三类，控制流，迭代，和分配变量

filters，用于改变object的输出，在object中使用，并用`|`隔开，如

**Note**：涉及liquid模版语言的%和{ 需要转义

#### 运算符

#### 逻辑真假

字符串，空内容，0等判断为真，nil 和 false 判断为假

#### 数据类型
