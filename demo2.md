#Markdown语法

## 一、链接demo
### 内嵌式链接
-外部链接  
[百度](http://baidu.com)  
方括号里链接名字，圆括号里链接地址

-内部链接  
1、链接仓库里的其他文件
[demo1](demo1.md)  
2、链接本文档的其他部分
[代码块](demo2.md#代码块-demo)

###引用式链接

-外部链接  
写法一：[百度]  
写法二：[百度][baidu]
-内部链接：
1、链接仓库里的其他文件
[demo1] 
2、链接本文档的其他部分
[代码块demo](demo2.md#代码块-demo)


##二、图片demo

  ![alt](url text) 这里的感叹号是英文半角下的。  
方括号：alt:图片不能正常显示的时候显示的文字内容  
圆括号：URL图片地址，txt指鼠标移动到图片上的时候浮动出来的文字信息。  
###外部图片：
 ![baidu](https://www.baidu.com/img/bd_logo1.png?where=super"百度网站")
###内部图片：  
![](images/图片名.png)
###图片的引用式链接：  
外部图片：
![baidu][baidu_log] 
内部图片：  
![][open_png]


##三、引用demo

>这是一个引文
      
                  ——出自《出处》
###多次引用
>>>这是多重引文

##四、代码块demo

###行内代码

这个代码中用来声明变量是`var=10;`打印变量时是`console.log(a);`函数的调用。

###块式代码
方法一：使用反引号
```
var a=10;
console.log(a);
```

注：开头和结尾各三个反引号，反引号是在数字键左边的按键。（英文半角下的）  
语法高亮：在第一排三个反引号之后加上语言名字
```javascript
var a=10;
console.log(a);
```

方法二：代码前面打四个空格  
此种方法局限：不能打上语言名字使其高亮。
    var a=10;
    console.log(a);

<!--- 下面是本文档中用到的链接-->
[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[demo1]:demo1.md
[代码块demo]:demo2.md#代码块-demo

[baidu_log]:https://www.baidu.com/img/bd_logo1.png?where=super
[open_png]:images/open.png
