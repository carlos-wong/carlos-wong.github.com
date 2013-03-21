---
layout: post
title: "第一篇博客"
description: "关于自己写第一篇博客的过程"
category : jekyll
tags :
- 教程
- 文章
---
{% include JB/setup %}

##第一篇静态博客



如何使用jekyll发布文章？ 在命令行中输入 rake post title="name" 不能使
用中文可能还是因为是字符编码的问题。


如何为一篇文章添加多个标签在md文件的开头描述中

    tags:
    - tag1
    - tag2
    
默认的模板文件是

    tags:[ ]
    
这样容易产生误导
