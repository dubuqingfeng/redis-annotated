## Redis 源码

源代码来自： https://github.com/antirez/redis，目前是 4.0.9 版本，并尽量保持同步。

### 源码文件的作用简介

| 文件名  | 作用 |
| ------------- | ------------- |
| sds.c、sds.h、sdsalloc.h | 动态字符串的实现 |
| sentinel.c | [sentinel 哨兵](https://redis.io/topics/sentinel) 源码实现 |