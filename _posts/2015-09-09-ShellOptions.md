---
layout: post
title: Shell脚本中处理参数Options
comments: true
category: 技术
tags: [Shell,Shell脚本]
---


对于Shell脚本的只读参数，Shell只把它当作普通只读数组，放在变量$@中。

```shell
$@
```

