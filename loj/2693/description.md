
# 题目描述

**译自 POI 2012 Stage 2. Day 0「[Tour de Byteotia](https://szkopul.edu.pl/problemset/problem/mormqC6WwjeIiBpSNMhVbHni/site/?key=statement)」**

给定一个 $n$ 个点 $m$ 条边的无向图，问最少删掉多少条边能使得编号小于等于 $k$ 的点都不在任何一条简单环上。

# 输入格式

第一行包含三个整数 $ n $、$ m $、$ k $，分别表示 $ n $ 个节点， $ m $ 条边，$ k $ 意义见题面。

接下来 $ m $ 行，每行两个整数 $ u $，$ v $，表示一条由 $ u $ 到 $ v $ 的双向边，每一对点之间至多只有一条边。

# 输出格式

第一行一个整数 $ k $，表示最少的删边数量；

接下来 $ k $ 行，每行输出两个正整数 $a,b$，表示删除 $a,b$ 之间的一条边，先输出编号小的点，再输出编号大的点。

# 样例

#### 样例输入
```plain
11 13 5
1 2
1 3
1 5
3 5
2 8
4 11
7 11
6 10
6 9
2 3
8 9
5 9
9 10
```

#### 样例输出
```plain
3
2 3
5 9
3 5
```

#### 样例解释
![](/source/loj/2693/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vbW9ybXFDNld3amVJaUJwU05NaFZiSG5pL3NpdGUvaW1hZ2VzL09JMTkvdG91emFkMS5naWY=.gif)

# 数据范围与提示

对于 $40\%$ 的数据有 $n \le 1000,m \le 5000$.

对于所有数据有 $1 \le n \le 1\ 000\ 000,0 \le m \le 2\ 000\ 000,1 \le k \le n, 1 \le u \lt v \le n$.

