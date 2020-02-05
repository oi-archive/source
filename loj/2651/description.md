
# 题目描述

**译自 POI 2007 Stage 1.「[Axes of Symmetry](https://szkopul.edu.pl/problemset/problem/ETArorvqQVqRUJRa4kx02f8D/site/?key=statement)」**

给定一个多边形，不一定是凸多边形，但没有自交，即除了相邻的边在顶点上相交外没有两条边有公共点。

求多边形的对称轴个数。

# 输入格式

第一行一个整数 $t (1 \le t \le 10)$，表示测试点个数。

接下来有 $t$ 组数据，每组数据第一行有一个整数 $n (3 \le n \le 100\ 000)$，表示多边形的点数。

接下来 $n$ 行每行有两个整数 $x$ 和 $y$ （$-100\ 000\ 000 \le x \le 100\ 000\ 000$，$-100\ 000\ 000 \le y \le 100\ 000\ 000$），表示多边形的点。保证相邻边不共线。

# 输出格式

输出 $t$ 行，对每个多边形输出一个整数表示对称轴的个数。

# 样例

#### 样例输入
```plain
2
12
1 -1
2 -1
2 1
1 1
1 2
-1 2
-1 1
-2 1
-2 -1
-1 -1
-1 -2
1 -2
6
-1 1
-2 0
-1 -1
1 -1
2 0
1 1
```

#### 样例输出
```plain
4
2
```

#### 样例解释
![](/source/loj/2651/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vRVRBcm9ydnFRVnFSVUpSYTRreDAyZjhEL3NpdGUvaW1hZ2VzL09JMTQvb3NpaW1nLnBuZw==.png)

# 数据范围与提示



