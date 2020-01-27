
# 题目描述

**译自 POI 2012 Stage 1. 「[Well](https://szkopul.edu.pl/problemset/problem/S-cyTRH8ScRh-XfLPAsXCQ0e/site/?key=statement)」**

给定 $n$ 个正整数 $x_1, x_2, \ldots, x_n$，可以进行不超过 $m$ 次操作，每次操作时选择一个正整数 $x_i$ 并将其减一。

在存在 $k$ 使得 $x_k=0$ 的情况下，最小化
$$ z = \max_{i=1,2,\ldots,n-1}{\lvert x_i - x_{i+1} \rvert} $$

求最小的 $z$ 和对应的 $k$。如果有多组解，可以输出任意一组。

# 输入格式

第一行两个正整数 $n, m (1 \le n \le 1\ 000\ 000, 1 \le m \le 10^{18})$，表示正整数的个数和操作的次数。

第二行 $n$ 个正整数 $x_1, x_2, \ldots, x_n (1 \le x_i \le 10^9)$。

# 输出格式

输出两个正整数，分别表示 $k$ 和 $z$。

# 样例

#### 样例输入
```plain
16 15
8 7 6 5 5 5 5 5 6 6 7 8 9 7 5 5
```

#### 样例输出
```plain
1 2
```

#### 样例解释
![](/source/loj/2692/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vM29DNmpXTjdIWkFVaEVHTGxIZEZfY2kyL3NpdGUvaW1hZ2VzL09JMTkvc3R1MC5naWY=.gif)

# 数据范围与提示

对于 $35\%$ 的数据，$n \le 10\ 000$；

对于所有数据，$1 \le n \le 1\ 000\ 000, 1 \le m \le 10^{18},1 \le x_i \le 10^9$。

