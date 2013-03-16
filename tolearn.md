---
layout: page
title: Markdown编辑范例
tagline: 看code
---
{% include JB/setup %}



标题
---------------
### this is a level-3 header ### 

This is an H1
=============

This is an H2
--------
~~~~~~~~~~~~~~~~~~

强调
-----------
*single asterisks*


_single underscores_ 

~~~~~~~~~~~~~~~~~

**double asterisks**

__double underscores__ 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

分隔线
---------
* * *
1

***
2

*****
3
- - -
4

--------------------------------------- 
5

区块引用
--------------
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

列表
---------
*   Red
*   Green
*   Blue 



1.  Bird
2.  McHale
3.  Parish 


代码
---------
Use the `printf()` function.


	<div class="footer">
        &copy; 2004 Foo Corporation
	</div> 

链接
-----------
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute. 

~

This is [an example][id] reference-style link.

  [id]: http://example.com/  "Optional Title Here" 


<http://example.com/> 


I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search" 

图片
------------
![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title") 

~~~

![Alt text][id]

  [id]: url/to/image  "Optional title attribute" 


转义字符 
--------
利用反斜杠来插

\*literal asterisks\* 

\\   反斜线

\`   反引号

\*   星号

\_   底线

\{\}  花括号

\[\]  方括号

\(\)  括弧

\#   井字号

\+   加号

\-   减号

\.   英文句点

\!   惊叹号 