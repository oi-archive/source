
# 题目描述

> <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 喜欢金字塔。

一个正常的离散金字塔的高度图应该是这样的：
$$
\begin{array}{|c|c|c|c|c|}\hline 1 & {1} & {1} & {1} & {1} \\ \hline 1 & {2} & {2} & {2} & {1} \\ \hline 1 & {2} & {3} & {2} & {1} \\ \hline 1 & {2} & {2} & {2} & {1} \\ \hline 1 & {1} & {1} & {1} & {1} \\ \hline\end{array}
$$
一个正向螺旋的离散金字塔的高度图长这样：
$$
\begin{array}{|c|c|c|c|c|}\hline 1 & {2} & {3} & {4} & {5} \\ \hline {16} & {17} & {18} & {19} & {6} \\ \hline 15 & {24} & {25} & {20} & {7} \\ \hline 14 & {23} & {22} & {21} & {8} \\ \hline 13 & {12} & {11} & {10} & {9} \\ \hline\end{array}
$$
一个逆向螺旋的离散金字塔的高度图长这样：
$$
\begin{array}{|c|c|c|c|c|}\hline 1 & {16} & {15} & {14} & {13} \\ \hline 2 & {17} & {24} & {23} & {12} \\ \hline 3 & {18} & {25} & {22} & {11} \\ \hline 4 & {19} & {20} & {21} & {10} \\ \hline 5 & {6} & {7} & {8} & {9} \\ \hline\end{array}
$$
没错，这是三个 $n\times n$ 的方阵。我们把三个方阵每个位置上的数对应乘起来（即矩阵的点积），形成一个新的矩阵，记为 $\mathbf A$。

现在给定 $n, x_1,y_1,x_2,y_2$，<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 想让你求出
$$
\left (\sum_{i=x_1}^{x_2} \sum_{j=y_1}^{y_2} \mathbf A_{i,j} \right )\bmod \, 10^8
$$
的值。

> <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 懒得想了，于是他丢给你这个问题就去睡觉了。

# 输入格式

一行五个数，表示 $n, x_1,y_1,x_2,y_2$。

# 输出格式

一行一个数表示答案。

# 样例

#### 样例输入
```plain
5 1 1 2 2
```

#### 样例输出
```plain
643
```

# 数据范围与提示

对 $100\%$ 的数据有 $1\leqslant x_1,y_1\leqslant x_2,y_2\leqslant n \leqslant 10^6$。

$20\%$ 的数据保证 $n\leqslant 500$；

另有 $20\%$ 的数据满足 $x_1 = x_2, y_1 = y_2$；

另有 $20\%$ 的数据满足 $x_1 = y_1 = 1, x_2 = y_2 = n$；

对另外 $40\%$ 的数据，无特殊限制。


