
# 题目描述

给出一个 $N \times N$ 的矩阵 $\mathbf{B}$ 和一个 $1 \times N$ 的矩阵 $\mathbf{C}$。求出一个 $1 \times N$ 的 $01$ 矩阵 $\mathbf{A}$，使得
$D=(\mathbf{A}\mathbf{B}-\mathbf{C})\mathbf{A}^T$ 最大。其中 $\mathbf{A}^T$ 为 $\mathbf{A}$ 的转置。输出 $D$。

# 输入格式

第一行输入一个整数 $N$，接下来 $N$ 行输入 $\mathbf{B}$ 矩阵， 第 $i$ 行第 $j$ 个数字代表 $B_{ij}$.

接下来一行输入 $N$ 个整数，代表矩阵 $\mathbf{C}$。矩阵 $B$ 和矩阵 $C$ 中每个数字都是不超过 $1000$ 的非负整数。

# 输出格式

输出最大的 $D$。

# 样例

#### 样例输入
```plain
3
1 2 1
3 1 0
1 2 3
2 3 7
```

#### 样例输出
```plain
2
```

# 数据范围与提示

对于所有的数据，$1 \leq N \leq 500$。

