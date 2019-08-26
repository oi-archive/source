
# 题目描述

给定一个 $n$ 个点 $m$ 条边的有向弱连通图， 每个点均匀点权 $d_i$ 和修改耗时 $w_i$， 每次修改可以花费 $w_i$ 的时间把 $d_i$ 加 $1$ 或者减 $1$，求最少消耗多少时间，使得 $\forall (u,v)\in E, d_u\le d_v$。

# 输入格式

输入共包括 $m+3$ 行  
第一行包含两个整数 $n,m$，表示点数和边数。  
第二行包含 $n$ 个整数，第 $i$ 个整数表示第 $i$ 个点的点权 $d_i$。  
第三行包含 $n$ 个整数，第 $i$ 个整数表示第 $i$ 个点的修改耗时 $w_i$。  
第 $4 ~ m+3$ 行，每行包含两个整数 $u_i,v_i$，表示有向图种的一条由 $u_i$ 到 $v_i$ 的有向边。

# 输出格式

输出包含一个整数，表示最小总耗时。

# 样例

#### 样例输入1
```plain
3 3
5 9 8
1 2 3
1 2
2 3
3 1
```
#### 样例输出 1
```plain
5
```
#### 样例解释 1   
限制为 $d_1\le d_2,d_2\le d_3,d_3\le d_1$，即要求 $d_1 = d_2 = d_3$，故将 $d_1$ 加 $3$ 至 $8$，$d_2$ 减 $1$ 至 $8$ 最优，最小耗时为 $1 \times |5-8| + 2\times |9-8| + 3 \times |8-8| = 5$。

#### 样例输入2
```plain
3 2
5 9 8
1 2 3
1 2
2 3
```
#### 样例输出 2
```plain
2
```



# 数据范围与提示

 <!-- BEGIN: Migrated markdown table -->

| 子任务 | 分值 | $n \leq $ | $m=$ | 特殊限制 |
|-|-|-|-|-|
| $1$ | $10$ | $5000$ | $n-1$ | 无 |
| $2$ | $20$ | $100000$ | $n-1$ | 将所有有向边看成无向边时，整张图构成一条链 |
| $3$ | $20$ | $100000$ | $n-1$ | 无 |
| $4$ | $15$ | $300000$ | $n-1$ | 无 |
| $5$ | $10$ | $300000$ | $n$ | 存在数列$f_i$,满足有且仅有$i$向$f_i$的有向边，$w_i=1$ |
| $6$ | $10$ | $300000$ | $n$ | 将所有有向边看成无向边时，整张图构成一个环 |
| $7$ | $15$ | $300000$ | $n-1,n$ | 无 |

<!-- Migrated from original HTML table:
<table>
  <thead>
   <tr><th>子任务</th><th>分值</th><th> $n \leq $ </th><th> $m=$ </th><th>特殊限制</th></tr>
  </thead>
  <tbody>
   <tr><td rowspan="1"> $1$ </td><td rowspan="1"> $10$ </td><td rowspan="1"> $5000$ </td><td rowspan="4"> $n-1$ </td><td rowspan="1">无</td></tr>
   <tr><td rowspan="1"> $2$ </td><td rowspan="1"> $20$ </td><td rowspan="2"> $100000$ </td><td rowspan="1">将所有有向边看成无向边时，整张图构成一条链</td></tr>
   <tr><td rowspan="1"> $3$ </td><td rowspan="1"> $20$ </td><td rowspan="2">无</td></tr>
   <tr><td rowspan="1"> $4$ </td><td rowspan="1"> $15$ </td><td rowspan="1"> $300000$ </td></tr>
   <tr><td rowspan="1"> $5$ </td><td rowspan="1"> $10$ </td><td rowspan="3"> $300000$ </td><td rowspan="2"> $n$ </td><td rowspan="1">存在数列$f_i$,满足有且仅有$i$向$f_i$的有向边，$w_i=1$ </td></tr>
   <tr><td rowspan="1"> $6$ </td><td rowspan="1"> $10$ </td><td rowspan="1">将所有有向边看成无向边时，整张图构成一个环</td></tr>
   <tr><td rowspan="1"> $7$ </td><td rowspan="1"> $15$ </td><td rowspan="1"> $n-1,n$ </td><td rowspan="1">无</td></tr>
  </tbody>
 </table>
-->

<!-- END: Migrated markdown table -->


