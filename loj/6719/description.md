
# 题目描述

题面参考 [**Codeforces Gym 102331 C. Counting Cactus**](https://codeforces.com/gym/102331/problem/C)。

仙人掌是一种无向**联通**图，其中每条边最多在一个简单环内。

![cactus](/source/loj/6719/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wNS8yNS81ZWNiNjgzOWU0ZDIwLnBuZw==.png)

Dreamoon 现在有一个无向图，他想知道这个无向图有多少子图（边的子集）是一个仙人掌？请你找到方案数取模 $998244353$。


# 输入格式

第一行输入两个整数 $n, m$ 表示图的点数和边数。

接下来 $m$ 行，每行两个数 $u, v$，表示一条边的两个端点，保证输入没有重边和自环。


# 输出格式

输出一个整数表示生成仙人掌的数量，对 $998244353$ 取模。


# 样例

#### 样例输入 1

```plain
3 3
1 2
2 3
3 1
```

#### 样例输出 1

```plain
4
```

#### 样例输入 2

```plain
5 0
```

#### 样例输出 2

```plain
0
```

#### 样例输入 3

```plain
8 9
1 5
1 8
2 4
2 8
3 4
3 6
4 7
5 7
6 8
```

#### 样例输出 3

```plain
35
```


# 数据范围与提示

- $1\le n\le \mathbf{18}$
- $0\le m\le \frac{n(n-1)}2$
- $u\neq v, 1\le u, v\le n$, 输入的全体 $(u, v), (v, u)$ 互不相同

子任务：

- （$16$ 分）$n\le 5$
- （$20$ 分）$n\le 7$
- （$14$ 分）$n\le 10$
- （$20$ 分）$n\le 13$
- （$10$ 分）$n\le 16$
- （$20$ 分）没有附加限制


