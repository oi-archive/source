
# 题目描述

**译自 POI 2007 Stage 3. Day 1「[Gas Pipelines](https://szkopul.edu.pl/problemset/problem/zWn2E-v-nn-bozeXQrykmCgD/site/?key=statement)」**

平面上有 $n$ 个天然气井和中转站，从天然气井开始向 $x$ 轴正方向、$y$ 轴负方向建立管道连接到中转站，使得管道的总长度最小。

# 输入格式

第一行一个整数 $n (1 \le n \le 50\ 000)$，表示天然气井的数量，中转站的数量与天然气井的数量一样。

接下来 $n$ 行每行两个整数 $x_i, y_i (0 \le x_i, y_i \le 100\ 000)$，表示天然气井的坐标。

接下来 $n$ 行每行两个整数 $x_i', y_i' (0 \le x_i, y_i \le 100\ 000)$，表示中转站的坐标。

保证存在一个合法的方案。

# 输出格式

第一行输出一个整数，表示最小的管道总长度。

接下来 $n$ 行表示一组可能的方案，每行两个整数，分别表示用管道连接的天然气井和中转站的编号。

如果有多组解，可以输出任意一组。

# 样例

#### 样例输入
```plain
3
3 5
1 2
4 3
6 3
5 2
2 1
```

#### 样例输出
```plain
9
2 3
1 2
3 1
```

#### 样例解释
![](/source/loj/2659/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0velduMkUtdi1ubi1ib3plWFFyeWttQ2dEL3NpdGUvaW1hZ2VzL09JMTQvZ2F6LmdpZg==.gif)

# 数据范围与提示



