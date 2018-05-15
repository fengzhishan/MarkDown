###Welcome to use MarkDown

### 水平分割线 demo 



    <hr>horizontal rule
    

---
    <hr>horizontal rule--- 王顶老师更多的使用3个-
注意三个---的方式生成分割线，上一行如果是文字的话，需要空行，否则形成文字的二级标题效果  

比如:  
hello
---


***
    <hr>horizontal rule***


___
    <hr>horizontal rule***



### HTML 代码 demo

<p align="center">hello world</p>
hello world
<hr><hr>
<img src="images/002.jpg" alt="风景 - 玉米地"/>
  
<p align="center">
<img src="https://www.baidu.com/img/bd_logo1.png" alt="百度 - logo"/>
</p>

html图片语法：  
<img src="https://www.baidu.com/img/bd_logo1.png" alt="百度 - logo"/>  

markdown图片语法    
![][baidu_logo]

---
markdown语法无法与html语法混用(html的段落标签与markdown的图片标签)  
<p align="center">
![][baidu_logo]
</p>

---


### 表格 demo  


精简表格在Hbuilder没有效果，在GitHub上可以看到效果

- 普通表格(最常用)
|这是一个     |   很好玩的|    表头|
|----       |-----|    ----|
|很       |好       |     玩 |


- 左、右、居中对齐
|这是一个     |   很好玩的|    表头|
|----|:---:|---:|
|**大学最后一个月哎**       |![][baidu_logo]|     *天天玩，真带劲* |
|***1***  | 2|~3~|

- 精简表格(HBuilder无法显示效果)  
这     |   是|    表头
----|:----:|    ---:
现在很热为什么？       |今天下了好几场雨，天气闷热       |     打法 是发好吧  


### GFM demo  
github flavore markdown

- task list
- [ ] task1
- [ ] task2
- [x] task3

:smile:

[baidu_logo]:https://www.baidu.com/img/bd_logo1.png 