---
title: linux 终端使用代理
date: 2024-12-31 19:28:00
categories: [运维系统]
tags: []
---

核心思想 , 改变终端的环境变量
终端输入命令

```
export http_proxy=http://proxyAddress:port
export https_proxy=http://proxyAddress:port
export ALL_PROXY=socks5://127.0.0.1:1080
```
