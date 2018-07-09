# demo3

# 一、水平分割线demo

HTML里面<hr>标记 Horizontal Rule水平分割线  
### 方法一：三个短横线

---
注：三个短横线还可以实现二级标题，要把短横线和上一行内容之间空一行，才能实现水平分割线。  
### 方法二：三个星

***
### 方法三：三个下划线

___
注：HTML语句里的水平分割线的标签也可以实现水平分割线
<hr>
# 二、HTML代码demo
HTML代码可以直接在Markdown里面应用
### 标题居中：
<p align='center'>Hello git!</p>

### 注释：
<!--块注释
-->


# 三、表格demo
  
表格帮助实现数据效果  
|  这  |  是  |  表头  |
|:----|:----:|----:|
| cell1| cell2|cell3|
|**demo1**|demo2|![baidu_log]|  

注：1、在第二行里面，用冒号实现对齐方式，横线左边放冒号是左对齐，右边放冒号是右对齐，两边都放冒号是居中。  
2、书写时竖线不对齐并没有什么影响。  
3、在表格中加图片，在表格中加链接。

## 精简表格：
  这  |  是  |  表头  
----|:----:|----
cell1|cell2|cell3
demo1|demo2|demo3

注：把表格两边的竖线都去掉。
 
# 四、GFM demo
指GitHub实现的具有自身特色的Markdown：github flavored markdown

## 1、task list：任务列表
- item1  
- item2
- item3  

注：在无序列表中，在符号后面加上方括号，方括号里面加上空格，方括号后面加上空格。(即方括号左边、右边、里面都要有空格)方括号里面打上x,显示的是勾选。
- [x] task1 
- [ ] task2
- [ ] task3

## 2、emoji表情符号
:emoji code:Emoji表情
=========
将对应emoji表情的符号码复制后输入你的markdown文本即可显示emoji表情。
如`:blush:`，显示为:blush:

