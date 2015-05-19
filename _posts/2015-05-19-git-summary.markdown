---
layout: post
title:  "Git学习总结"
date:   2015-05-19 15:33:00
description: 
categories:
- blog
- git
---

#####SSH key

#####Git命令：

0. 设置
<pre>$ git config --global user.email "123@gmail.com"</pre>

1. 拉取最新代码
<pre>
$git pull git@github.com:123/123.git master  
$git remote add [name] [path]
</pre>

2. 查询状态
<pre>$ git status</pre>
红字：未追踪， 绿字：已追踪

3. 查询改变
<pre>$ git diff</pre>

4. 加入版本管理中
<pre>$ git add [path]</pre>

5. 提交 P.S.m = message，commit之前文件都在缓冲区里面~如影随形
<pre>$ git commit -m [string]</pre>

6. 查询log
<pre>$ git log</pre>

7. push到master分支
<pre>$ git push origin master</pre>

8. reset到某个提交状态
*不改变文件系统，只改变git的状态和指针:
<pre>$ git reset --soft 4789</pre>
*改变文件系统:
<pre>$ git reset —hard 4789</pre>

9. 分支
*建分支
<pre>
$ git branch [name] // 新建一个branch
$ git checkout [name] // 切换到
$ git checkout -b [name] // 新建并切换到
$ git branch -D [name] // delete
</pre>

*合并分支
<pre>$ git merge tree</pre>


