
# 题目描述

在北纬 $91°$ ，有一个神奇的国度，叫做企鹅国。这里的企鹅也有自己发达的文明，称为企鹅文明。因为企鹅只有黑白两种颜色，所以他们的数学也是以二进制为基础发展的。

比如早在 $11101001$ 年前，他们就有了异或这样一个数学概念。如果你不知道异或是什么，请出门过墙左转到[这里](https://zh.wikipedia.org/wiki/%E9%80%BB%E8%BE%91%E5%BC%82%E6%88%96)。

再比如早在 $1000010$ 年前，他们的大科学家 `Penguin. Tu` 就提出了[图](https://zh.wikipedia.org/wiki/%E5%9B%BE_%28%E6%95%B0%E5%AD%A6%29#%E6%9C%89/%E7%84%A1_%E5%90%91%E5%9B%BE)和[最短路径](https://zh.wikipedia.org/wiki/%E6%9C%80%E7%9F%AD%E8%B7%AF%E9%97%AE%E9%A2%98)这样一些概念。

<hr>

企鹅国中有 $N$ 座城市，编号从 $1$ 到 $N$ 。

对于任意的两座城市 $i$ 和 $j$ ，企鹅们可以花费 $(i~\mathrm{xor}~j) \times C$ 的时间从城市 $i$ 走到城市 $j$ ，这里 $C$ 为一个给定的**常数**。

当然除此之外还有 $M$ 条**单向**的快捷通道，第 $i$ 条快捷通道从第 $F_i$ 个城市通向第 $T_i$ 个城市，走这条通道需要消耗 $V_i$ 的时间。

现在来自 **P**enguin **K**ingdom **U**niversity 的企鹅豆豆正在考虑从城市 $A$ 前往城市 $B$ 最少需要多少时间？

# 输入格式

从标准输入读入数据。

输入第一行包含三个整数 $N,M,C$ ，表示企鹅国城市的个数、快捷通道的个数以及题面中提到的给定的常数C。

接下来的 $M$ 行，每行三个正整数 $F_i,T_i,V_i$ $(1 \leq F_i \leq N , 1 \leq T_i \leq N , 1\leq V_i \leq 100 )$，分别表示对应通道的起点城市标号、终点城市标号和通过这条通道需要消耗的时间。

最后一行两个正整数 $A,B$ $(1 \leq C \leq 100 )$，表示企鹅豆豆选择的起点城市标号和终点城市标号。

# 输出格式

输出到标准输出。

输出一行一个整数，表示从城市 $A$ 前往城市 $B$ 需要的最少时间。

# 样例

#### 样例输入 1

```plain
4 2 1
1 3 1
2 4 4
1 4
```



#### 样例输出 1

```plain
5
```


#### 样例解释 1
直接从 $1$ 走到 $4$ 就好了。






#### 样例输入 2

```plain
7 2 10
1 3 1
2 4 4
3 6
```



#### 样例输出 2

```plain
34
```


#### 样例解释 2

先从 $3$ 走到 $2$ ，再从 $2$ 通过通道到达 $4$ ，再从 $4$ 走到 $6$。

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 子任务编号 | $N$ | $M$ | 子任务分值 |
|-|-|-|-|
| $1$ | $= 10^{5}$ | $= 0$ | $1$ |
| $2$ | $= 10^{5}$ | $= 1$ | $2$ |
| $3$ | $= 10^{5}$ | $= 3$ | $4$ |
| $4$ | $= 10^{5}$ | $= 10$ | $8$ |
| $5$ | $= 10^{5}$ | $= 10^{3}$ | $15$ |
| $6$ | $= 10^{3}$ | $\leq 5 \times 10^{5}$ | $15$ |
| $7$ | $= 10^{5}$ | $\leq 5 \times 10^{5}$ | $55$ |

<!-- Migrated from original HTML table:
<table class="ui celled center aligned table"><thead><tr><th rowspan="1">子任务编号</th><th rowspan="1">$N$ </th><th rowspan="1">$M$ </th><th rowspan="1">子任务分值</th></tr></thead><tbody><tr><td rowspan="1">$1$ </td><td rowspan="5">$= 10^{5}$ </td><td rowspan="1">$= 0$ </td><td rowspan="1">$1$ </td></tr><tr><td rowspan="1">$2$ </td><td rowspan="1">$= 1$ </td><td rowspan="1">$2$ </td></tr><tr><td rowspan="1">$3$ </td><td rowspan="1">$= 3$ </td><td rowspan="1">$4$ </td></tr><tr><td rowspan="1">$4$ </td><td rowspan="1">$= 10$ </td><td rowspan="1">$8$ </td></tr><tr><td rowspan="1">$5$ </td><td rowspan="1">$= 10^{3}$ </td><td rowspan="2">$15$ </td></tr><tr><td rowspan="1">$6$ </td><td rowspan="1">$= 10^{3}$ </td><td rowspan="2">$\leq 5 \times 10^{5}$ </td></tr><tr><td rowspan="1">$7$ </td><td rowspan="1">$= 10^{5}$ </td><td rowspan="1">$55$ </td></tr></tbody></table>
-->

<!-- END: Migrated markdown table --> 

活泼可爱的出题人给大家留下了下面这张图。

![whatisthis.jpg](/source/loj/6354/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMDQvMDIvNWFjMWJiMjMzM2MyMi5qcGc=.jpg)

<hr style='color: #ddd; margin-bottom: 1em'>

来自 [CodePlus](https://cp.thusaac.com/) 第 4 次月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。  
Credit：idea 与命题/吴凯路　验题/张瀚文  
Git Repo：https://git.thusaac.org/publish/CodePlus4  
感谢腾讯公司对此次比赛的支持。

