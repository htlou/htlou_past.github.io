---
layout: article
title: 集群教程：我的被坑经验
mathjax: true
tags:tutorial
---

# 集群教程：我的被坑经验

**本文仅代表一种可行的解法，即使（某些我没有注意到的地方）有些繁琐**
**注：代码里的汉字是要根据情况被替换的内容**

0.0 一些有用的东西

&emsp;也即我在自己摸索的时候用到的一些东西：
&emsp;[朱毅鑫老师的使用手册](https://pku-core.feishu.cn/docx/KZerdFIcQoESlexvY5XcpdtgnBd)(密码班级群发过)
&emsp;[etc]()

1.0 登录集群

~~~
ssh -p 19922 你的姓名小写全拼@117.139.124.77
~~~

1.1 安装anaconda

从[anaconda官网](https://www.anaconda.com/download#downloads)获取下载链接，wget下载到你的目录（随着时间推移这个包可能会有新版本）：

~~~
wget https://repo.anaconda.com/archive/Anaconda3-2023.03-1-Linux-x86_64.sh
~~~

<blockquote>
服务器网速挺慢的...没啥办法（（（
</blockquote>
下载完成后用bash命令安装：

~~~
bash Anaconda3-2023.03-1-Linux-x86_64.sh
~~~
