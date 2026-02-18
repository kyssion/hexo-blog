---
title: mybatis-源码阅读记录(1)-building包
date: 2024-12-31 21:56:00
categories: [java]
tags: [mybatis]
---

building 包是用来构造Mapper的包含如下的类

#  building包

负责接口 mapper 模式的代理类,其中mapperProxy实用了java7 的放射新特性这个需要注意一下

# building 包

