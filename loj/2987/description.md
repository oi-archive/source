
# 题目描述

2045 年，人类的技术突飞猛进，已经找到了进行时空旅行的方法。小 R 得到了一台时空旅行仪，他想用它调查不同时空中人类的发展状况。

根据平行时空理论，宇宙中存在着很多独立的时空， 每个时空在下一个时间点还会分化出若干个不同的时空。宇宙是一个三维空间，人类使用空间直角坐标系来描述空间中的一个位置，三维坐标分别是 $x,y,z$。

我们假设在初始的时空（编号为 $0$）中，人类存在于地球上（地球的坐标为 $(0,0,0)$），其它的时空都是从一个现有的时空发展而来。一个时空发生一个事件
之后会发展成为另外一个时空（原来的时空不发生任何变化）。 会影响小 R 的事件包括两类：
- 人类殖民了一个新的星球，该星球的状态变成「已被殖民」；
- 人类放弃了一个已被殖民的星球，该星球的状态变成「未被殖民」。

每次进行时空旅行时，小 R 会先选定一个时空。在这个时空中，人类已经殖民了一些星球。 小 R 只要到达该时空中任意一个已被殖民的星球， 就能调查人类的发展状况。

小 R 的时空旅行仪出现了一些问题，调整 $x$ 坐标的按钮坏掉了，因此到达点的 $x$ 坐标被固定了（每次旅行的 $x$ 坐标值可能不同）。与此同时， 他仍能任意调整到达点的 $y$ 坐标和 $z$ 坐标。

这个问题大大增大了小 R 的花费： 因为时空旅行没有花费，但在太空中航行却需要花钱；同时，在不同的星球进行调查也可能会产生不同的费用。

假设小 R 将时空旅行的终点设为 $A$，他要进行调查的星球为 $B$：如果 $A$ 与 $B$ 的欧几里德距离为 $d$，那么他太空航行的花费就为 $d^2$；又如果星球 $B$ 上进行调查的费用为 $c$，那么小 R 此次调查的总花费就为 $d^2+c$。

现在给定小 R 每次旅行到达的时空以及时空旅行仪上固定的 $x$ 坐标值，请你计算出小 R 每次旅行完成调查的最小总花费。

# 输入格式

输入文件为 `travel.in`。

输入的第一行包含三个非负整数 $n,m,c_0$，$n$ 表示平行时空数量，这些平行时空的编号为 0 到 $n − 1$ 的整数，初始时空的编号为 0。$m$ 表示小 R 进行的时空旅行的次数，$c_0$ 表示在地球进行调查的花费。保证 $n,m$ 是正整数，$0 \le c_0 \le 10^{12}$。

接下来 $n − 1$ 行，依次描述平行时空 $1$ 到 $n − 1$，其中第 $i$ 行分两种情况：
- `0 fr id x y z c`：表示编号为 $i$ 的平行时空由编号为 $\text{fr}$ 的时空发展而来，数据保证人类殖民了一个编号为 $\text{id}$ 的星球，该星球的坐标为 $(x, y, z)$，在该星球进行调查的花费为 $c$。数据保证给出的星球编号不重复，且 $0 < \text{id} < n$；保证 $|x|, |y|, |z| \le 10^6,0 \le c \le 10^{12}$。
- `1 fr id`：表示编号为 $i$ 的平行时空由编号为 $\text{fr}$ 的时空发展而来，人类放弃了编号为 $\text{id}$ 的星球。数据保证该星球在编号为 $\text{fr}$ 的时空中处于被殖民的状态；保证 $\text{id} > 0$，即地球一定不会被放弃。

上述两种情况中，各参数均为整数，相邻整数之间均用一个空格隔开； 均保证 $0 \le \text{fr} < i$。保证不会出现上述两种之外的情况。

接下来 $m$ 行，每行表示小 R 进行的一次时空旅行。每行包括 $2$ 个整数 $s$ 和 $x_0$，表示小 R 到编号为 $s$ 的平行时空进行了一次时空旅行，时空旅行仪上 $x$ 坐标被固定为了 $x_0$。保证 $0 \le s < n,|x_0| \le 10^6$。

# 输出格式

输出文件为 `travel.out`。

输出 $m$ 行，分别表示每次旅行完成调查的最小总花费

# 样例

#### 样例输入 1
```plain
4 4 2
0 0 1 8 2 3 7
0 1 2 10 1 6 2
1 1 1
1 4
2 8
2 6
3 8
```
#### 样例输出 1
```plain
18
6
11
66
```
#### 样例 2
见附加文件。

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点 | $n$ | $m$ | 数据特点 |
|:-:|:-:|:-:|:-:|
| $1$ | $\le 100$ | $\le 100$ | 无 |
| $2\sim 4$ | $\le 10^5$ | $\le 10^5$ | 人类不会放弃星球 |
| $5\sim 6$ | $\le 10^5$ | $\le 10^5$ | 每次旅行的 $x$ 值是相同的 |
| $7\sim 8$ | $\le 10^5$ | $\le 10^5$ | 无 |
| $9\sim 10$ | $\le 5\times 10^5$ | $\le 5\times 10^5$ | 每次旅行的 $x$ 值是相同的 |
| $11\sim 13$ | $\le 5\times 10^5$ | $\le 5\times 10^5$ | 编号为 $i$ 的时空由编号为 $i-1$ 的时空发展而来且人类不会放弃星球 |
| $14\sim 17$ | $\le 5\times 10^5$ | $\le 5\times 10^5$ | 编号为 $i$ 的时空由编号为 $i-1$ 的时空发展而来 |
| $18\sim 20$ | $\le 5\times 10^5$ | $\le 5\times 10^5$ | 无 |

<!-- Migrated from original HTML table:
<table><thead>
  <tr>
    <th style='text-align: center'>测试点</th>
    <th style='text-align: center'> $n$ </th>
    <th style='text-align: center'> $m$ </th>
    <th style='text-align: center'>数据特点</th>
  </tr>
</thead><tbody>
  <tr>
    <td style='text-align: center'> $1$ </td>
    <td style='text-align: center'> $\le 100$ </td>
    <td style='text-align: center'> $\le 100$ </td>
    <td style='text-align: center'>无</td>
  </tr>
  <tr>
    <td style='text-align: center'> $2\sim 4$ </td>
    <td rowspan="3" style='text-align: center'> $\le 10^5$ </td>
    <td rowspan="3" style='text-align: center'> $\le 10^5$ </td>
    <td style='text-align: center'>人类不会放弃星球</td>
  </tr>
  <tr>
    <td style='text-align: center'> $5\sim 6$ </td>
    <td style='text-align: center'>每次旅行的 $x$ 值是相同的</td>
  </tr>
  <tr>
    <td style='text-align: center'> $7\sim 8$ </td>
    <td style='text-align: center'>无</td>
  </tr>
  <tr>
    <td style='text-align: center'> $9\sim 10$ </td>
    <td rowspan="4" style='text-align: center'> $\le 5\times 10^5$ </td>
    <td rowspan="4" style='text-align: center'> $\le 5\times 10^5$ </td>
    <td style='text-align: center'>每次旅行的 $x$ 值是相同的</td>
  </tr>
  <tr>
    <td style='text-align: center'> $11\sim 13$ </td>
    <td style='text-align: center'>编号为 $i$ 的时空由编号为 $i-1$ 的时空发展而来且人类不会放弃星球</td>
  </tr>
  <tr>
    <td style='text-align: center'> $14\sim 17$ </td>
    <td style='text-align: center'>编号为 $i$ 的时空由编号为 $i-1$ 的时空发展而来</td>
  </tr>
  <tr>
    <td style='text-align: center'> $18\sim 20$ </td>
    <td style='text-align: center'>无</td>
  </tr></tbody>
</table>
-->

<!-- END: Migrated markdown table -->

