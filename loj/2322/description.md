
# 题目描述

不远的一年前，小V还是一名清华集训的选手，坐在机房里为他已如风中残烛的OI生涯做最后的挣扎。而如今，他已成为了一名光荣的出题人。他感到非常激动，不禁感叹道：“Hello world!”。

小V有 $n$ 道题，他的题都非常毒瘤，所以关爱选手的 ufozgg 打算削弱这些题。为了逃避削弱，小V把他的毒瘤题都藏到了一棵 $n$ 个节点的树里（节点编号从 $1$ 至 $n$），这棵树上的所有节点与小V的所有题一一对应。小V的每一道题都有一个毒瘤值，节点 $i$ （表示标号为 $i$ 的树上节点，下同）对应的题的毒瘤值为 $a_i$ 。

魔法师小V为了保护他的题目，对这棵树施了魔法，这样一来，任何人想要一探这棵树的究竟，都必须在上面做跳跃操作。每一次跳跃操作包含一个起点 $s$ 、一个终点 $t$ 和一个步频 $k$ ，这表示跳跃者会从 $s$ 出发，在树上沿着简单路径多次跳跃到达 $t$ ，每次跳跃，如果从当前点到 $t$ 的最短路长度不超过 $k$ ，那么跳跃者就会直接跳到 $t$ ，否则跳跃者就会沿着最短路跳过恰好 $k$ 条边。

既然小V把题藏在了树里，ufozgg 就不能直接削弱题目了。他就必须在树上跳跃，边跳跃边削弱题目。ufozgg 每次跳跃经过一个节点（包括起点 $s$ ，当 $s=t$ 的时候也是如此），就会把该节点上的题目的毒瘤值开根并向下取整：即如果他经过了节点 $i$，他就会使 $a_i=\lfloor{\sqrt{a_i}}\rfloor$。这种操作我们称为`削弱操作`。

ufozgg 还会不时地希望知道他对题目的削弱程度。因此，他在一些跳跃操作中会放弃对题目的削弱，转而统计该次跳跃经过节点的题目毒瘤值总和。这种操作我们称为`统计操作`。

吃瓜群众绿绿对小V的毒瘤题和 ufozgg 的削弱计划常感兴趣。他现在想知道 ufozgg 每次做统计操作时得到的结果。你能帮帮他吗？



# 输入格式

输入的第一行一个正整数 $n$ ，表示树的节点数。

接下来一行 $n$ 个用空格隔开的正整数 $a_1,a_2,\dots,a_n$ ，依次描述每个节点上题目的毒瘤值。

接下来 $n-1$ 行，描述这棵树。每行 $2$ 个正整数 $u,v$ ，描述一条树上的边 $\left( u,v\right)$ 。（保证 $1\leq u,v\leq n$ ，保证这 $n-1$ 条边构成了一棵树）

接下来一行一个正整数 $Q$ ，表示 ufozgg 的操作总数。

接下来 $Q$ 行按 ufozgg 执行操作的先后顺序依次描述每个操作，每行 $4$ 个用空格隔开的整数 $op,s,t,k$ ，表示 ufozgg 此次跳跃的起点为 $s$ ，终点为 $t$ ，步频为 $k$ 。如果 $op=0$ ，表示这是一次`削弱操作`；如果 $op=1$ ，表示这是一次`统计操作`。

# 输出格式

对于每个`统计操作`，输出一行一个整数，表示此次`统计操作`统计到的所有题的毒瘤值总和。

# 样例

#### 样例输入 1
```plain
5
1 2 3 4 5
1 2
2 3
3 4
2 5
5
1 1 4 1
1 1 4 2
0 1 5 2
1 2 4 5
1 1 5 1
```

#### 样例输出 1
```plain
10
8
6
5
```

#### 样例 2
见附加文件

# 数据范围与提示

对于 $100\%$ 的数据，保证 $n\leq 50000$，$Q\leq 400000$，$1\leq a_i\leq {10}^{13}$，对于所有的操作保证 $0\leq op\leq 1$，$1\leq s,t,k\leq n$。

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n=$ | $Q=$ | 其他约束 | 测试点分值 |
|:-:|:-:|:-:|:-:|:-:|
| 1 | $2000$ | $5000$ |  | $12$ |
| 2 | $40000$ | $400000$ |  | $14$ |
| 3 | $45000$ | $400000$ |  | $14$ |
| 4 | $50000$ | $400000$ | 对于所有边都有 $u+1=v$ | $17$ |
| 5 | $50000$ | $400000$ | 保证所有初始毒瘤值 $a_i=1$ | $7$ |
| 6 | $50000$ | $400000$ | 保证对于所有询问 $k=1$ | $13$ |
| 7 | $50000$ | $400000$ |  | $23$ |

<!-- Migrated from original HTML table:
<table><thead>
<tr>
<th style='text-align:center'>测试点编号</th><th style='text-align:center'>$n=$ </th><th style='text-align:center'>$Q=$ </th><th style='text-align:center'>其他约束</th><th style='text-align:center'>测试点分值</th></tr>
</thead><tbody>
<tr>
<td style='text-align:center'>1</td><td style='text-align:center'>$2000$ </td><td style='text-align:center'>$5000$ </td><td style='text-align:center'></td><td style='text-align:center'> $12$ </td></tr>
<tr>
<td style='text-align:center'>2</td><td style='text-align:center'>$40000$ </td><td style='text-align:center'>$400000$ </td><td style='text-align:center'></td><td style='text-align:center'> $14$ </td></tr>
<tr>
<td style='text-align:center'>3</td><td style='text-align:center'>$45000$ </td><td style='text-align:center'>$400000$ </td><td style='text-align:center'></td><td style='text-align:center'> $14$ </td></tr>
<tr>
<td style='text-align:center'>4</td><td style='text-align:center'>$50000$ </td><td style='text-align:center'>$400000$ </td><td style='text-align:center'>对于所有边都有 $u+1=v$ </td><td style='text-align:center'> $17$ </td></tr>
<tr>
<td style='text-align:center'>5</td><td style='text-align:center'>$50000$ </td><td 

style='text-align:center'>$400000$ </td><td style='text-align:center'>保证所有初始毒瘤值 $a_i=1$ </td><td style='text-align:center'> $7$ </td></tr>
<tr>
<td style='text-align:center'>6</td><td style='text-align:center'>$50000$ </td><td 

style='text-align:center'>$400000$ </td><td style='text-align:center'>保证对于所有询问 

$k=1$ </td><td style='text-align:center'> $13$ </td></tr>
<tr>
<td style='text-align:center'>7</td><td style='text-align:center'>$50000$ </td><td 

style='text-align:center'>$400000$ </td><td style='text-align:center'></td><td 

style='text-align:center'> $23$ </td>
</tbody></table>
-->

<!-- END: Migrated markdown table -->


