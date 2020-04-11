
# 题目描述

一次小 G 和小 H 原本准备去聚餐，但由于太麻烦了于是题面简化如下：

一个转盘上有摆成一圈的 $n$ 个物品（编号 $1$ 至 $n$）其中第 $i$ 个物品会在 $T_i$ 时刻出现。

在 $0$ 时刻时,小 G 可以任选 $n$ 个物品中的一个，我们将其编号记为 $s_0$。并且如果 $i$ 时刻选择了物品 $s_i$，那么 $i + 1$ 时刻可以继续选择当前物品或者选择下一个物品。当 $s_i$ 为 $n$ 时，下一个物品为物品 $1$，否则下一个物品为 $s_{i} + 1$。在每一时刻（包括 $0$ 时刻），如果小 G 所选择的物品已经出现了，那么小 G 将会标记它。小 H 想知道，在物品选择的最优策略下，小 G 什么时候能标记所有物品？

但麻烦的是，物品的出现时间会不时修改。我们将其描述为 $m$ 次修改，每次修改将改变其中一个物品的出现时间。每次修改之后，你也需要求出当前局面的答案。对于其中部分测试点，小 H 还追加了强制在线的要求。

# 输入格式

第一行三个非负整数 $n,m,p$，代表一共有 $n$ 个物品，$m$ 次修改。$p$ 只有 $0$ 或 $1$ 两种取值，强制在线时 $p$ 为 $1$，否则为 $0$。本节后面将解释如何使用 $p$。

接下来一行，有 $n$ 个用空格隔开的非负整数，第 $i$ 个数 $T_i$ 代表物品 $i$ 的出现时间。

接下来 $m$ 行，每行两个非负整数 $x,y$，代表一次修改及询问。修改方式如下：
* 如果 $p = 0$，则表示物品 $x$ 的出现时间 $T_x$ 修改为 $y$。
* 如果 $p = 1$，则先将 $x$ 和 $y$ 分别异或 $LastAns$ 得到 $x′$ 和 $y′$：即 $x′ = x \oplus LastAns, y′ = y \oplus LastAns$。然后将物品 $x′$ 的出现时间 $T_{x′}$ 修改为 $y′$ 。其中的 $LastAns$ 是前一个询问的答案；特别的，第一次修改时的 $LastAns$ 为初始局面的答案。其中的 $\oplus$ 为按位异或运算，例如 $1 \oplus 2 = 3,4 \oplus 5 = 1,6 \oplus 11 = 13$。

保证输入合法。

# 输出格式

第一行一个整数代表初始局面的答案。

接下来 $m + 1$ 行每行一个整数分别代表每次修改后的答案。

# 样例

#### 样例输入
```plain
5 3 0
1 2 3 4 5
3 5
5 0
1 4
```
#### 样例输出
```plain
5
7
6
7
```

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n$ | $m$ | $T_i/T_x$ | $p$ |
|-|-|-|-|-|
| 1 | $\le 10$ | $\le 10$ | $\le 10$ | $=0$ |
| 2 | $\le 1000$ | $=0$ | $\le 1000$ | $=0$ |
| 3 | $\le 10^5$ | $=0$ | $\le 10^5$ | $=0$ |
| 4 | $\le 5000$ | $\le 5000$ | $\le 10^5$ | $=0$ |
| 5 | $\le 8\times 10^4$ | $\le 8\times 10^4$ | $\le 10^5$ | $=0$ |
| 6 | $\le 8\times 10^4$ | $\le 8\times 10^4$ | $\le 10^5$ | $=1$ |
| 7 | $\le 9\times 10^4$ | $\le 9\times 10^4$ | $\le 10^5$ | $=0$ |
| 8 | $\le 9\times 10^4$ | $\le 9\times 10^4$ | $\le 10^5$ | $=1$ |
| 9 | $\le 10^5$ | $\le 10^5$ | $\le 10^5$ | $=0$ |
| 10 | $\le 10^5$ | $\le 10^5$ | $\le 10^5$ | $=1$ |

<!-- Migrated from original HTML table:
<table class="ui celled table" style="text-align: center;!important; margin: auto;">
  <thead>
    <tr>
      <th> 测试点编号 </th>
      <th> $n$ </th>
      <th> $m$ </th>
      <th> $T_i/T_x$ </th>
      <th> $p$ </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> 1 </td>
      <td colspan="3"> $\le 10$ </td>
      <td rowspan="5"> $=0$ </td>
    </tr>
    <tr>
      <td> 2 </td>
      <td> $\le 1000$ </td>
      <td rowspan="2"> $=0$ </td>
      <td> $\le 1000$ </td>
    </tr>
    <tr>
      <td> 3 </td>
      <td> $\le 10^5$ </td>
      <td rowspan="8"> $\le 10^5$ </td>
    </tr>
    <tr>
      <td> 4 </td>
      <td colspan="2"> $\le 5000$ </td>
    </tr>
    <tr>
      <td> 5 </td>
      <td rowspan="2" colspan="2"> $\le 8\times 10^4$ </td>
    </tr>
    <tr>
      <td> 6 </td>
      <td> $=1$ </td>
    </tr>
    <tr>
      <td> 7 </td>
      <td rowspan="2" colspan="2"> $\le 9\times 10^4$ </td>
      <td> $=0$ </td>
    </tr>
    <tr>
      <td> 8 </td>
      <td> $=1$ </td>
    </tr>
    <tr>
      <td> 9 </td>
      <td rowspan="2" colspan="2"> $\le 10^5$ </td>
      <td> $=0$ </td>
    </tr>
    <tr>
      <td> 10 </td>
      <td> $=1$ </td>
    </tr>
  </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

