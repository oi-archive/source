
# 题目描述

对于一个 $n$ 阶排列 $p$，我们建立一张**无向简单图** $G(p)$，有 $n$ 个节点，标号从 $1$ 到 $n$，每个点向左右两侧最近的比它大的点以及比它小的点连边。  
形式化地，在 $G(p)$ 中，$\forall u<v$，边 $(u,v)$ 存在当且仅当以下四个条件至少一个成立：

* $p_u<p_v$，且不存在 $u<i<v$ 满足 $p_u<p_i$；
* $p_u>p_v$，且不存在 $u<i<v$ 满足 $p_u>p_i$；
* $p_u<p_v$，且不存在 $u<i<v$ 满足 $p_i<p_v$；
* $p_u>p_v$，且不存在 $u<i<v$ 满足 $p_i>p_v$。

对于区间 $[l,r]$，规定其对应的排列 $p[l:r]$ 表示与 $p_l,p_{l+1},\cdots,p_r$ 大小顺序相同的 $(r-l+1)$ 阶排列。  
例如，对于排列 $q=\{1,4,2,5,3\}$，$q[2:4]$ 表示与 $\{4,2,5\}$ 大小顺序相同的 $3$ 阶排列，即 $\{2,1,3\}$。

无向图 $G$ 的最小[染色](https://en.wikipedia.org/wiki/Graph_coloring)数即给图的每个点染一种颜色，满足每条边的两端颜色不同，最少需要的颜色种类数。记为 $c(G)$。

现在给定一个 $n$ 阶排列 $p$，请你求出 $G(p)$ 的染色数，另外有 $q$ 次询问，每次询问一个区间 $[l,r]$，请你求出其所有子区间对应的排列的图的染色数最大值 $\mathrm{maxc}$，以及达到最大值的子区间个数 $\mathrm{cnt}$。  
（形式化地，对于一对 $l,r$，求所有满足 $l\le l'\le r'\le r$ 的 $l',r'$ 中，$c(G(p[l':r']))$ 的最大值 $\mathrm{maxc}$，以及满足 $c(G(p[l':r']))=i$ 的 $l',r'$ 组数 $\mathrm{cnt}$。）

<div class="lang-divider"></div>

For an $n$-order permutation $p$, we set up an **undirected simple graph** $G(p)$ with $n$ vertices numbered from $1$ to $n$.
We create an edge between each vertice $i$ and the nearest vertices in each side which correspond a greater (or less) $p$ value than $p_i$.  
Formally,in this graph, $\forall u<v$, the edge $(u, v)$ exists iff at least one of the following four conditions hold:

* $p_u<p_v$, and no $u<i<v$ exists such that $p_u<p_i$;
* $p_u>p_v$, and no $u<i<v$ exists such that $p_u>p_i$;
* $p_u<p_v$, and no $u<i<v$ exists such that $p_i<p_v$;
* $p_u>p_v$, and no $u<i<v$ exists such that $p_i>p_v$.

For a segment $[l,r]$, define its **corresponding permutation** $p[l:r]$ as an $(r-l+1)$-order permutation with the same relative orders of elements as $p_l,p_{l+1},\cdots,p_r$; that is, for all $1 \leq i < j \leq r-l+1$, the boolean value $[p_{l-1+i} < p_{l-1+j}]$ is the same as the boolean value $[(p[l:r])_i < (p[l:r])_j]$.   
For instance, for the permutation $q=\{1,4,2,5,3\}$, $q[2:4]$ is a permutation of length $3$ with the same relative orders of elements as $\{4,2,5\}$, i.e. $\{2,1,3\}$.

The [chromatic number](https://en.wikipedia.org/wiki/Graph_coloring) of an undirected graph $G$ is the smallest number of colors needed to give each vertex a color such that every edge connects two vertices with different colors. We call this $c(G)$.

Given a permutation $p$ of length $n$, please find the chromatic number of $G(p)$.   
Additionally, please answer $q$ queries in the form of $[l,r]$ asking for: the greatest chromatic number among those of all **corresponding permutations** of each subsegment of $[l,r]$, $\mathrm{maxc}$; and the number of subsegment that achieve this maximum number $\mathrm{cnt}$.  
(Formally,for each given $l,r$,$\forall l\le l'\le r' \le r$,calculate the maximum possible value of $c(G(p[l':r']))$,called $\mathrm{maxc}$,and $\sum_{l\leqslant l'\leqslant r'\leqslant r}[c(G(p[l':r']))=\mathrm{maxc}]=\mathrm{cnt}$ .)

# 输入格式

第一行一个正整数 $n$。

第二行 $n$ 个正整数 $p_1,p_2,\cdots ,p_n$。

第三行一个整数 $q$。

接下来 $q$ 行每行两个正整数 $l,r$ 表示一组询问。

<div class="lang-divider"></div>

The first line contains a positive integer $n$.

The second line contains $n$ positive integers $p_1,p_2,\cdots ,p_n$.

The third line contains an integer $q$.

The following $q$ lines each contains two positive integers $l,r$, denoting a query.

# 输出格式

输出共 $q+1$ 行，第一行一个正整数表示 $G(p)$ 的染色数，接下来每行两个整数 $\mathrm{maxc},\mathrm{cnt}$。

<div class="lang-divider"></div>

Output contains $q+1$ lines in total. The first one should contain a positive integer denoting the chromatic number of $G(p)$, followed by $q$ lines each containing two integers $\mathrm{maxc},\mathrm{cnt}$ for each query.

# 样例

#### 样例输入
```plain
6
1 4 5 3 6 2
5
1 6
1 3
2 5
2 6
3 3
```

#### 样例输出
```plain
4
4 1
2 3
3 3
3 6
1 1
```

#### 样例解释

下图描述 $G(p)$ 及一种染色方案：

![sampleexp.png](/source/loj/554/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMDIvMjIvNWE4ZTMxZTJkNzE3OS5wbmc=.png)

<div class="lang-divider"></div>

#### Sample Input
```plain
6
1 4 5 3 6 2
5
1 6
1 3
2 5
2 6
3 3
```

#### Sample Output
```plain
4
4 1
2 3
3 3
3 6
1 1
```

#### Sample Explanation

The following picture describes $G(p)$ and a way of coloring:

![sampleexp.png](/source/loj/554/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMDIvMjIvNWE4ZTMxZTJkNzE3OS5wbmc=.png)

# 数据范围与提示

对于所有数据，$1\le n\le 3\times 10^5,0\le q\le 3\times 10^5$。

详细的数据限制及约定如下（留空表示和上述所有数据的约定相同）：

|Subtask #|分值（百分比）|$n$|$q$|
|:-:|:-:|:-:|:-:|
|$1$|$10$|$\le 10$|$\le 10$|
|$2$|$15$|$\le 100$|$\le 10^4$|
|$3$|$15$|$\le 2000$|$\le 10^4$|
|$4$|$15$|-|$=0$|
|$5$|$15$|-|$\le 5$|
|$6$|$30$|-|-|

<div class="lang-divider"></div>

For all test cases, $1\le n\le 3\times 10^5,0\le q\le 3\times 10^5$.

Detailed constraints and hints are as follows (blank grids denote the same constraints as mentioned above):

|Subtask #|Score (percentage)|$n$|$q$|
|:-:|:-:|:-:|:-:|
|$1$|$10$|$\le 10$|$\le 10$|
|$2$|$15$|$\le 100$|$\le 10^4$|
|$3$|$15$|$\le 2000$|$\le 10^4$|
|$4$|$15$|-|$=0$|
|$5$|$15$|-|$\le 5$|
|$6$|$30$|-|-|

