
# 题目描述

**译自 POI 2010 Stage 3. Day 2「[Bridges](https://szkopul.edu.pl/problemset/problem/gh2Yj6Ckrt4Lo_RojONuljuC/site/?key=statement)」**

给定一个 $n$ 个点的无向图，每条边的两个方向各有一个权值，求一条从 1 号点出发，恰经过所有边一次并回到 1 号点的路线，使得权值的最大值最小。

# 输入格式

第一行两个整数 $n,m$ ，分别表示点的数量和边的数量。点从 $1$ 到 $n$ 编号，边从 $1$ 到 $m$ 编号。

接下来 $m$ 行每行有四个整数 $a_i,b_i,l_i,p_i $ ，表示第 $i$ 条边连接 $a,b$ ，且从 $a$ 到 $b$ 的权值为 $l_i$ ，从 $b$ 到 $a$ 的权值为 $p_i$。

# 输出格式

如果原图不存在这样的路线，输出 ```NIE``` 。否则，应该输出两行，第一行表示路线中权值最大值的最小值，第二行有 $m$ 个整数，依次表示你选择的路线的边。如果有多条这样的路线，可以输出任意一条。

# 样例

### 样例输入
```plain
4 4
1 2 2 4
2 3 3 4
3 4 4 4
4 1 5 4
```

### 样例输出
```plain
4
4 3 2 1
```

### 样例解释
![mos.gif](/source/loj/2460/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMDMvMjkvNWFiY2RmMzU3N2ZmNy5naWY=.gif)

最优路线为 $1 \xrightarrow{4} 4 \xrightarrow{4} 3 \xrightarrow{4} 2 \xrightarrow{4}1$，最大权值为 $4$。

# 数据范围与提示

对于 $100\%$ 的数据，  $2 \le n \le 1000,1 \le m \le 20000 , 1 \le a_i,b_i \le n,a_i \neq b_i,1 \le l_i,p_i \le 1000$ 。

Translated & SPJ by vincent163

