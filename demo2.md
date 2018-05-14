###Welcome to use MarkDown

## 链接 demo

### 内嵌式链接  
- 外部链接：[百度](https://wwww.baidu.com)  
- 内部链接：链接仓库的其他文件：[demo1](demo1.md)  
- 内部链接：链接本文的其他标题：[demo1 代码块](demo2.md#代码块 demo)  
需要注意的是 引用的空格通常使用-替代,在内嵌式链接中可以使用空格，因此推荐使用-代替空格

### 引用式链接  
- 外部链接：[百度]
- 外部链接：[百度a][baidu]  
- 内部链接：链接仓库的其他文件：[demo1]
- 内部链接：链接本文的其他标题：[demo1 代码块]  


## 图片 demo    

四个空格代码与-无序列表冲突  
<!--  - 图片markdwon语法   -->


    ![alt](url text)  

- 图片markdwon语法  
``` 
![alt](url text)
```
使用反引号代替四个空格代码，就与-无序列表不冲突了 
- 引用外部图片  
![baidu](https://www.baidu.com/img/bd_logo1.png "这是一个图片")  
注意最后text需要使用"" 双引号 引起来，否则这个语法就会不好使，成为一个链接

- 引用内部图片  
![picture](images/002.jpg "风景图片")


## 引用 demo
> 这是一个引文  

                             -- 出自《道德经》
<!--  这样写会有阴影 --> 
-- 出自《山海经》

### 多重引用
>首层引用
>>二层引用
>>> 这是一个多重引文


## 代码块 demo

- 块式代码  
```javascript
var tag = 10;
console.log(tag);
``` 
必须隔开，四个空格不能与三个反引号连用，否则四个空格无法达到代码块的效果  

    var tag = 10;  
    console.log(tag);  
- 行内代码
首先定义一个变量`int a = 1`,然后控制台输出 `System.out.println(a)`查看结果;


<!-- 下面是本文档的链接 -->
[百度]:https://wwww.baidu.com 
[baidu]:https://wwww.baidu.com 
[demo1]:demo1.md
[demo1 代码块]:demo2.md#代码块-demo   
但是在引用是链接里 空格就会导致 引用式链接不好用
