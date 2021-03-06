
# 题目描述

给定一个长度为$n$的数组$A$，定义一个二元函数$f(x, y), 1 \leq x \leq 10^9, 1 \leq y \leq n$：

$$ f(x, y) = \begin{cases} A_y & x = 1 \\ f(x-1, y) + A_y & y = 1 \text{ and } x \neq 1 \\ \min \{ f(x-1, y-1), f(x-1, y) \} + A_y & \text{otherwise} \end{cases} $$

你需要回答$q$个询问，每个询问给出两个数$x_i, y_i$, 你需要求出$f(x_i, y_i)$的值．

# 输入格式

第一行一个整数$n$.

接下来一行$n$个整数表示$A_i$.

接下来一行一个整数$q$.

接下来$q$行，每行两个整数$x_i, y_i$．

# 输出格式

每行一个整数表示答案．

# 样例

**样例 1 输入**
```
6
2 2 3 4 3 4
4
4 5
3 4
3 4
2 3
```

**样例 1 输出**
```
12
9
9
5
```

本题有附加样例，请自行下载。

# 数据范围与提示

对于所有数据，有$1 \leq n, q \leq 5 \times 10^5, 0 \leq A_i \leq 10^9, 1 \leq x_i \leq 10^9, 1 \leq y_i \leq n$.

| 子任务编号 |         $n$          | $\max x_i$  |         $q$          | 特殊限制 | 分值 |
| :--------: | :------------------: | :---------: | :------------------: | :------: | :--: |
|     1      |      $\leq 300$      | $\leq 10^3$ |     $\leq 10^5$      |    无    |  13  |
|     2      |      $\leq 300$      | $\leq 10^9$ |     $\leq 10^5$      |    无    |  14  |
|     3      |     $\leq 10^5$      | $\leq 10^5$ |     $\leq 10^5$      |    无    |  31  |
|     4      |     $\leq 10^5$      | $\leq 10^5$ |     $\leq 10^5$      | 性质$1$  |  15  |
|     5      | $\leq 5 \times 10^5$ | $\leq 10^9$ | $\leq 5 \times 10^5$ | 性质$2$  |  18  |
|     6      | $\leq 5 \times 10^5$ | $\leq 10^9$ | $\leq 5 \times 10^5$ |    无    |  9   |

性质$1$：$A_i$在一定范围内随机生成．

性质$2$：询问中所有$x_i$均相同．

出题人：dy0607

来源：HNOI 2018 省队集训 Day 1 T2

