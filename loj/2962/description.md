
# 题目描述

 **译自 [COCI 2009.12](http://hsin.hr/coci/archive/2009_2010/) T6.** ***[PLANETE](http://hsin.hr/coci/archive/2009_2010/contest3_tasks.pdf)***

已知 $N$ 组记录，第 $i$ 组记录包含两个**无年份**的日期 $A_i,$ $B_i$（换言之，只有月和日）以及一个长度为 $M$ 的数组 $a_{i,1},$ $a_{i,2},$ $\ldots,$ $a_{i,M}$。

请给出关于 $x_1,$ $x_2,$ $\ldots,$ $x_N$ 的方程组

$$\begin{cases}
A_1+\sum_{j=1}^{M} a \small_{1,j} x\small_j \equiv B_1 \pmod{365} \\
A_2+\sum_{j=1}^{M} a \small_{2,j} x\small_j \equiv B_2 \pmod{365} \\
\qquad\qquad\qquad\vdots \\
A_N+\sum_{j=1}^{M} a \small_{N,j} x\small_j \equiv B_N \pmod{365} \\
\forall x_j,\ \ 1\leqslant x_j\leqslant 365
\end{cases}$$

的任意一组解，无解则输出 $\texttt{-1}$。

# 输入格式

第一行两个整数 $N,M$。  
接下来 $N$ 行，每行开头有四个整数，分别表示 $A_i$ 的日，$A_i$ 的月，$B_i$ 的日，$B_i$ 的月。接下来有 $M$ 个整数，表示 $a_{i,1},$ $a_{i,2},$ $\ldots,$ $a_{i,M}$。  
保证输入的月、日合法。

# 输出格式

若有解，输出共 $M$ 行，每行一个整数，表示 $x_i$。  
若无解则输出 $\texttt{-1}$。

# 样例

#### 样例输入 1
```plain
1 1
26 02 03 03 1
```

#### 样例输出 1
```plain
5
```

#### 样例输入 2
```plain
1 1
26 02 03 03 2
```

#### 样例输出 2
```plain
185
```

#### 样例输入 3
```plain
3 3
22 03 01 10 9 10 10
05 05 16 12 1 7 10
20 06 15 01 4 9 10
```

#### 样例输出 3
```plain
102
204
125
```

# 数据范围与提示

$1\le N,M\le 200,$ $0\le a_{i,j}\le 200,$ 保证输入的月、日合法。

