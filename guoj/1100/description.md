
# 题目描述

恭喜你，你又发现了一道数据结构题。

在这道题中，你需要维护一个长度为 $n$ 的序列 $a_0,a_1 \cdots a_{n-1}$。

你需要处理两种操作：

1. `edit x y`：把 $a_x$ 修改为 $y$。

2. `query l r k`：你需要输出最大的非负整数 $m$，使 $k,k+1 \cdots k+m-1$ 为 $a_l,a_{l+1} \cdots a_r$ 的子序列。

保证每时每刻序列中的元素均在 $[0,n)$ 范围内。

# 输入格式

第一行两个正整数，$n$ 和 $q$，表示序列的长度和操作的数量。

第二行 $n$ 个正整数 $a_0,a_1 \cdots a_{n-1}$，为 $a$ 数组的初始值。

接下来 $q$ 行每行形如：

1. `edit x y`

2. `query l r k`

# 输出格式

对于每个 `query` 操作输出一行，表示询问的答案。


# 样例

#### 样例输入1
```
6 7
2 3 3 3 3 4
query 0 0 2
query 0 4 2
query 0 5 2
query 0 1 1
edit 1 1
query 0 1 1
query 0 2 1
```

#### 样例输出1
```
1
2
3
0
1
1
```

# 数据范围与提示

对于所有数据，$2 \leq n,q \leq 2 \times 10^5$，$0 \leq a_i,x,y,k<n$，$0 \leq l \leq r <n$。

Subtask 1（10pts）：$n,q \leq 300$。

Subtask 2（20pts）：$n,q \leq 5000$。

Subtask 3（30pts）：$n,q \leq 50000$。

Subtask 4（20pts）：没有`edit`操作。

Subtask 5（20pts）：无特殊限制。

命题人：fjzzq2002

