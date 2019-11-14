
# 题目描述

九条可怜手上有一个长度为 $n$ 的整数数列 $r_i$ ，她现在想要构造一个长度为 $n$ 的，满足如下条件的整数数列 $A$：

* $1\leq  A_i \leq r_i$。
* 对于任意 $3 \leq i \leq n$，令 $R$ 为 $A_1$ 至 $A_{i-2}$ 中大于等于 $A_{i-1}$ 的最小值，$L$ 为 $A_1$ 至 $A_{i-2}$ 中小于等于 $A_{i-1}$ 的最大值。$A_i$ 必须满足 $L \leq A_i \leq R$。如果不存在大于等于 $A_{i-1}$ 的，那 么 $R = +\infty$；如果不存在小于等于 $A_{i-1}$ 的，那么 $L = −\infty$。

现在可怜想要知道共有多少不同的数列满足这个条件。两个数列 $A$ 和 $B$ 是不同的当且仅当至少存在一个位置 $i$ 满足 $A_i \neq B_i$。

# 输入格式

第一行输入一个整数 $n$，第二行输入 $n$ 个整数 $r_i$。

# 输出格式

输出一个整数表示方案数，答案可能很大，对 $998244353$ 取模后输出。

# 样例

#### 样例输入
```plain
3
2 2 2
```

#### 样例输出
```plain
6
```

#### 样例解释
满足条件的序列有 $[1, 1, 1], [1, 2, 1], [1, 2, 2], [2, 1, 1], [2, 1, 2], [2, 2, 2]$ 。

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n$ | $r_i$ |
|:-:|:-:|:-:|
| $1$ | $\leq 7$ | $\leq 7$ |
| $2$ | $\leq 7$ | $\leq 7$ |
| $3$ | $\leq 50$ | $\leq 10$ |
| $4$ | $\leq 50$ | $\leq 10$ |
| $5$ | $\leq 50$ | $\leq 16$ |
| $6$ | $\leq 50$ | $\leq 16$ |
| $7$ | $\leq 50$ | $\leq 50$ |
| $8$ | $\leq 50$ | $\leq 50$ |
| $9$ | $\leq 50$ | $\leq 150$ |
| $10$ | $\leq 50$ | $\leq 150$ |

<!-- Migrated from original HTML table:
<table><thead>
	<tr>
		<th style='text-align:center'>测试点编号</th>
		<th style='text-align:center'> $n$ </th>
		<th style='text-align:center'> $r_i$ </th>
	</tr></thead><tbody>
	<tr>
		<td style='text-align:center'> $1$ </td>
		<td rowspan=2 style='text-align:center'> $\leq 7$ </td>
		<td rowspan=2 style='text-align:center'> $\leq 7$ </td>
	</tr>
	<tr>
		<td style='text-align:center'> $2$ </td>
	</tr>
	<tr>
		<td style='text-align:center'> $3$ </td>
		<td rowspan=8 style='text-align:center'> $\leq 50$ </td>
		<td rowspan=2 style='text-align:center'> $\leq 10$ </td>
	</tr>
	<tr>
		<td style='text-align:center'> $4$ </td>
	</tr>
	<tr>
		<td style='text-align:center'> $5$ </td>
		<td rowspan=2 style='text-align:center'> $\leq 16$ </td>
	</tr>
	<tr>
		<td style='text-align:center'> $6$ </td>
	</tr>
	<tr>
		<td style='text-align:center'> $7$ </td>
		<td rowspan=2 style='text-align:center'> $\leq 50$ </td>
	</tr>
	<tr>
		<td style='text-align:center'> $8$ </td>
	</tr>
	<tr>
		<td style='text-align:center'> $9$ </td>
		<td rowspan=2 style='text-align:center'> $\leq 150$ </td>
	</tr>
	<tr>
		<td style='text-align:center'> $10$ </td>
	</tr></tbody>
</table>
-->

<!-- END: Migrated markdown table -->

对于全部数据，保证 $n\ge 1,r_i\ge 1$。

