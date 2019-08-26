
# 题目描述

给定一个 $n \times n$ 的网格状地图，每个方格 $(i,j)$有一个高度 $w_{ij}$。如果两个方格有公共顶点，则它们是相邻的。

定义山峰和山谷如下：
* 均由地图上的一个连通块组成；
* 所有方格高度都相同；
* 周围的方格（即不属于山峰或山谷但与山峰或山谷相邻的格子）高度均大于山谷的高度，或小于山峰的高度。

求地图内山峰和山谷的数量。特别地，如果整个地图方格的高度均相同，则整个地图既是一个山谷，也是一个山峰。

# 输入格式

第一行一个整数 $n$ （$2 \le n \le 1000$），表示地图的大小。

接下来 $n$ 行每行 $n$ 个整数表示地图。第 $i$ 行有 $n$ 个整数 $w_{i1}, w_{i2}, \ldots, w_{in} (0 \le w_{ij} \le 1\ 000\ 000\ 000)$，表示地图第 $i$ 行格子的高度。

# 输出格式

输出一行两个整数，分别表示山峰和山谷的数量。

# 样例

#### 样例输入 1
```plain
5
8 8 8 7 7
7 7 8 8 7
7 7 7 7 7
7 8 8 7 8
7 8 8 8 8
```

#### 样例输出 1
```plain
2 1
```

#### 样例解释 1
![](source/loj/2653/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vcmQ2SDA1RG04TUU3OXNPM1U5X2ZfZ2FfL3NpdGUvaW1hZ2VzL09JMTQvZ3J6emFkMS5naWY=.gif)

#### 样例输入 2
```plain
5
5 7 8 3 1
5 5 7 6 6
6 6 6 2 8
5 7 2 5 8
7 1 0 1 7
```

#### 样例输出 2
```plain
3 3
```

#### 样例解释 2
![](source/loj/2653/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vcmQ2SDA1RG04TUU3OXNPM1U5X2ZfZ2FfL3NpdGUvaW1hZ2VzL09JMTQvZ3J6emFkMi5naWY=.gif)

# 数据范围与提示



