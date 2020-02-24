---
layout: post
title: Markdown常用语法
categories: [Markdown]
tags: [Markdown]
excerpt_separator: <!--more-->
key: 10000001
---

Markdown基础语法介绍及显示效果展示。测试在本网站中Markdown的显示，Jekyll默认是通过kramdown来解析的，部分显示和Markdown不一致。[详细文档](https://daringfireball.net/projects/markdown/syntax#list)。

<!--more-->

## 标题
#符号的个数表示标题的层级，#后不要忘记空格
```
# 一级标题 h1
## 二级标题 h2
### 三级标题 h3
#### 四级标题 h4
##### 五级标题 h5
###### 六级标题 h6
```
### 显示效果
# 一级标题 h1
## 二级标题 h2
### 三级标题 h3
#### 四级标题 h4
##### 五级标题 h5
###### 六级标题 h6

## 上下文标题
```
AAA
===
BBB
---
```
### 显示效果
AAA
===
BBB
---
## 段落
文字前后加换行
### 显示效果
    文字前后加换行  

## 无序列表
```
- 加空格 就是一个无序列表的项。
- 无序列表1
+ 无序列表2
* 无序列表3
注：+或*也可以
```
### 显示效果
- 无序列表1
+ 无序列表2
* 无序列表3

## 有序列表
数字加点加空格就是一个有序列表的项
```
1. 有序列表1
2. 有序列表2
3. 有序列表3
```
### 显示效果
1. 有序列表1
2. 有序列表2
3. 有序列表3

## 多选框：
```
- [x] 选项一
- [ ] 选项二
```
### 显示效果
- [x] 选项一
- [ ] 选项二

## 代码块
以三个```包括代码即可,在文字中插入代码
以单个`包含代码块即可
### 显示效果
```
var a=b;
console.log(a)
```

## 链接
[]中写链接名称，()中写具体的url，如：
`[baidu](www.baidu.com)`邮箱链接`<admin@admin.com>`
### 显示效果
[baidu](www.baidu.com),<admin@admin.com>

## 图片
与链接相似，只是多了一个感叹号，`![]()`

## 字体
```
**加粗** : 加粗 *斜体*: 斜体
删除线
~~WWW~~

引用
> 大于号表示引用。 >后的内容就是引用的内容
```
### 显示效果
**加粗**  
*斜体*  
~~WWW~~  
> 引用。

## 表格
```
| Tables | Are | Cool |
| ------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |
```
### 显示效果

| Tables | Are | Cool |
| ------------- |:-------------:| -----:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |


## 分割线
三个连续的 * 或者 - 表示一跳分割线
### 显示效果
***
---
