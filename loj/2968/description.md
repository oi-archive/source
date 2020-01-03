
# 题目描述

 **译自 [COCI 2010.03.06](http://hsin.hr/coci/archive/2009_2010/) T6.** ***[CHUCK](http://hsin.hr/coci/archive/2009_2010/contest5_tasks.pdf)***

给你一个 $R$ 行 $C$ 列的矩阵 $A$，$|A_{i,j}|\leq 10^4$。请使用若干次下述操作（次数尽量少），使得矩阵中 $\sum_i \sum_j A_{i,j}$ 尽可能大。

|操作|示例|
|-|-|
|$\texttt{rotR i k}$ <br> 将第 $i$ 行的元素循环右移 $k$ 位|$\begin{pmatrix}1&2&3\\4&5&6\\7&8&9\\10&11&12\end{pmatrix}\xrightarrow{\large\texttt{ rotR 3 1 }}\begin{pmatrix}1&2&3\\4&5&6\\9&7&8\\10&11&12\end{pmatrix}$ |
|$\texttt{rotS j k}$ <br> 将第 $j$ 列的元素循环下移 $k$ 位|$\begin{pmatrix}1&2&3\\4&5&6\\7&8&9\\10&11&12\end{pmatrix}\xrightarrow{\large\texttt{ rotS 3 2 }}\begin{pmatrix}1&2&9\\4&5&12\\7&8&3\\10&11&6\end{pmatrix}$ |
|$\texttt{negR i}$ <br> 将第 $i$ 行的元素全部乘以 $-1$ <br> **该操作当且仅当该行任何一个元素均未乘以 $-1$ 时有效**|$\begin{pmatrix}1&2&3\\4&5&6\\7&8&9\\10&11&12\end{pmatrix}\xrightarrow{\large\texttt{ negR 2 }}\begin{pmatrix}1&2&3\\-4&-5&-6\\7&8&9\\10&11&12\end{pmatrix}$ |
|$\texttt{negS j}$ <br> 将第 $j$ 列的元素全部乘以 $-1$ <br> **该操作当且仅当该列任何一个元素均未乘以 $-1$ 时有效**|$\begin{pmatrix}1&2&3\\0&0&0\\7&8&9\\10&11&12\end{pmatrix}\xrightarrow{\large\texttt{ negS 1 }}\begin{pmatrix}-1&2&3\\0&0&0\\-7&8&9\\-10&11&12\end{pmatrix}$ |

# 输入格式

第一行：$R,C$。  
接下来 $R$ 行：矩阵 $A$。

# 输出格式

第一行包含两个整数，第一个整数为 $\sum_i \sum_j A_{i,j}$ 的最大值，第二个数为操作数量 $T$。  
接下来 $T$ 行，每行包含一组操作。

# 样例

#### 样例输入 1
```plain
3 4
1 -2 5 200
-8 0 -4 -10
11 4 0 100
```

#### 样例输出 1
```plain
345 2
rotS 2 1
negR 2
```

#### 样例输入 2
```plain
3 3
8 -2 7
1 0 -3
-4 -8 3
```

#### 样例输出 2
```plain
34 4
rotR 1 1
rotS 3 1
negR 2
negR 3
```

# 数据范围与提示

$1≤R,C≤100,$ $|A_{i,j}|≤10^4$。

#### 评分标准
若你求了个错误的最大和，或是执行的操作中有无效的，该测试点不得分，否则：
* 若 $T≤ 5\cdot RC$，你将得到该点的所有分数；
* 若 $5\cdot RC<T≤10^5$，你将得到该点 $50\%$ 的分数；
* 若 $T>10^5$，你将得不到该点的任何分数。

