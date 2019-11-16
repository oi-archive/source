
# 题目描述

** 译自 BalticOI 2011 Day2 T3「Polygon」**

在平面直角网格图中有一个简单多边形，它有 $N$ 个顶点，每个顶点都在格点上（格点=整点）。  
试求：严格在多边形内部的网格线有多长。在「样例解释」中， 严格在多边形内部的网格线将会加粗显示。  
请注意精度。设你的答案为 $L$，标准答案为 $R$，则只需满足 $|L − R| ≤ R \times 10^{−6}$ 和 $|L − R| ≤ 10^{−6}$ 两个条件中的其中一个即可得分。

A simple polygon with N vertices is drawn on an infinite rectangular grid. For such a polygon, only neighboring edges touch at their common vertex; no other of its edges intersect or touch. All vertices of the polygon lie on grid points, i.e., vertices have integer coordinates.  
Your task is to find the total length of grid line segments which lie strictly inside the given polygon (these line segments are highlighted in the drawings below).

# 输入格式

第一行有一个整数 $N$。  
在接下来的 $N$ 行中，每行两个整数 $x$ 和 $y$，表示一个顶点的坐标。

The first line of input contains a single integer N, the number of vertices of the polygon. Each of the following N lines contains two integers x and y, the coordinates of one vertex. The vertices are given either in clockwise or counterclockwise order. All vertices are distinct, but more than two consecutive vertices may lie on a line.

# 输出格式

输出仅一行，一个数，表示严格在多边形内部的网格线的长度。

The only line of output must contain a decimal number: the total length of grid line segments which lie strictly inside the given polygon.

# 样例

#### 样例输入 1
```plain
3
5 1
2 4
1 1
```

#### 样例输出 1
```plain
10.0
```

#### 样例解释 1
<img src="/source/loj/2636/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNjM2L3Rlc3RkYXRhL2Rvd25sb2FkLzEuUE5H.PNG" width="50%">

符合要求的竖线之长为 $\frac{4}{3} + \frac{8}{3} =4$，横线之长为 $3+2+1=6$。总长 $4+6=10$。

The length of horizontal lines is 4/3 + 8/3 = 4. The length of vertical lines is 3 + 2 + 1 = 6.
The total length is 4 + 6 = 10.

#### 样例输入 2
```plain
5
0 0
-2 2
-2 -1
2 -2
2 0
```

#### 样例输出 2
```plain
12.5
```

#### 样例解释 2
<img src="/source/loj/2636/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNjM2L3Rlc3RkYXRhL2Rvd25sb2FkLzIuUE5H.PNG" width="50%">

符合要求的竖线之长为 $1+2+4=7$，横线之长为 $\frac{9}{4}+\frac{3}{2}+\frac{7}{4}=5.5$。总长 $7+5.5=12.5$。

The length of horizontal lines is 1+2+4 = 7. The length of vertical lines is 9/4+3/2+7/4 = 5.5. The total length is 7 + 5.5 = 12.5.

# 数据范围与提示

对于 $50\%$ 的数据，多边形所有的边均在网格线上。  
对于所有数据，$3 ≤ N ≤ 10^5, -5\times 10^8 ≤ x,y ≤ 5\times 10^8$。

