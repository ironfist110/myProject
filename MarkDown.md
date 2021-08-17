---
title: "MarkDown语法，front-matter部分"
author: 王聪
date: 2020年4月7日 
output: word_document
/* reference_docx: mystyles.docx
*/
---
# MarkDown 语法
### 一、字体
1. 斜体    *这是一个斜体的例子*
2. 粗体    **这是一个加粗体的例子**
3. 粗斜体 ***这是一个粗斜体的例子***

### 二、链接
1. 行内式    [链接地址为](http://www.baidu.com "百度")
2. 参考式    [常用网址][1]
3. 自动链接如：<http://www.baidu.com>,<xywang7@163.com>
[1]:http://www.google.com
### 三、列表
1. 无序列表
* 无序列表一
+ 无二列表三
2. 有序列表
（略）  
-[] 任务列表1  
-[x] 任务列表2  
3. 定义型列表

MarkDown
:MarkDonw 是一种解释性语言，是 HTML 的简化版。

### 四、引用
<pre>悄悄的，我走了，已如我悄悄的来。
我挥一挥衣，不带走一片云彩。
</pre>
>> 另外一种方式 引用用、>的方法
>>>>更深一个层次的引用
### 五、插入图像
![插入图片](Images/git-process.png "图")
### 六、代码
1. 单位代码<br>
<code>Printf("hello world"); </code>
2. 多行代码
<pre>
<code>
# includ io.*
funtion()
{
    printf("hello world!“）；
}
</code>
</pre>
```
# includ io.*
funtion()
{
    printf("hello world!“）；
}
``` 
### 七、注脚
<font  class="aa" color=red>字体红色</font>
使用 Markdown[^1] 可以效率的书写文档，直接转换成 HTML[^2]， 你可以使用简书或者支持 Markdown 的编辑器进行书写。
[^1]:Markdown 是一种纯文本标记语言
[^2]:HyperText Markup Language 超文本标记语言
### 八、针对vscode markdown all in one的快捷键说明
黑体  **黑体**  ctrl+B
斜体  
列表  
### 八、表格
表格我用HTML来制作简易表格
<table border = 1 ><tr><td>第一行、第一列</td><td>第一行、第二列</td><td>第一行、第三列</td></tr>
<tr><td>第二行、第一列</td><td></td><td></td></tr>
</table>
<hr>

