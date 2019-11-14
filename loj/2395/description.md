
# 题目描述

**题目译自 [JOISC 2017](https://www.ioi-jp.org/camp/2017/2017-sp-tasks/index.html) Day2 T3「[鉄道旅行](https://www.ioi-jp.org/camp/2017/2017-sp-tasks/2017-sp-d2.pdf) / [Railway Trip](https://www.ioi-jp.org/camp/2017/2017-sp-tasks/2017-sp-d2-en.pdf)」**

某条铁路线（非环线）有 $N$ 站，依次编号为 $1\ldots N$。这条线路上跑着 $K$ 类列车，编号为 $1\ldots K$。每种列车都是双向运行的。  
这条铁路线上的每个车站都有个旅客流量，旅客流量是一个 $\le K$ 的正整数。车站 $i(1\le i\le N)$ 的旅客流量为 $L_i$，$L_1=L_N=K$。  
第 $j$ 类列车 $(1\le j\le N)$ 在且只在旅客流量 $\ge j$ 的车站停车。
现有 $Q$ 名旅客，依次编号为 $1\ldots Q$，旅客 $k(1\le k\le Q)$ 的起点是车站 $A_k$，终点是 $B_k$ $(1\le A_k, B_k\le N)$。假设这些旅客只能靠这条铁路线移动。  
对于每个旅客，求这名旅客的途中至少要**停几次站**（不含该旅客的起终点站）。保证同一名旅客的起点与终点不同。允许走回头路。  


# 输入格式

第一行有三个整数 $N, K, Q$，用空格分隔。  
在接下来的 $N$ 行中，第 $i$ 行 $(1\le i\le N)$ 有一个整数 $L_i$。  
在接下来的 $Q$ 行中，第 $k$ 行 $(1\le k\le N)$ 有两个整数 $A_k,B_k$。

# 输出格式

输出共 $Q$ 行，每行一个整数，表示旅客 $k$ 最少的停站次数。

# 样例

#### 样例输入 1
```plain
9 3 3
3
1
1
1
2
2
2
3
3
2 4
4 9
6 7
```

#### 样例输出 1
```plain
1
3
0
```

#### 样例解释 1
旅客 $1$ 从车站 $2$ 出发，可以直接坐 $1$ 类车抵达车站 $4$。中途站只有车站 $3$。  
旅客 $2$ 从车站 $4$ 出发，可以先坐 $1$ 类车到车站 $5$，再换乘 $2$ 类车坐到车站 $1$，再换乘 $3$ 类车坐到车站 $9$。中途站为车站 $5,1,8$。  
旅客 $3$ 从车站 $6$ 出发，直接坐 $1$ 类车抵达车站 $7$。

#### 样例输入 2
```plain
5 2 1
2
1
1
1
2
1 4
```

#### 样例输出 2
```plain
1
```

#### 样例解释 2
注意可以走过目的地，再走回来。

#### 样例输入 3
```plain
15 5 15
5
4
1
2
3
1
1
2
4
5
4
1
5
3
5
8 1
11 1
5 3
6 11
9 12
15 14
15 2
3 12
2 1
4 8
15 5
12 6
1 13
13 8
14 9
```

#### 样例输出 3
```plain
2
1
1
3
2
0
3
4
0
1
3
4
1
2
2
```

# 数据范围与提示

对于所有数据，$2\le N\le 10^5, 1\le K\le N, 1\le Q\le 10^5, 1\le L_i\le K(1\le i\le N), 1\le A_k, B_k\le N, A_k\not=B_k(1\le k\le Q)$。
<!-- BEGIN: Migrated markdown table -->

| Subtask # | 分值 | $N$ | $K$ | $Q$ |
|-|-|-|-|-|
| 1 | 5 | $N\le 100$ | $K\le 100$ | $Q\le 50$ |
| 2 | 15 |  |  | $Q\le 50$ |
| 3 | 25 |  | $K\le 20$ |  |
| 4 | 55 |  |  |  |

<!-- Migrated from original HTML table:
<table class="ui celled table">
<thead>
<tr>
<th>Subtask #</th>
<th>分值</th>
<th> $N$ </th>
<th> $K$ </th>
<th> $Q$ </th>
</tr>
</thead>
<tbody>
<tr>
<td>1</td>
<td>5</td>
<td> $N\le 100$ </td>
<td> $K\le 100$ </td>
<td> $Q\le 50$ </td>
</tr>
<tr>
<td>2</td>
<td>15</td>
<td></td>
<td></td>
<td> $Q\le 50$ </td>
</tr>
<tr>
<td>3</td>
<td>25</td>
<td></td>
<td> $K\le 20$ </td>
<td></td>
</tr>
<tr>
<td>4</td>
<td>55</td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>
-->

<!-- END: Migrated markdown table -->
表格中留空的均无特殊限制。

