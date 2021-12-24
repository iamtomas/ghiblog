

<p align='center'>
    <img src="https://badgen.net/badge/labels/9"/>
    <img src="https://badgen.net/github/issues/iamtomas/ghiblog"/>
    <img src="https://badgen.net/badge/last-commit/2021-12-24 15:57:27"/>
    <img src="https://badgen.net/github/forks/iamtomas/ghiblog"/>
    <img src="https://badgen.net/github/stars/iamtomas/ghiblog"/>
    <img src="https://badgen.net/github/watchers/iamtomas/ghiblog"/>
    <img src="https://badgen.net/github/release/iamtomas/ghiblog"/>
</p>

<p align='center'>
    <a href="https://github.com/jwenjian/visitor-count-badge">
        <img src="https://visitor-badge.glitch.me/badge?page_id=jwenjian.ghiblog"/>
    </a>
</p>


## 置顶 :thumbsup: 
- [基于Github Action自动生成并更新GitHub Issue博客的ReadMe](https://github.com/iamtomas/note/issues/1)  <sup>0 :speech_balloon:</sup>  	 
## 最新 :new: 

#### [MySQL中InnoDB记录与页结构](https://github.com/iamtomas/note/issues/10) <sup>0 :speech_balloon:</sup> 	 2021-12-24 15:56:55

:label: : 

InnoDB 本身就是个存储引擎，专门负责对数据做存取操作，但在本篇呢，仅讲述在InnoDB下的记录与页的结构

## 记录结构

在InnoDB下支持4种行格式：Compact、Redundant、Dynamic和Compressed，但不管怎么变，在原理上大体都是相同的，下边以Compa

[更多>>>](https://github.com/iamtomas/note/issues/10)

---


#### [两数之和 - 力扣（LeetCode）](https://github.com/iamtomas/note/issues/9) <sup>0 :speech_balloon:</sup> 	 2021-12-21 15:12:45

:label: : [算法](https://github.com/iamtomas/ghiblog/labels/%E7%AE%97%E6%B3%95)

## 题目链接
https://leetcode-cn.com/problems/two-sum/

## 思路

1. 暴力解法

2. 哈希表

## 代码实现

```ruby
# @param {Integer[]} nums
# @param {Integer} 

[更多>>>](https://github.com/iamtomas/note/issues/9)

---


#### [MySQL中SQL是如何执行的？](https://github.com/iamtomas/note/issues/8) <sup>0 :speech_balloon:</sup> 	 2021-12-17 10:05:54

:label: : [MySQL](https://github.com/iamtomas/ghiblog/labels/MySQL), [数据库](https://github.com/iamtomas/ghiblog/labels/%E6%95%B0%E6%8D%AE%E5%BA%93)

# 服务器处理客户端

处理请求的大致过程：

![image](https://user-images.githubusercontent.com/83901620/146526155-87cade0d-c797-4028-9ff1-1dd0a8a69ab8.png)

## 连接管理

MySQL支持下边三种客户端进程和服务器进程的通信方式：

- TCP/IP
- 命名管道和共享内存
- Unix域套接字文件

## 解析与优化

- 查询缓存（在一个对大小写敏感的哈希中进行查找）

> 虽然缓存有时能提高性能，但是维护的成本更高，例如表结构和数据被修改，缓存都会失效并被删除，从 MySQL 5.7.20开始，不再推荐使用，并在MySQL 8.0中删除

- 语法解析与预处理

1. 将 sql 语句打碎成一个个单词
2. 语法检查分析后生成解析树
3. 预处理器再次进行检查后（比如表名等）， 生成一个新的解析树，结构如下：

![image](https://user-images.githubusercontent.com/83901620/146774577-e24f2a71-f8d5-4c64-a235-7e7e35846984.png)

- 查询优化（根据比较成本生成一个执行计划）

那么它是如何从众多的计划中做选择，这就涉及到了查询优化器（Optimizer），在 MySQL 里默认使用的是基于开销的优化器，我们可以通过以下命令查看最近的查询所需要的开销：

```bash
mysql> show status like 'last_query_cost';
+

[更多>>>](https://github.com/iamtomas/note/issues/8)

---


#### [基于Github Action自动生成并更新GitHub Issue博客的ReadMe](https://github.com/iamtomas/note/issues/1) <sup>0 :speech_balloon:</sup> 	 2021-12-16 13:26:34

:label: : [good first issue](https://github.com/iamtomas/ghiblog/labels/good%20first%20issue), [:+1:置顶](https://github.com/iamtomas/ghiblog/labels/%3A%2B1%3A%E7%BD%AE%E9%A1%B6)

https://github.com/jwenjian/ghiblog/issues/1

[更多>>>](https://github.com/iamtomas/note/issues/1)

---


## 分类  :card_file_box: 

<details open="open">
    <summary>
        <img src="assets/wordcloud.png" title="词云, 点击展开详细分类" alt="词云， 点击展开详细分类">
        <p align="center">:cloud: 词云 :cloud: <sub>点击词云展开详细分类:point_down: </sub></p>
    </summary>


<details>
<summary>:+1:置顶	<sup>1:newspaper:</sup></summary>

- [基于Github Action自动生成并更新GitHub Issue博客的ReadMe](https://github.com/iamtomas/note/issues/1)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>:framed_picture:封面	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>bug	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>good first issue	<sup>1:newspaper:</sup></summary>

- [基于Github Action自动生成并更新GitHub Issue博客的ReadMe](https://github.com/iamtomas/note/issues/1)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>MySQL	<sup>1:newspaper:</sup></summary>

- [MySQL中SQL是如何执行的？](https://github.com/iamtomas/note/issues/8)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>开源	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>技术栈	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>数据库	<sup>2:newspaper:</sup></summary>

- [MySQL中InnoDB记录与页结构](https://github.com/iamtomas/note/issues/10)  <sup>0 :speech_balloon:</sup>  	 
- [MySQL中SQL是如何执行的？](https://github.com/iamtomas/note/issues/8)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>算法	<sup>1:newspaper:</sup></summary>

- [两数之和 - 力扣（LeetCode）](https://github.com/iamtomas/note/issues/9)  <sup>0 :speech_balloon:</sup>  	 


</details>


</details>    
