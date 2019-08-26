
# 题目描述

> <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 是神仙。

小学里，~~有故事~~看过童话故事的你一定知道神仙一般住在幽深的山林里，<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 也不例外。然而由于 <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 长时间研究理论计算机科学，不经意间~~秃了顶~~他建立了 $n$ 个有标号的亭子，分别为 $1\ldots n$，它们之间一共有 $m$ 条道路。当然，最优化理论大师 <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 不可能建造一个亭子到它自身的道路或两个亭子之间重复的道路。

最近 <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 听说了「饭后百步走活到九十九」这句话，于是他想：作为神仙，怎么能不长寿呢？但为了确保自己能长寿，他还是决定开始暴走。具体地，每次他将会选择一些亭子和一些道路，使得**存在一种方案，他可以从一个亭子出发不重复不遗漏地走完所有所选的道路，并回到这个亭子**。

<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 想让你告诉他一共有多少种不同的选择亭子和道路的方案，使其能够满足于他的要求。答案对 $998244353$ 取模。

> <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 用了 $1.1$ 秒就得出了答案。他说：本来想让你求出我有多少不同的行走方案的，鉴于你用了这么长时间才把这题读完，那还是先把这题做出来吧。


# 输入格式

第一行两个整数 $n,m$，表示有 $n$ 个顶点和 $m$ 条边。

接下来 $m$ 行，每行两个整数 $u,v$ ，表示一条连接 $u$ 和 $v$ 的无向边。

# 输出格式

一行一个整数表示答案。

# 样例

#### 样例输入
```plain
4 5
1 2
2 4
1 3
1 4
2 3
```

#### 样例输出
```plain
1
```

# 数据范围与提示

$100\%$ 的数据满足 $1\leqslant n\leqslant 20,0\leqslant m\leqslant \dfrac{n(n-1)}2$。

对于 $10\%$ 的数据：$n\leqslant 6$；

对于另外 $30\%$ 的数据：$n\leqslant 16$；

对于另外 $20\%$ 的数据：$n\leqslant 20$，$G$ 为完全图；

对于另外 $20\%$ 的数据：$n\leqslant 18$；

对于另外 $20\%$ 的数据：$n\leqslant 20$。

