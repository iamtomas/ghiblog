

<p align='center'>
    <img src="https://badgen.net/badge/labels/11"/>
    <img src="https://badgen.net/github/issues/iamtomas/ghiblog"/>
    <img src="https://badgen.net/badge/last-commit/2022-01-09 12:20:17"/>
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

#### [MySQL零散知识笔记](https://github.com/iamtomas/note/issues/14) <sup>0 :speech_balloon:</sup> 	 2022-01-09 11:23:51

:label: : [MySQL](https://github.com/iamtomas/ghiblog/labels/MySQL), [面试题](https://github.com/iamtomas/ghiblog/labels/%E9%9D%A2%E8%AF%95%E9%A2%98)

## CPU飙升时如何排查与处理（MySQL）

1. top命令排查是否为mysqld占用导致的，否则找出其他占用高的进程进行处理
2. 若是mysqld导致的，则通过 `SHOW PROCESSLIST; ` 查看正在运行的进程中是否有消耗资源的SQL在运行
3. 如果存在高消耗的SQL

[更多>>>](https://github.com/iamtomas/note/issues/14)

---


#### [冒泡排序 - 排序算法](https://github.com/iamtomas/note/issues/13) <sup>0 :speech_balloon:</sup> 	 2022-01-06 16:07:40

:label: : [算法](https://github.com/iamtomas/ghiblog/labels/%E7%AE%97%E6%B3%95)

## 基本思想

两两比较相邻记录的关键字，如果是反序则交换，直到没有反序为止

## 特性

![image](https://user-images.githubusercontent.com/83901620/148403588-e6969b52-3577-49b9-ab95-70

[更多>>>](https://github.com/iamtomas/note/issues/13)

---


#### [一条SQL更新语句是如何执行的？](https://github.com/iamtomas/note/issues/12) <sup>0 :speech_balloon:</sup> 	 2022-01-01 11:05:18

:label: : [MySQL](https://github.com/iamtomas/ghiblog/labels/MySQL), [数据库](https://github.com/iamtomas/ghiblog/labels/%E6%95%B0%E6%8D%AE%E5%BA%93)

更新语句执行的过程其实和查询语句很类似，都是由客户端发送 SQL 语句到 Serve 层，然后通过存储引擎调用 API 去存取数据，如下图

![image](https://user-images.githubusercontent.com/83901620/147848554-b68607b

[更多>>>](https://github.com/iamtomas/note/issues/12)

---


#### [Rails7 demo](https://github.com/iamtomas/note/issues/11) <sup>0 :speech_balloon:</sup> 	 2021-12-26 15:38:56

:label: : [Rails](https://github.com/iamtomas/ghiblog/labels/Rails)

### 新功能和改进

- 
- 

### DEMO

### 参考

- https://www.youtube.com/watch?v=mpWFrUwAN88
- https://rubyonrails.org/2021/12/15/Rails-7-fulfilling-a

[更多>>>](https://github.com/iamtomas/note/issues/11)

---


#### [MySQL中InnoDB记录与页结构](https://github.com/iamtomas/note/issues/10) <sup>0 :speech_balloon:</sup> 	 2021-12-24 15:56:55

:label: : [MySQL](https://github.com/iamtomas/ghiblog/labels/MySQL), [数据库](https://github.com/iamtomas/ghiblog/labels/%E6%95%B0%E6%8D%AE%E5%BA%93)

InnoDB 本身就是个存储引擎，专门负责对数据做存取操作，但在本篇呢，仅讲述在InnoDB下的记录与页的结构

## 记录结构

在InnoDB下支持4种行格式：Compact、Redundant、Dynamic和Compressed，但不管怎么变，在原理上大体都是相同的，下边以Compa

[更多>>>](https://github.com/iamtomas/note/issues/10)

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
<summary>MySQL	<sup>4:newspaper:</sup></summary>

- [MySQL零散知识笔记](https://github.com/iamtomas/note/issues/14)  <sup>0 :speech_balloon:</sup>  	 
- [一条SQL更新语句是如何执行的？](https://github.com/iamtomas/note/issues/12)  <sup>0 :speech_balloon:</sup>  	 
- [MySQL中InnoDB记录与页结构](https://github.com/iamtomas/note/issues/10)  <sup>0 :speech_balloon:</sup>  	 
- [一条SQL查询语句是如何执行的？](https://github.com/iamtomas/note/issues/8)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>Rails	<sup>1:newspaper:</sup></summary>

- [Rails7 demo](https://github.com/iamtomas/note/issues/11)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>开源	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>技术栈	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>数据库	<sup>3:newspaper:</sup></summary>

- [一条SQL更新语句是如何执行的？](https://github.com/iamtomas/note/issues/12)  <sup>0 :speech_balloon:</sup>  	 
- [MySQL中InnoDB记录与页结构](https://github.com/iamtomas/note/issues/10)  <sup>0 :speech_balloon:</sup>  	 
- [一条SQL查询语句是如何执行的？](https://github.com/iamtomas/note/issues/8)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>算法	<sup>2:newspaper:</sup></summary>

- [冒泡排序 - 排序算法](https://github.com/iamtomas/note/issues/13)  <sup>0 :speech_balloon:</sup>  	 
- [两数之和 - 力扣（LeetCode）](https://github.com/iamtomas/note/issues/9)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>面试题	<sup>1:newspaper:</sup></summary>

- [MySQL零散知识笔记](https://github.com/iamtomas/note/issues/14)  <sup>0 :speech_balloon:</sup>  	 


</details>


</details>    
