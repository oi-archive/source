
# 题目描述

对于一个 $n$ 阶排列 $p$，我们建立一张**无向简单图** $G(p)$，有 $n$ 个节点，标号从 $1$ 到 $n$，每个点向左右两侧最近的比它大的点以及比它小的点连边。  
形式化地，在 $G(p)$ 中，$\forall u<v$，边 $(u,v)$ 存在当且仅当以下四个条件至少一个成立：

* $p_u<p_v$，且不存在 $u<i<v$ 满足 $p_u<p_i$；
* $p_u>p_v$，且不存在 $u<i<v$ 满足 $p_u>p_i$；
* $p_u<p_v$，且不存在 $u<i<v$ 满足 $p_i<p_v$；
* $p_u>p_v$，且不存在 $u<i<v$ 满足 $p_i>p_v$。

现在在所有的 $n$ 阶排列中随机选择一个排列 $p$，请求出 $G(p)$ 中三元简单环的期望个数，答案对 $998244353$ 取模。

<div class="lang-divider"></div>

For an $n$-order permutation $p$, we set up an **undirected simple graph** $G(p)$ with $n$ vertices numbered from $1$ to $n$.
We create an edge between each vertice $i$ and the nearest vertices in each side which correspond a greater (or less) $p$ value than $p_i$.  
Formally,in this graph, $\forall u<v$, the edge $(u, v)$ exists iff at least one of the following four conditions hold:

* $p_u<p_v$, and no $u<i<v$ exists such that $p_u<p_i$;
* $p_u>p_v$, and no $u<i<v$ exists such that $p_u>p_i$;
* $p_u<p_v$, and no $u<i<v$ exists such that $p_i<p_v$;
* $p_u>p_v$, and no $u<i<v$ exists such that $p_i>p_v$.

Now we randomly choose a permutation $p$ from all $n$-order permutations. Your task is to calculate the expected number of the $3$-cycles in $G(p)$. You only need to output the answer modulo $998244353$. 

# 输入格式

一行一个正整数 $n$。

<div class="lang-divider"></div>

The only line contains a positive integer $n$ which means the order of the permutation. 

# 输出格式

一行一个整数 $\mathrm{ans}$ 表示答案。

<div class="lang-divider"></div>

Output only one line,which contains an integer $\mathrm{ans}$ which means the expected number of the $3$-cycles in $G(p)$ modulo $998244353$. 

# 样例

#### 样例输入 1

```plain
3
```

#### 样例输出 1

```plain
665496236
```

#### 样例解释 1

在所有 $n!$ 种排列中共有 $4$ 个三元简单环（$\{1,3,2\},\{2,3,1\},\{2,1,3\},\{3,1,2\}$ 各一个），所以答案为 $\frac{4}{3!}=\frac{2}{3}$，即 $2\times 3^{-1} \pmod{998244353}=665496236$。

#### 样例输入 2

```plain
91
```

#### 样例输出 2

```plain
116578319
```

<div class="lang-divider"></div>

#### Sample Input 1

```plain
3
```

#### Sample Output 1

```plain
665496236
```

#### Sample Explanation 1

It is easy to count that there are four $3$-cycles in total from the $3!$ permutations(each of $\{1,3,2\},\{2,3,1\},\{2,1,3\},\{3,1,2\}$ has one). So answer is $\frac{4}{3!}=\frac{2}{3}$,that is, $2\times 3^{-1} \pmod{998244353}=665496236$.

#### Sample Input 2

```plain
91
```

#### Sample Output 2

```plain
116578319
```

# 数据范围与提示

对于所有数据，$1\le n<998244353$。

详细的数据限制及约定如下（留空表示和上述所有数据的约定相同）：

|Subtask #|分值（百分比）|$n$|
|:-:|:-:|:-:|
|$1$|$15$|$\le 10$|
|$2$|$20$|$\le 100$|
|$3$|$40$|$\le 10^6$|
|$4$|$15$|$\ge 998000000$|
|$5$|$10$|-|

<div class="lang-divider"></div>

For all test cases, $1\le n<998244353$.

Detailed constraints and hints are as follows (blank grids denote the same constraints as mentioned above):

|Subtask #|Score (percentage)|$n$|
|:-:|:-:|:-:|
|$1$|$15$|$\le 10$|
|$2$|$20$|$\le 100$|
|$3$|$40$|$\le 10^6$|
|$4$|$15$|$\ge 998000000$|
|$5$|$10$|-|

