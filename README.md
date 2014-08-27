


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
</pre>

↑此处代码有失误,我这里混合使用"*"和"**"会出现错误.
所以在下面的代码中,我实际使用的是"_"和"**"的结合

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
  * Item 2b
</pre>

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
  * Item 3b
</pre>

**显示结果**

1. Item 1
2. Item 2
3. Item 3
  * Item 3a
  * Item 3b

####链接

**语法格式**

<pre>
http://github.com - automatic!
[GitHub](http://github.com)
</pre>

**显示结果**

http://github.com - automatic!
[GitHub](http://github.com)

####引用

**语法格式**

<pre>
As Kanye West said:
> We're living the future so
> the present is our past.

</pre>

**显示结果**

As Kanye West said:

> We're living the future so
> the present is our past.

####Inline code

**语法格式**

<pre>
I think you should use an
`<addr>` element here instead.
</pre>

**显示结果**

I think you should use an
`<addr>` element here instead.

####GitHub Flavored Markdown

Github使用了Markdown的独特版本,这使它具备了一些特性.

其中的一些特性只在只有在Issues和Pull Requests的描述和评论中有效.

####高亮文字

**语法格式**

<pre>
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
</pre>

**显示结果**

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
####表格
**语法格式**
<pre>
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
</pre>
**显示结果**

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

######总结说来,Markdown用起来简单,但是要注意空格和分行,特别是在与html代码结合使用的时候.
_我在上面的例子中,由于<pre></pre>没有换行,出了不少错误_
