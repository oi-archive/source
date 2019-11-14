
# 题目描述

**本题译自 [JOI 2016 Final](https://www.ioi-jp.org/joi/2015/2016-ho/index.html) T3「[鉄道運賃](https://www.ioi-jp.org/joi/2015/2016-ho/2016-ho.pdf)」**

给出一个包含 $N$ 个点，$M$ 条无向边的图，点的编号为 $1\ldots N$，边的编号为 $1\ldots M$。  
$i$ 号边 $(1\leqslant i\leqslant M)$ 连接结点 $U_i$ 和 $V_i$。开始时，每条边的长度为 $1$ 。  
接下来有 $Q$ 次修改，第 $j$ 次修改 $(1\leqslant j\leqslant Q)$ 会将 $R_j$ 号边的长度由 $1$ 修改为 $2$ 。保证每条边最多只修改一次。  
每次修改后，试求：与原图（未作任何修改的图）相比，有多少结点到结点 $1$ 的最短路变长了。

# 输入格式

第一行有三个整数 $N, M, Q$，用空格分隔。  
在接下来的 $M$ 行中，第 $i(1\leqslant i\leqslant M)$ 行有两个整数 $U_i, V_i$，用空格分隔。  
在接下来的 $Q$ 行中，第 $j(1\leqslant j\leqslant Q)$ 行有一个整数 $R_j$。  
输入的所有数的含义见题目描述。

# 输出格式

输出共 $Q$ 行，第 $j(1\leqslant j\leqslant Q)$ 行有一个整数，表示第 $j$ 次修改后，与原图相比，有多少结点到结点 $1$ 的最短路变长了。

# 样例

#### 输入样例 1
```plain
5 6 5
1 2
1 3
4 2
3 2
2 5
5 3
5
2
4
1
3
```

#### 输出样例 1
```plain
0
2
2
4
4
```

#### 样例解释 1
|时刻\最短路之长|2|3|4|5|
|:-:|:-:|:-:|:-:|:-:|
|原图|1|&nbsp;1&nbsp;|2|&nbsp;2&nbsp;|
|第 $1$ 次修改后|&nbsp;1&nbsp;|1|&nbsp;2&nbsp;|2|
|第 $2$ 次修改后|1|&nbsp;2&nbsp;|2|3|
|第 $3$ 次修改后|&nbsp;1&nbsp;|2|&nbsp;2&nbsp;|&nbsp;3&nbsp;|
|第 $4$ 次修改后|2|&nbsp;2&nbsp;|&nbsp;3&nbsp;|3|
|第 $5$ 次修改后|&nbsp;2&nbsp;|2|4|&nbsp;3&nbsp;|

例如，在第 $3$ 次修改后，结点 $3$ 和结点 $5$ 到结点 $1$ 的最短路与原图相比变长了，因此输出的第三个数是 2。

#### 输入样例 2
```plain
4 6 6
1 2
1 3
1 4
2 3
2 4
3 4
1
4
2
5
3
6
```

#### 输出样例 2
```plain
1
1
2
2
3
3
```

#### 输入样例 3
```plain
2 1 1
1 2
1
```

#### 输出样例 3
```plain
1
```

# 数据范围与提示

对于 $12\%$ 的数据，$N\leqslant 100, M\leqslant 4950, Q\leqslant 30$。  
对于另外 $14\%$ 的数据，$Q\leqslant 30$。  
对于另外 $35\%$ 的数据，将输出的 $Q$ 个整数去重后不超过 $50$ 个。  
对于所有数据，$2\leqslant N\leqslant 10^5, 1\leqslant Q\leqslant M\leqslant 2\times 10^5; 1\leqslant U_i, V_i\leqslant N, U_i ≠ V_i(1\leqslant i\leqslant M); 1\leqslant R_j\leqslant M, R_j ≠ R_k(1\leqslant j<k\leqslant Q)$，保证图连通，无重边。

