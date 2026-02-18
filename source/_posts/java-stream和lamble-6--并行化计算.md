---
title: java-stream和lamble(6)-并行化计算
date: 2024-12-31 22:23:00
categories: [java]
tags: [java的stream]
---

java 的函数式变成将一个stream操作变成并行化的过程非常简单，只要使用parallelStream() 方法替代stream()方法就好了

```java
public int parallelArraySum() {
return albums.parallelStream()
.flatMap(Album::getTracks)
.mapToInt(Track::getLength)
.sum();
}
```