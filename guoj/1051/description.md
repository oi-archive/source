
# 题目描述

在一个 $\text{n} \times \text{n}$ 个方格的国际象棋棋盘上，马（骑士）可以攻击的棋盘方格如图所示。棋盘上某些方格设置了障碍，骑士不得进入。

![233](/source/guoj/1051/img/aHR0cHM6Ly93d3cub2ouc3d1c3QuZWR1LmNuL3VwbG9hZC9pbWFnZS9wcm9ibGVtLzE3NTkucG5n.png)

对于给定的 $\text{n} \times \text{n}$ 个方格的国际象棋棋盘和障碍标志，计算棋盘上最多可以放置多少个骑士，使得它们彼此互不攻击。

# 输入格式

第一行有两个正整数 $\text{n}$ 和 $\text{m}$ $( 1 \leq n \leq 200, 0 \leq m \leq n^2 - 1 )$ 分别表示棋盘的大小和障碍数。

# 输出格式

输出计算出的共存骑士数。

# 样例

#### 样例输入
```plain
3 2
1 1
3 3
```
#### 样例输出
```plain
5
```

# 数据范围与提示

$1\leq n\leq 200$

$0 \leq m \leq n^2-1$

