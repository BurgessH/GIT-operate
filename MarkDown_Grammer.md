# 标题和次级标题

## 标题  
### 标题1  
标题1：  
===  

## 段落  

标题和段落之间需要空行，段落与段落之间也需要空行隔开；  
我是BurgessH,正在学习Github开源社区的技术和文档；  
我的QQ号码是20.  

## 强调

我是*斜体*字体样式，我是**粗体**字体文字样式，我是***粗体加斜体***文字样式，删除线~~字体样式~~。  

_斜体——，__粗体__, ___粗体加斜体___;

安装GFM viewer  


### 无序列表  
* Name: BurgessH  
* QQ: 514980339  
等价于：  
- Name: BurgessH  
- QQ: 514980339  
二级列表：2space - ;  
  - Name1:  
  - QQ1:  
    - Name2:
    - QQ2:
    
### 有序列表
1. Name:BurgessH  
2. QQ:514980339  
3. Email: 2042877026@qq.com


# 链接 Demo
## 内嵌式链接  
- 外部链接：[百度](http://www.baidu.com)；
- 内部链接：链接仓库的其他文件：[list](list.md)；
- 内部链接：链接本文档的其他部分；[代码块demo](demo1.md#代码块-demo);

## 引用式链接   
- 外部链接：[百度]；
- 内部链接：链接仓库的其他文件：[list]；
- 内部链接：链接本文档的其他部分；[代码块demo];

# 图片Demo 
## 图片内嵌式链接： 
- 外部图片
![百度](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png "百度网站")
- 仓库内的图片
![Selenimopen](open.png)

## 引用式链接  
- 外部图片:  
![百度](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png)
- 仓库内链接:  
![open_png](open.png)


# 引用Demo  
 > 这是一个引文。  
 
 	--出自《出处》
 	
## 多重引用
>>> 多级引用内容

# 代码块demo  

- 行内代码  
这个代码中用来声明变量`var = 10`, 打印变量内容为`console.log()`函数调用；

- 块式代码
```javascript
var = 10;
console.log(a);
```
  - 
    var = 20;
    console.log(a);

# 水平分割线Demo
	<hr> horizontal Rule 
	
---
	<hr> horizontal Rule 
***
	<hr> horizontal Rule 
___

# HTML代码Demo
<p align='center'>Hello World!</p>

# 表格Demo
|这	 |是		 |表头   |
|:-- |:---:|----:|
|cell|cell2|cell3|
|**row1**|row2 |*row3*|


# GFM (Github flvored Markdown) Demo
##task list
- [x] task1
- [] task2
- [x] task3
##emoji 表情符号

# 基本强调样式
 - **加粗**
 - *倾斜*
 - ~~删除~~  
# 混合强调样式
 - ***加粗倾斜***
 - **~~加粗删除~~**
 - *~~倾斜删除~~*  
 - ***~~加粗倾斜删除~~*** 
  
# 图片链接
## 基本文字
[百度](http://www.baidu.com)

## 基本图片
![百度](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png "百度网站")

## 图片链接
[![](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png "百度网站")](http://www.baidu.com)

### 引用式链接
[![][baidu_logo]][baidu]


## 多级有序列表
### 如何打断（空行间多个文字）、续号（4空格缩进）多级列表  
1. item1  
  1.1. miss  
  1.2. miss  
  1.3. miss  
  
    lostone

2. item 2
3. item 3
4. item 4



<!--以下是本文中的链接 -->

[baidu]: http://www.baidu.com
[baidu_logo]: https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png 
