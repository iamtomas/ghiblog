

<p align='center'>
    <img src="https://badgen.net/badge/labels/20"/>
    <img src="https://badgen.net/github/issues/iamtomas/ghiblog"/>
    <img src="https://badgen.net/badge/last-commit/2022-04-06 05:34:57"/>
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

#### [Rails Dotenv 不刷新](https://github.com/iamtomas/note/issues/38) <sup>0 :speech_balloon:</sup> 	 2022-04-06 05:34:32

:label: : [Rails](https://github.com/iamtomas/ghiblog/labels/Rails)



[更多>>>](https://github.com/iamtomas/note/issues/38)

---


#### [Rack](https://github.com/iamtomas/note/issues/37) <sup>0 :speech_balloon:</sup> 	 2022-04-05 15:33:04

:label: : [Rack](https://github.com/iamtomas/ghiblog/labels/Rack)

将了解到
- 什么是 Rack
- Rack 实现原理
- 如何使用 Rack
- Rack 的作用及场景

什么是 Rake ：一般 Ruby Web Application 包含 Framework（如 Rails、Sinatra 等）、Rack 层及 WebServer 层（如 p

[更多>>>](https://github.com/iamtomas/note/issues/37)

---


#### [K8s + Helm](https://github.com/iamtomas/note/issues/36) <sup>0 :speech_balloon:</sup> 	 2022-03-31 09:02:12

:label: : [K8s](https://github.com/iamtomas/ghiblog/labels/K8s)

定义：The package manager for Kubernetes

解决：K8s 抽象了各种各样的资源，如Pod、deployemnt、Service等，Helm 作为包管理器可以对这些多资源进⾏管理

待更新

[更多>>>](https://github.com/iamtomas/note/issues/36)

---


#### [M1开发环境](https://github.com/iamtomas/note/issues/35) <sup>0 :speech_balloon:</sup> 	 2022-03-31 09:00:24

:label: : [部署](https://github.com/iamtomas/ghiblog/labels/%E9%83%A8%E7%BD%B2)

# brew

从官网下载（如果因网络问题拉不下来，可以下载国内的脚本）后，把镜像修改成国内

# asdf

负责多环境管理（包括 node 、ruby、go等）

```zsh
brew install asdf
```

# git

不要使用系统自带的 git

```zsh
brew install git
```

另外 M1 下通过 `brew install bash-completion` 方式无法实现 git 补全，而是采用下边方式

```zsh
curl https://raw.githubusercontent.com/git/git/master/contrib/completion/git-completion.bash -o ~/.git-completion.bash

mkdir ~/.zsh

cp git-completion.bash ~/.zsh/.git-completion.bash

# ~/.zshrc
zstyle ':completion:*:*:git:*' script ~/.zsh/.git-completion.bash
fpath=(~/.zsh $fpath)
autoload -Uz compinit && compinit
```

terminal 显示 git 分支则可以采用以下方式

```zsh
# ~/.zshrc
function parse_git_branch() {
    git branch 2> /dev/null | sed -n -e 's/^\* \(.*\)/[\1]/p'
}

setopt PROMPT_SUBST
export PROMPT='%F{grey}%n%f %F{cyan}%~%f %F{green}$(parse_git_branch)%f %F{normal}$%f '
```

# mysql

```zsh
brew install mysql
```

# navicat premium 16.0.9

无需注册码

# docker

```zsh
brew install docker
```

# k8s

网上查询下，下载规定版本的 docker desktop，可以通过镜像启动 k8s

# helm

```zsh
brew install helm
```

# redis

```zsh
brew install redis
```

# java

官网下载

# kafka

在 m1 芯片下通过 brew 安装始终启动不了，也确保了 java 和 zookeeper 环境存在，最后通过 docker 将 kafka 和 zookeeper 容器跑起来

```yml


[更多>>>](https://github.com/iamtomas/note/issues/35)

---


#### [Sidekiq](https://github.com/iamtomas/note/issues/33) <sup>0 :speech_balloon:</sup> 	 2022-03-30 07:49:54

:label: : [Sidekiq](https://github.com/iamtomas/ghiblog/labels/Sidekiq)

定义：用于处理后台任务且依赖于 Redis 的工具

快速使用：



[更多>>>](https://github.com/iamtomas/note/issues/33)

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
<summary>CI/CD	<sup>1:newspaper:</sup></summary>

- [GitLab CI/CD 实践](https://github.com/iamtomas/note/issues/16)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>Docker	<sup>4:newspaper:</sup></summary>

- [Docker入门二](https://github.com/iamtomas/note/issues/26)  <sup>0 :speech_balloon:</sup>  	 
- [Docker入门一](https://github.com/iamtomas/note/issues/25)  <sup>0 :speech_balloon:</sup>  	 
- [Docker-compose up failing because "port is already allocated"](https://github.com/iamtomas/note/issues/24)  <sup>0 :speech_balloon:</sup>  	 
- [Docker Demo（进阶）](https://github.com/iamtomas/note/issues/22)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>good first issue	<sup>1:newspaper:</sup></summary>

- [基于Github Action自动生成并更新GitHub Issue博客的ReadMe](https://github.com/iamtomas/note/issues/1)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>K8s	<sup>2:newspaper:</sup></summary>

- [K8s + Helm](https://github.com/iamtomas/note/issues/36)  <sup>0 :speech_balloon:</sup>  	 
- [Kubernetes入门一](https://github.com/iamtomas/note/issues/27)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>MQ	<sup>2:newspaper:</sup></summary>

- [Kafka](https://github.com/iamtomas/note/issues/32)  <sup>0 :speech_balloon:</sup>  	 
- [消息队列零散知识笔记](https://github.com/iamtomas/note/issues/17)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>MySQL	<sup>5:newspaper:</sup></summary>

- [数据库设计大全](https://github.com/iamtomas/note/issues/28)  <sup>0 :speech_balloon:</sup>  	 
- [MySQL零散知识笔记](https://github.com/iamtomas/note/issues/14)  <sup>0 :speech_balloon:</sup>  	 
- [一条SQL更新语句是如何执行的？](https://github.com/iamtomas/note/issues/12)  <sup>0 :speech_balloon:</sup>  	 
- [MySQL中InnoDB记录与页结构](https://github.com/iamtomas/note/issues/10)  <sup>0 :speech_balloon:</sup>  	 
- [一条SQL查询语句是如何执行的？](https://github.com/iamtomas/note/issues/8)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>PostgreSQL	<sup>2:newspaper:</sup></summary>

- [如何本地不安装 postgreSQL 情况下执行 gem install pg](https://github.com/iamtomas/note/issues/21)  <sup>0 :speech_balloon:</sup>  	 
- [一条SQL查询语句是如何执行的？](https://github.com/iamtomas/note/issues/18)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>Rack	<sup>1:newspaper:</sup></summary>

- [Rack](https://github.com/iamtomas/note/issues/37)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>Rails	<sup>4:newspaper:</sup></summary>

- [Rails Dotenv 不刷新](https://github.com/iamtomas/note/issues/38)  <sup>0 :speech_balloon:</sup>  	 
- [状态机（AASM）实现持久化](https://github.com/iamtomas/note/issues/31)  <sup>0 :speech_balloon:</sup>  	 
- [Sidekiq 浅析](https://github.com/iamtomas/note/issues/19)  <sup>0 :speech_balloon:</sup>  	 
- [Rails7 demo](https://github.com/iamtomas/note/issues/11)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>Redis	<sup>1:newspaper:</sup></summary>

- [Redis零散知识笔记](https://github.com/iamtomas/note/issues/15)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>Sidekiq	<sup>1:newspaper:</sup></summary>

- [Sidekiq](https://github.com/iamtomas/note/issues/33)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>开源	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>技术栈	<sup>0:newspaper:</sup></summary>



</details>

<details>
<summary>数据库	<sup>5:newspaper:</sup></summary>

- [数据库设计大全](https://github.com/iamtomas/note/issues/28)  <sup>0 :speech_balloon:</sup>  	 
- [一条SQL查询语句是如何执行的？](https://github.com/iamtomas/note/issues/18)  <sup>0 :speech_balloon:</sup>  	 
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
<summary>踩坑	<sup>3:newspaper:</sup></summary>

- [grpc_c.bundle fails to load on Apple M1 (wrong architecture) ](https://github.com/iamtomas/note/issues/30)  <sup>0 :speech_balloon:</sup>  	 
- [ld: library not found for -lzstd while bundle install for mysql2 gem Ruby on macOS Big Sur](https://github.com/iamtomas/note/issues/29)  <sup>0 :speech_balloon:</sup>  	 
- [解决OSX使用oh-my-zsh后.bash_profile自定义失效](https://github.com/iamtomas/note/issues/23)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>部署	<sup>1:newspaper:</sup></summary>

- [M1开发环境](https://github.com/iamtomas/note/issues/35)  <sup>0 :speech_balloon:</sup>  	 


</details>

<details>
<summary>面试题	<sup>3:newspaper:</sup></summary>

- [消息队列零散知识笔记](https://github.com/iamtomas/note/issues/17)  <sup>0 :speech_balloon:</sup>  	 
- [Redis零散知识笔记](https://github.com/iamtomas/note/issues/15)  <sup>0 :speech_balloon:</sup>  	 
- [MySQL零散知识笔记](https://github.com/iamtomas/note/issues/14)  <sup>0 :speech_balloon:</sup>  	 


</details>


</details>    
