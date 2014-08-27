


怎样使用Markdown
======================

Markdown是一款基于Github平台的、简单易用的规范文章格式的语法。


**你能从这篇文章学到什么：**
* 使用Markdown转变传统样式编辑的文本
* 使用Markdown进行文本编辑
* 应用Markdown的个性扩展

####什么是Markdown？
[Markdown](http://daringfireball.net/projects/markdown/)是一种在web中编辑文本样式的方式。你可以利用Markdown控制文件的显示方式；对文字进行加粗或使其倾斜，添加图片，创造列表······简单来说，Markdown就是一段普通的文本加上一些特殊符号，比如<code>#</code>,<code>*</code>。

####你可以使用Markdown的地方包括但不限于：
* [Gists](https://gist.github.com/)
* Pull Requests 和 Issues的时候
* 以<code>.md</code>和<code>.markdown</code>为扩展名的文件中

###例子
<a href="# ">Text</a>

<pre id="text">It's very easy to make some words **bold** and other words *italic* with 
Markdown. You can even [link to Google!](http://google.com).
</pre>

It's very easy to make some words **bold** and other words *italic* with 
Markdown. You can even [link to Google!](http://google.com).

###语法导引

下面的语法你可以在Github的任意地方使用

###Headers
**语法格式**
<pre># This is an h1 tag
## This is an h2 tag
###### This is an h6 tag
</pre>

**显示结果**

# This is an h1 tag
## This is an h2 tag
###### This is an h6 tag

####Emphasis
**语法格式**
<pre>*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

*You **can** combine them*
↑此处代码有失误,我这里混合使用"*"和"**"会出现错误.
所以在下面的代码中,我实际使用的是"_"和"**"的结合</pre>

**显示结果**

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

####Lists
#####无序
**语法格式**
<pre>
* Item 1
* Item 2
  * Item 2a
  * Item 2b</pre>
**显示结果**
* Item 1
* Item 2
  * Item 2a
  * Item 2b

####有序
**语法格式**
<pre>1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b</pre>
**显示结果**
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

####图片
**语法格式**
<pre>![GitHub Logo](http://imgcache.chinayes.com/cnews/20100324/201003240917356175103.jpg)
Format: ![Alt Text](url)</pre>
**显示结果**

[GitHub Logo](http://imgcache.chinayes.com/cnews/20100324/201003240917356175103.jpg)
