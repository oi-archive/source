
# 题目描述

**译自 POI 2007 Stage 1.「[Queries](https://szkopul.edu.pl/problemset/problem/MVjuhH4JZu17rusHweyEdyJx/site/?key=statement)」**

给定正整数 $a,b,d$，找出满足以下条件的正整数对 $(x,y)$ 的个数：
* $1 \le x \le a$
* $1 \le y \le b$
* $\gcd(x,y)=d$

# 输入格式

第一行一个整数 $n (1 \le n \le 50\ 000)$，表示询问的个数。

接下来 $n$ 行每行三个整数 $a,b,d$,$(1 \le d \le a,b \le 50\ 000)$，表示询问。

# 输出格式

输出 $n$ 行，表示 $n$ 组询问的答案。

# 样例

#### 样例输入
```plain
2
4 5 2
6 4 3
```

#### 样例输出
```plain
3
2
```

#### 样例解释
第一组询问的三个正整数对分别为 $(2,2), (2,4), (4,2)$。
第二组询问的两个正整数对分别为 $(3,3), (6,3)$.

# 数据范围与提示



