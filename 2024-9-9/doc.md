<!--
	FileName : doc.md
	By : yzx
	MakeTime : 2024年9月11日 下午 07:47:20
	Copyright (C) 2024-2025 openGames 
-->
# 2024年9月9日开发文档
## 1.标题的作用
标题的作用是让用户快速了解文档的结构与大致信息。<br>它是通过`<h1>`~`<h6>`标签进行定义的,`<h1>`标题是最大的一号标题;`<h6>`标题是最小的六号标题。当为文字添加标题标签后，它会独立成一行显示。
## 2.水平线
水平线主要是用来分隔网页中的内容。<br>水平线标签`<hr>`是一个单标签，其作用是在HTML页面创建水平线。
## 3.段落
HTML段落是通过`<p>` `</p>`标签进行定义的
## 4.换行
要在不产生一个新段落的情况下换行，需使用`<br/>标签`
## 5.无序列表与有序列表
- **无序列表**
无序列表就是列表结构中的列表项，没有先后顺序的列表方式。大部分网页中的列表均采用无序列表，使用`<ul>` `</ul>`标签定义。包含的列表使用`<li>` `</li>`标签定义，列表项默认的符号为小圆点,要改变符号类型或去除符号，可使用CSS属性进行调整
- **有序列表** 有序列表在列表项前都有编号，因此浏览者可以清晰地了解每项的顺序，其中`<ol>` `</ol>`标签用来定义有序列表，包含的列表用`<li>` `</li>`标签定义，默认序号是1.2.3
## 6.定义列表
定义列表是项目及其注释的组合<br>
`<dl>` `</dl>`标签定义列表<br>`<dt>` `</dt>` 标签定义每个列表项的名称<br>`<dd>` `</dd>`标签表示每个定义名称的详细内容。
## 7.图像标签
HTML插入图像是通过`<img />`标签进行定义的。<br>它是一个单标签，由图像标签`<img />`和属性构成,其中src属性用来表示图片的源地址，是必不可少的。