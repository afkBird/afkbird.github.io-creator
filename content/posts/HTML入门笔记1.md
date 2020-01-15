---
title: "HTML入门笔记1"
date: 2020-01-15T22:42:46+08:00
draft: false
---
## HTML是谁发明的
HTML的英文全称是 Hypertext Marked Language，即超文本标记语言。HTML是由Web的发明者 Tim Berners-Lee（李爵士）和同事 Daniel W. Connolly于1990年创立的一种标记语言，它是标准通用化标记语言SGML的应用。用HTML编写的超文本文档称为HTML文档，它能独立于各种操作系统平台(如UNIX， Windows等)。使用HTML语言，将所需要表达的信息按某种规则写成HTML文件，通过专用的浏览器来识别，并将这些HTML文件“翻译”成可以识别的信息，即现在所见到的网页。

## HTML起手式
``` html
 <!DOCTYPE html> <!--声明文档类型 -->
<html lang="en"> <!-- html标签 -->
<head>
    <meta charset="UTF-8"> <!--文件的字符编码  -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!--禁用页面缩放，兼容手机-->
    <meta http-equiv="X-UA-Compatible" content="ie=edge"> <!--告诉ie使用最新内核-->
    <title>Document</title> <!--标题-->
</head>
<body>
    
</body>
</html> 
```

## 常用的表章节标签
- `<h1>,<h2>,<h3>,<h4>,<h5>,<h6> `:从大到小表示标题
- `<section> `:章节
- `<p>`:段落
- `<header>`:用于置顶的文章之外的内容
- `<footer>`:用于底部的文章之外的内容
- `<main>`:主要内容
- `<asaide>`:旁枝内容
- `<div>`:用于划分内容

## 全局属性
- `class`:为元素分类
- `id`:类似class，但适用于只出现一次的元素
- `contenteditable`:使网页内容可以被编辑
- `hidden`:隐藏元素
- `sytle`:定义元素的样式
- `title`:鼠标移至元素上时会显示`title`的内容
- `tabindex`:自定义tab键的控制顺序

## 常用的内容标签
- `<ol>+<li>`:有序列表
- `<ul>+<li>`:无需列表
- `<dl>+<dt>+<dd>`:带描述的列表
- `<pre>`:其内的空格和换行不会被忽略
- `<hr>`:分割线
- `<br>`:换行
- `<a>`:链接标签
- `<em>`:加粗（指特意强调）
- `<strong>`:加粗（指其本身很重要）
- `<code>`:代码框
- `<quote>`:行内引用
- `<blockquote>`:块级引用