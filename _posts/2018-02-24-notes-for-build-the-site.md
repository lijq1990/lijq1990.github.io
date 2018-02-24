---
layout: post
title:  "Notes for build this site"
date:   2015-11-17 16:16:01 -0600
categories: site build note
---

__初始化本地文件夹__
```$ git init```
``` Initialized empty Git repository in /Users/michael/learngit/.git/```

__本地文件夹（仓库）关联远程github仓库__
在本地文件夹下运行命令：
```$ git remote add origin git@github.com:lijq1990/****.git```
其中```$ git remote``` 是命令，```git@github.com:lijq1990/****.git```的部分是从github上复制的。
***
__关联后推送内容__
关联后，使用命令```git push -u origin master```第一次推送 master 分支的所有内容；

此后，每次本地提交后，只要有必要，就可以使用命令```git push origin master```推送最新修改。
***
__从远程github克隆仓库到本地__
在本地文件夹下运行命令：
```$ git clone git@github.com:lijq1990/****.git```，其中```$ git clone```是命令。
***

