
# 题目描述

这是一道（集合并卷积的）模板题。

给定一个集合 $S = \{{x_1}, {x_2}, \dots, {x_n}\}$ 和一个 $S$ 上的集合族 $\mathcal F = \{{S_0}, {S_1}, \dots, {S_{m-1}}\}$。

一个覆盖 $\mathcal C$ 是 $\mathcal F$ 的一个子族，满足 $\mathcal C$ 中所有集合的并为 $S$。

求大小不大于 $k$ 的覆盖的数量 $\text{mod}\;998244353 %% \bmod 会在前面产生一个空白。。$。

两个覆盖 ${\mathcal C_1}, {\mathcal C_2}$ 不同，当且仅当存在 $i$ 使 $S_i \in {\mathcal C_1} \land S_i \notin {\mathcal C_2}$ 或 $S_i \notin {\mathcal C_1} \land S_i \in {\mathcal C_2}$。$S_i$ 和 $S_j$ 不同当且仅当 $i \neq j$。

# 输入格式

第 $1$ 行：$n\ m\ k$

第 $2$ 行：$s_0\ s_1\ \ldots s_{m-1}$，$s_i$ 二进制第 $j$ 位为 $0$ 表示 ${x_j} \notin {S_i}$ ，为 $1$ 表示 ${x_j} \in {S_i}$

# 输出格式

$1$ 个非负整数，表示大小不大于 $k$ 的覆盖的数量 $\text{mod}\;998244353 %% \bmod 会在前面产生一个空白。。$。

# 样例

#### 样例输入
```plain
4 8 2
7 10 8 11 5 15 4 5
```

#### 样例输出
```plain
16
```

# 数据范围与提示

* $1 \leq k \leq n \leq 22$
* $1 \leq m \leq 131072$
* $1 \leq s_i \leq 2^n-1$

#### 子任务

1. （16 分）$n \leq 9$，$m \leq 16$
2. （20 分）$n \leq 13$，$m \leq 256$
3. （14 分）$n \leq 16$，$m \leq 2048$
4. （25 分）$n \leq 18$，$m \leq 8192$
5. （25 分）没有附加限制

