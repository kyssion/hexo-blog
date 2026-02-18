---
title: git_在linux 环境下中文乱码问题解决
date: 2024-12-31 23:54:00
categories: [git]
tags: []
---

看了网上好多教程

其实一行命令就可以解决

```
git config --global core.quotepath false
git config --global i18n.logoutputencoding utf-8
git config --global i18n.commitencoding utf-8
git config --global gui.encoding utf-8
```


