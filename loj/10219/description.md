
# 题目描述

矩阵 $A$ 规模为 $n\times m$，矩阵 $B$ 规模为 $m\times p$，现需要你求 $A\times B$。

矩阵相乘的定义：$n\times m$ 的矩阵与 $m\times p$ 的矩阵相乘变成 $n\times p$ 的矩阵，令 $a_{ik}$ 为矩阵 $A$ 中的元素，$b_{kj}$ 为矩阵 $B$ 中的元素，则相乘所得矩阵 $C$ 中的元素

$$c_{ij}=\sum_{k=1}^m a_{ik}b_{kj}$$

具体可见样例。

# 输入格式

第一行两个数 $n,m$；

接下来 $n$ 行 $m$ 列描述一个矩阵 $A$；

接下来一行输入 $p$；

接下来 $m$ 行 $p$ 列描述一个矩阵 $B$。


# 输出格式

输出矩阵 $A$ 与矩阵 $B$ 相乘所得的矩阵 $C$。

# 样例

#### 样例输入
```plain
2 3
1 2 3
3 2 1
2 
1 1
2 2
3 3
```
#### 样例输出
```plain
14 14
10 10
```
#### 样例解释
$$
\begin{bmatrix}
14=1\times 1+2\times 2+3\times 3&14=1\times 1+2\times 2+3\times 3\\
10=3\times 1+2\times 2+1\times 3&10=3\times 1+2\times 2+1\times 3
\end{bmatrix}
$$

# 数据范围与提示

对于全部数据，$1\le n,m,p \le 100,-10000\le a_{ij},b_{ij}\le 10000$。

