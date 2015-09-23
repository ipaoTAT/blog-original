---
layout: post
title: Shell脚本中处理参数Options
comments: true
category: 技术
tags: [Shell,Shell脚本]
---


对于Shell脚本的只读参数，Shell只把它当作普通只读数组，放在变量$@中。

```shell

$@	#参数列表(数组)
$*	#参数串接字符串(空格隔开)
$#	#参数个数(实际个数)
$0	#脚本文件名
$1-$9	#第一到第九个参数(大于9的无法通过位置直接访问)
$$	#进程ID
$?	#上条命令的返回状态

```

