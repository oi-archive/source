
# 题目描述

给定 $n$ 和 $m$，记 $A_n$ 为所有 $n$ 个节点的无标号有根二叉树构成的集合（任意非叶子节点的左和右被视作不等价，即一个节点交换左右子树后可能会变成一棵不同的树）。对于任意 $0 \le k \le m$，要求计算 
$$
\sum_{T \in A_n} {\sum_{\substack{u \in \operatorname{leaf}(T) \\ v \in \operatorname{leaf}(T)}} \operatorname{len}(u, v)^k \pmod{1234567891}}
$$
 其中，$\operatorname{leaf}(T)$ 表示二叉树 $T$ 所有叶子节点构成的集合，$\operatorname{len}(u, v)$ 表示树上 $u$ 和 $v$ 之间的路径长度（即经过的总点数，包括端点）。

# 输入格式

一行两个整数，$n,m$。


# 输出格式

一行输出 $m+1$ 个数，表示 $k\in[0,m]$ 相对应的答案。


# 样例

#### 样例输入
```plain
3 10
```
#### 样例输出
```plain
7 9 15 33 87 249 735 2193 6567 19689 59055
```

# 数据范围与提示

$1 \le n \le 10^7, 0 \le m \le 300$。


