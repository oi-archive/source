
# 题目描述

给定一个 $n$ 个点 $m$ 条边的带权图，每条边的边权为 $w_i$ ，有两种询问。

1.求其最小方差生成树。

2.对于每条边，问如果删除它，残余图（包含 $n$ 个点 $m-1$ 条边）的最小方差生成树。

你只需要求出最小的方差值。如果图不连通，输出 $-1$。

一个生成树的方差定义为它的所有边的权值的方差。

对于 $N$ 个变量 $x_1,x_2...x_N$，其方差计算方式为 $\sigma^2 = \frac{\sum_{1\leq i\leq N}(x_i-\mu)^2}{N}$

其中 $\sigma^2$ 为方差，$\mu$ 为平均值，由于是生成树，所以 $N=n-1$。

你需要将方差乘 $N^2$ 后输出，可以证明这是一个整数。

# 输入格式

第 $1$ 行包含 $3$ 个整数 $n,m,T$，表示点数，边数和询问类型。

接下来 $m$ 行，每行包含 $3$ 个正整数 $u_i,v_i,w_i$ ，表示第 $i$ 条边连接 $u_i$ 和 $v_i$ ，权值为 $w_i$ ，保证无自环，但可能有重边。

# 输出格式

当 $T=1$，输出一个数表示答案。

当 $T=2$，输出 $m$ 行，每行一个数表示删除第 $i$ 条边的答案。

如果图不连通，输出-1。


# 样例

#### 样例输入

```plain
4 4 2
1 2 1
2 3 3
1 3 2
3 4 5
```

#### 样例输出

```plain
14
26
24
-1
```

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 子任务 | 分值 | $T$ | $n \le$ | $m \le$ | $C \le$ |
|:-:|:-:|:-:|:-:|:-:|:-:|
| $1$ | $5$ | $1$ | $m$ | $20$ | $10^6$ |
| $2$ | $10$ | $1$ | $m$ | $200$ | $10^6$ |
| $3$ | $10$ | $1$ | $m$ | $1000$ | $10^4$ |
| $4$ | $10$ | $1$ | $m$ | $1000$ | $10^6$ |
| $5$ | $10$ | $1$ | $m$ | $10^5$ | $10^9$，且满足特性 1 |
| $6$ | $15$ | $1$ | $m$ | $10^5$ | $10^9$ |
| $7$ | $20$ | $2$ | $300$ | $10^5$ | $10^6$ |
| $8$ | $20$ | $2$ | $300$ | $10^5$ | $10^{18}$ |

<!-- Migrated from original HTML table:
<table class='ui celled table'>
    <thead>
        <tr>
            <th style='text-align: center'> 子任务 </th>
            <th style='text-align: center'> 分值 </th>
            <th style='text-align: center'> $T$ </th>
            <th style='text-align: center'> $n \le$ </th>
            <th style='text-align: center'> $m \le$ </th>
            <th style='text-align: center'> $C \le$ </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style='text-align: center'> $1$ </td>
            <td style='text-align: center'> $5$ </td>
            <td style='text-align: center' rowspan='6'> $1$ </td>
            <td style='text-align: center' rowspan='6'> $m$ </td>
            <td style='text-align: center'> $20$ </td>
            <td style='text-align: center' rowspan='2'> $10^6$ </td>
        </tr>
        <tr>
            <td style='text-align: center'> $2$ </td>
            <td style='text-align: center'> $10$ </td>
            <td style='text-align: center'> $200$ </td>
        </tr>
        <tr>
            <td style='text-align: center'> $3$ </td>
            <td style='text-align: center'> $10$ </td>
            <td style='text-align: center' rowspan='2'> $1000$ </td>
            <td style='text-align: center'> $10^4$ </td>
        </tr>
        <tr>
            <td style='text-align: center'> $4$ </td>
            <td style='text-align: center'> $10$ </td>
            <td style='text-align: center'> $10^6$ </td>
        </tr>
        <tr>
            <td style='text-align: center'> $5$ </td>
            <td style='text-align: center'> $10$ </td>
            <td style='text-align: center' rowspan='2'> $10^5$ </td>
            <td style='text-align: center'> $10^9$，且满足特性 1 </td>
        </tr>
        <tr>
            <td style='text-align: center'> $6$ </td>
            <td style='text-align: center'> $15$ </td>
            <td style='text-align: center'> $10^9$ </td>
        </tr>
        <tr>
            <td style='text-align: center'> $7$ </td>
            <td style='text-align: center'> $20$ </td>
            <td style='text-align: center' rowspan='2'> $2$ </td>
            <td style='text-align: center' rowspan='2'> $300$ </td>
            <td style='text-align: center' rowspan='2'> $10^5$ </td>
            <td style='text-align: center'> $10^6$ </td>
        </tr>
        <tr>
            <td style='text-align: center'> $8$ </td>
            <td style='text-align: center'> $20$ </td>
            <td style='text-align: center'> $10^{18}$ </td>
        </tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

特性1：第 $i$ 条边连接点 $(i\bmod n)+1$ 和点 $((i+1)\bmod n)+1$，且 $w_i\le w_{i+1}$。

