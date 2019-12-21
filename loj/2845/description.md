
# 题目描述

**译自 [ROI 2018](http://neerc.ifmo.ru/school/archive/2017-2018.html) Day1 T3.** ***[Иннофон](http://neerc.ifmo.ru/school/archive/2017-2018/ru-olymp-roi-2018-day1.pdf) ([Innophone](http://codeforces.com/gym/102147/problem/B))***

有一个二元函数 $f(x,y)$，它是这么定义的：

$$ f(x,y)=\left\{
\begin{array}{rcl}
a,       &      & {\text{if} \quad \quad \ \ \ a \leq x}\\
b,     &      & {\text{else if} \quad b \leq y}\\
0,     &      & {\text{else}}
\end{array} \right. $$

其中 $a,b$ 为常数。现在给定 $n$ 组 $x,y$，你需要选择合适的 $a,b$，使得 $\sum_{i=1}^{n} f(x_i,y_i)$ 最大。

# 输入格式

第一行一个整数 $n$，表示 $x,y$ 的组数。

后面 $n$ 行，每行两个数 $x_i,y_i$。

# 输出格式

一行，一个数，输出 $\max(\sum_{i=1}^{n} f(x_i,y_i))$。

# 样例

#### 样例输入 1
```plain
5
80 20
60 50
40 40
15 10
70 30
```
#### 样例输出 1
```plain
220
```

#### 样例输入 2
```plain
1
50 0
```
#### 样例输出 2
```plain
50
```

# 数据范围与提示

对于 $100\%$ 的数据，$1\le x_i,y_i\le 10^9$。

|任务编号|$1 \leq n \leq$|$x,y$|分值|
|:-:|:-:|:-:|:-:|
|$1$|$100$|$y_i \leq x_i \leq 100$|$9$|
|$2$|$300$||$10$|
|$3$|$3000$||$16$|
|$4$|$10^5$|$y_i=0$|$11$|
|$5$|$10^5$|$x_i=y_i$|$16$|
|$6$|$50000$||$7$|
|$7$|$75000$||$7 $|
|$8$|$10^5$||$8$|
|$9$|$1.25\times 10^5$||$8 $|
|$10$|$1.5\times 10^5$||$8$|

