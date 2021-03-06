[toc]
### HTML链接

HTML 使用超级链接与网络上的另一个文档相连。几乎可以在所有的网页中找到链接。点击链接可以从一张页面跳转到另一张页面。

#### HTML 超链接（链接）

HTML使用标签 &lt;a>来设置超文本链接。

超链接可以是一个字，一个词，或者一组词，也可以是一幅图像，您可以点击这些内容来跳转到新的文档或者当前文档中的某个部分。

当您把鼠标指针移动到网页中的某个链接上时，箭头会变为一只小手。

在标签&lt;a> 中使用了==href==属性来描述链接的地址。

默认情况下，链接将以以下形式出现在浏览器中：

+ 一个未访问过的链接显示为蓝色字体并带有下划线。
+ 访问过的链接显示为紫色并带有下划线。
+ 点击链接时，链接显示为红色并带有下划线。

#### HTML 链接语法

链接的 HTML 代码很简单。它类似这样：

```html
<a href="url">链接文本</a>
```

href 属性描述了链接的目标。

##### 实例
```html
<a href="https://www.runoob.com/">访问菜鸟教程</a>
```
上面这行代码显示为：[访问菜鸟教程](https://www.runoob.com/)

点击这个超链接会把用户带到菜鸟教程的首页。

**提示:** *"链接文本"* 不必一定是文本。图片或其他 HTML 元素都可以成为链接。

#### HTML链接-target属性

使用 target 属性，你可以定义被链接的文档在何处显示。

下面的这行会在新窗口打开文档：

```html
<a href="https://www.runoob.com/" target="_blank" rel="noopener noreferrer">访问菜鸟教程!</a>
```

#### HTML链接-ID属性

我们可以在一个网页上通过链接跳到指定位置，就需要在指定位置设定一个ID

实例：

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
</head>
<body>

<p>
<a href="#C4">查看章节 4</a>
</p>

<h2>章节 1</h2>
<p>这边显示该章节的内容……</p>

<h2>章节 2</h2>
<p>这边显示该章节的内容……</p>

<h2>章节 3</h2>
<p>这边显示该章节的内容……</p>

<h2><a id="C4">章节 4</a></h2>
<p>这边显示该章节的内容……</p>

<h2>章节 5</h2>
<p>这边显示该章节的内容……</p>

<h2>章节 6</h2>
<p>这边显示该章节的内容……</p>

<h2>章节 7</h2>
<p>这边显示该章节的内容……</p>

<h2>章节 8</h2>
<p>这边显示该章节的内容……</p>

</body>
</html>
```

点击<ins>查看章节 4</ins>就可以跳到章节4<br>这就是ID属性的作用！