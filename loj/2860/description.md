
# 题目描述

**译自 [BalticOI 2009](http://www.csc.kth.se/contest/boi/tasks.php) Day2 T1「[Rectangle](http://www.csc.kth.se/contest/boi/rectangle.pdf)」**

你被给定 $n$ 个在平面坐标上的点。

写一个程序计算出一个最大的矩形区域，使它的每一个顶点都是给定的点之一。你可以假设至少存在一个这样的区域。

# 输入格式

第一行，一个整数 $n$，表示点的数量。

以下 $n$ 行，每行两个整数，表示一个点的坐标。  
坐标值在 $-10^8$ 与 $10^8$ 之间。

没有两个点位于同一个坐标。

# 输出格式

一个整数，表示最大的矩形区域面积。

# 样例

#### 样例输入
```plain
8
-2 3
-2 -1
0 3
0 -1
1 -1
2 1
-3 1
-2 1
```

### 样例输出
```plain
10
```

#### 样例解释
![](/source/loj/2860/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMDgvMjUvNWI4MTMzZjFkNzYyMC5wbmc=.png)

# 数据范围与提示

|数据百分比|限制|
|:--------------:|:-----:|
|$20\%$|$n \le 500$|
|$100\%$|$4 \le n \le 1,500$|

