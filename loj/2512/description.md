
# 题目描述

有一条长度为 $n$ 的链（ $\forall 1 \leq i < n$ ，点 $i$ 与点 $i+1$ 之间有一条边的无向图）， 每个点有一个整数权值，第 $i$ 个点的权值是 $a_i$ 。现在有 $m$ 个操作，每个操作如下：

操作 1（修改）：给定链上两个节点 $u$、$v$ 和一个整数 $d$，表示将链上 $u$ 到 $v$ 唯一的简单路径上每个点权值都加上 $d$。

操作 2（询问）：给定两个正整数 $l$、$r$，表示求链上所有节点个数大于等于 $l$ 且小于等于 $r$ 的简单路径节点权值和之和。由于答案很大，只用输出对质数 $1000000007$ 取模的结果即可。

一条节点个数为 $k$ 的简单路径节点权值和为这条上所有 $k$ 个节点（包括端点）的权值之和，而本题中要求是对所有满足要求的简单路径，求这一权值和的和。

由于是无向图，路径也是无向的，即点 $1$ 到点 $2$ 的路径与点 $2$ 到点 $1$ 的路径是同一条，不要重复计算。

# 输入格式

输入第一行包含两个正整数 $n$、$m$，分别表示节点个数和操作次数。

第二行包含 $n$个整数，其中第 $i$ 个数 $a_i$ 为第 $i$ 个点的初始权值。

接下来 $m$行，每行为 ```1 u v d```或 ```2 l r```的形式，分别表示进行一次操作 1（修改）或操作 2（询问）。 

# 输出格式

对于每次询问，输出一行一个整数，表示答案对 $1000000007$ 取模的余数。

# 样例

#### 样例输入 1
```plain
5 5
1 1 1 1 1
2 5 5
2 1 2
1 1 2 2
2 1 1
1 1 5 3
```

#### 样例输出 1
```plain
5
13
9
```

#### 样例解释 1：
节点个数为 $5$ 的简单路径只有 $1$ 条，权值和为 $5$，故第一次询问输出 $5$。

节点个数为 $1$ 的简单路径有 $5$ 条，每条权值和都是 $1$；节点个数为 $2$ 的简单路径有 $4$ 条，每条权值和都是 $2$，故第二次询问输出 $13 $。

在将点 $1$ 和点 $2$ 的权值加 $2$ 后，$5$条节点个数为 $1$ 的简单路径权值和分别 为 $3$、$3$、$1$、$1$、$1$，故第三次询问输出 $9$。


# 数据范围与提示

记操作 1（修改）的次数为 $m^\prime$。

对于全部数据， 保证 $n \leq 200000, m \leq 500000, m^\prime \leq 100000, 0 \leq a_i < 1000000007$

$1 \leq u \leq n, 1\leq v \leq n, 0 \leq d < 1000000007, l \leq r \leq n$ 。

对于每个数据点的详细规模与约定见下表。
<!-- BEGIN: Migrated markdown table -->

| 测试点 | $n\le$ | $m\le$ | $m'\le$ | 约束 |
|:-:|:-:|:-:|:-:|:-:|
| 1 | $50$ | $50$ | $50$ | 无 |
| 2 | $50$ | $50$ | $50$ | 无 |
| 3 | $300$ | $300$ | $300$ | 无 |
| 4 | $300$ | $300$ | $300$ | 无 |
| 5 | $5000$ | $5000$ | $5000$ | 无 |
| 6 | $5000$ | $5\times 10^5$ | $5000$ | 无 |
| 7 | $5000$ | $5\times 10^5$ | $5000$ | 无 |
| 8 | $5000$ | $5\times 10^5$ | $10^5$ | 无 |
| 9 | $2\times 10^5$ | $1$ | $0$ | 保证 $l=1,r=n$ |
| 10 | $2\times 10^5$ | $5\times 10^5$ | $0$ | 无 |
| 11 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 保证 $u=v$ |
| 12 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 保证 $l=1,r=n$ |
| 13 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 保证 $u=1,v=n,a_i=0$ |
| 14 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 保证 $u=1,v=n$ |
| 15 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 保证 $d=1,a_i=0$ |
| 16 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 保证 $d=1$ |
| 17 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 保证 $a_i=0$ |
| 18 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 保证 $a_i=0$ |
| 19 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 无 |
| 20 | $2\times 10^5$ | $5\times 10^5$ | $10^5$ | 无 |

<!-- Migrated from original HTML table:
<table><thead>
  <tr>
    <th style='text-align:center'>测试点</th>
    <th style='text-align:center'> $n\le$ </th>
    <th style='text-align:center'> $m\le$ </th>
    <th style='text-align:center'> $m'\le$ </th>
    <th style='text-align:center'>约束</th>
  </tr></thead><tbody>
  <tr>
    <td style='text-align:center'>1</td>
    <td rowspan="2" style='text-align:center'> $50$ </td>
    <td rowspan="2" style='text-align:center'> $50$ </td>
    <td rowspan="2" style='text-align:center'> $50$ </td>
    <td rowspan="8" style='text-align:center'>无</td>
  </tr>
  <tr>
    <td style='text-align:center'>2</td>
  </tr>
  <tr>
    <td style='text-align:center'>3</td>
    <td rowspan="2" style='text-align:center'> $300$ </td>
    <td rowspan="2" style='text-align:center'> $300$ </td>
    <td rowspan="2" style='text-align:center'> $300$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>4</td>
  </tr>
  <tr>
    <td style='text-align:center'>5</td>
    <td rowspan="4" style='text-align:center'> $5000$ </td>
    <td style='text-align:center'> $5000$ </td>
    <td rowspan="3" style='text-align:center'> $5000$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>6</td>
    <td rowspan="3" style='text-align:center'> $5\times 10^5$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>7</td>
  </tr>
  <tr>
    <td style='text-align:center'>8</td>
    <td style='text-align:center'> $10^5$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>9</td>
    <td rowspan="12" style='text-align:center'> $2\times 10^5$ </td>
    <td style='text-align:center'> $1$ </td>
    <td rowspan="2" style='text-align:center'> $0$ </td>
    <td style='text-align:center'>保证 $l=1,r=n$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>10</td>
    <td rowspan="11" style='text-align:center'> $5\times 10^5$ </td>
    <td style='text-align:center'>无</td>
  </tr>
  <tr>
    <td style='text-align:center'>11</td>
    <td rowspan="10" style='text-align:center'> $10^5$ </td>
    <td style='text-align:center'>保证 $u=v$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>12</td>
    <td style='text-align:center'>保证 $l=1,r=n$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>13</td>
    <td style='text-align:center'>保证 $u=1,v=n,a_i=0$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>14</td>
    <td style='text-align:center'>保证 $u=1,v=n$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>15</td>
    <td style='text-align:center'>保证 $d=1,a_i=0$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>16</td>
    <td style='text-align:center'>保证 $d=1$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>17</td>
    <td rowspan="2" style='text-align:center'>保证 $a_i=0$ </td>
  </tr>
  <tr>
    <td style='text-align:center'>18</td>
  </tr>
  <tr>
    <td style='text-align:center'>19</td>
    <td rowspan="2" style='text-align:center'>无</td>
  </tr>
  <tr>
    <td style='text-align:center'>20</td>
  </tr></tbody>
</table>
-->

<!-- END: Migrated markdown table -->

