
# 题目描述

 **译自 [COCI 2010.02](http://hsin.hr/coci/archive/2009_2010/) T5.** ***[KABOOM](http://hsin.hr/coci/archive/2009_2010/contest4_tasks.pdf)***

Luka 在实验室里发现了一条奇怪的胶带。胶带分为 $N$ 段，从左到右依次编号为 $1\ldots N$。胶带厚度忽略不计。

胶带只能在两段的交点处弯折，且只能折叠 180°。

显然胶带有两面。胶带的一面涂满了粘性超大的胶，另一面则只有前 $A$ 段和后 $B$ 段涂了粘性超大的胶。

请问 Luka 有多少种折叠方式使他能还原现场（Luka 的手不会粘住胶带，但如果两个胶面粘一起了 Luka 就撕不开了）。答案对 $10301$ 取模。


# 输入格式

第一行，三个整数 $N,A,B$。  


# 输出格式

一行一个整数，表示答案。

# 样例

#### 样例输入 1
```plain
4 1 1
```
#### 样例输出 1
```plain
6
```
#### 样例说明 1

![p1.png](source/loj/2964/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMzAvNWMyOGM3NjFlZTNhMy5wbmc=.png)
![p2.png](source/loj/2964/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMzAvNWMyOGM3NjFlNDhjMC5wbmc=.png)

#### 样例输入 2
```plain
5 2 2
```
#### 样例输出 2
```plain
1
```
#### 样例输入 3
```plain
6 1 2
```
#### 样例输出 3
```plain
7
```

# 数据范围与提示

$1\le A+B\le N\le 1000,$ $A>0,$ $B>0$.

