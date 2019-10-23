
# 题目描述

你有一张 $m \times n$ 的地图，地图上所有点都被洪水淹没了。你知道地图上每个网格的海拔高度，其中一部分点属于 Byteburg 城。你需要放置尽可能少的巨型抽水机，将 Byteburg 城从洪水中解救出来。巨型抽水机会抽干该格子的所有水，直到该格子不被洪水淹没为止。

水会在有公共边的格子间从高向低流动。

# 输入格式

第一行两个整数 $m,n$（$1 \le m,n \le 1000$）。

接下来 $m$ 行每行 $n$ 个整数 $x_{i1}, x_{i2}, \ldots, x_{in} (-1000 \le x_{ij} \lt 1000)$，表示地图。第 $i$ 行第 $j$ 列格子的海拔高度为 $\lvert x_{ij} \rvert$，且如果 $x_{ij} \gt 0$，则这个格子在 Byteburg 城内，否则在城外。不保证 Byteburg 城形成一个连通块。

# 输出格式

输出一行一个整数，表示最少需要的抽水机的数量。

# 样例

#### 样例输入 1
```plain
6 9
-2 -2 -1 -1 -2 -2 -2 -12 -3
-2 1 -1 2 -8 -12 2 -12 -12
-5 3 1 1 -12 4 -6 2 -2
-5 -2 -2 2 -12 -3 4 -3 -1
-5 -6 -2 2 -12 5 6 2 -1
-4 -8 -8 -10 -12 -8 -6 -6 -4
```

#### 样例输出 1
```plain
2
```

#### 样例解释 1
![](/source/loj/2654/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vVnV0emNSMWlQdkd1WVJHWmd2TmtzbVYxL3NpdGUvaW1hZ2VzL09JMTQvcG93emFkMS5naWY=.gif)

# 数据范围与提示



