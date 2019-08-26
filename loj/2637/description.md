
# 题目描述

$T$ 是一棵有根树，$S$ 是 $T$ 的副本。我们将这两棵树相对应的叶子结点一一合并，就变成了一个树镜像图。如果你无法理解，请参见下图。

<img src="source/loj/2637/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNjM3L3Rlc3RkYXRhL2Rvd25sb2FkLzEuUE5H.PNG" width="50%">

给出一个由 $N$ 个结点 $M$ 条边组成的无向图 $G$，结点依次编号为 $1\ldots N$。  
试求 $G$ 是不是树镜像图，如果它是树镜像图，请输出 $\texttt{YES}$，否则输出 $\texttt{NO}$。

Let T be a rooted tree (a connected undirected acylic graph), and let S be a perfect copy of T. Construct a new graph by taking the union of T and S, and merging the corresponding leaf nodes (but never the root). We call such a graph a tree-mirrored graph.

# 输入格式

第一行有两个整数 $N$ 和 $M$。  
在接下来的 $M$ 行中，每行有两个整数 $x$ 和 $y\:(1≤ x, y≤ N, x≠y)$，表示一条边。

The first line of input contains two integers $N$ and $M$, the number of vertices and edges of a graph $G$. The vertices in $G$ are labeled from $1$ to $N$. The following $M$ lines describe the edges. Each such line contains two integers $x$ and $y (x ≠ y;1 ≤ x,y ≤ N)$, describing one edge. There will be at most one edge between any pair of vertices.


# 输出格式

输出仅一行，仅包含一个字符串 $\texttt{YES}$ 或 $\texttt{NO}$，表示 $G$ 是不是树镜像图。

The first and only line of output should contain the string $\texttt{YES}$ if the graph $G$ is a tree-mirrored graph, and $\texttt{NO}$ otherwise.

# 样例

#### 样例输入 1
```plain
7 7
1 2
2 3
3 4
4 5
5 6
6 7
7 1
```

#### 样例输出 1
```plain
NO
```

#### 样例输入 2
```plain
6 6
1 2
2 3
2 4
3 5
4 5
5 6
```

#### 样例输出 2
```plain
YES
```

#### 样例输入 3
```plain
22 28
13 8
8 1
1 22
1 12
1 14
13 18
13 4
4 20
20 7
13 15
15 3
15 9
9 16
9 19
22 5
12 5
14 5
5 11
11 6
18 6
7 10
10 17
17 6
3 21
21 6
16 2
19 2
2 21
```

#### 样例输出 3
```plain
YES
```

#### 样例说明 3
这组样例对应「题目描述」中的图。


# 数据范围与提示

对于 $30\%$ 的数据，$3 ≤ N,M ≤ 300$。  
对于 $60\%$ 的数据，$3 ≤ N,M ≤ 3500$。  
对于所有数据，$3 ≤ N,M ≤ 10^5$。

