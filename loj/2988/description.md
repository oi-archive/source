
# 题目描述

小 P 来到了 NOIP 2044 的赛场上，他发现第二题的题目是这样的：给你一个长度为 $n$ 的字符串，该字符串由至多 $m$ 种不同的字符组成，其中第 $i$ 种字符出现次数不超过 $c_i$，问你这个字符串的后缀数组是什么。

聪明的小 P 想到了一个新的问题希望你来帮忙解答：在题目给定的限制下，能有多少种不同的答案。也就是所有由 $m$ 种字符组成，其中第 $i$ 种字符出现次数不超过 $c_i$，且长度为 $n$ 的字符串，共有多少种不同的后缀数组。

由于答案很大，你只用输出答案对 $10^9 + 7$ 取模后的数。

对于一个字符串 $s=s_1s_2\cdots s_n$，记 $suf(i)$ 表示 $i$ 这个位置到末尾的子串。后缀数组为一个 $1$ 到 $n$ 的排列 $p_1, p_2, \cdots , p_n$，满足 $suf(p_1)<suf(p_2)<\ldots <suf(p_n)$。对于两个字符串 $s$ 和 $t$，令 $i$ 为第一个使得 $s_i \neq t_i$ 的位置，那么我们称 $s_i$ 和 $t_i$ 中小的对应的字符串更小，如果 $i$ 不存在，那么长度小的字符串更小。

对于字符之间的大小关系，我们规定第 $1$ 个字符最小，第 $2$ 个字符次小，依次类推。

# 输入格式

输入文件为 `suffix.in`。

输入的第一行包含 $2$ 个正整数 $n, m$，表示字符串的长度为 $n$，共有 $m$ 种字符。

接下来一行， 包含 $m$ 个非负整数 $c_1, c_2, \ldots , c_m$，表示每种字符最多的出现次数。保证 $0 \le c_1, c_2, \ldots , c_m ≤ n$，$c_1 + c_2 + \ldots + c_m \ge n$。

# 输出格式

输出文件为 `suffix.out`。

输出共 $1$ 行，包含一个整数，表示答案。

# 样例

#### 样例输入 1
```plain
3 2
2 2
```

#### 样例输出 1
```plain
5
```

#### 样例说明 1
我们记 `a` 为第一种字符，`b` 为第二种字符，那么共有 `aab`，`aba`，`abb`，`baa`，`bab`，`bba` 这六种可能的字符串。

它们的后缀数组为 $(1,2,3)$，$(3,1,2)$，$(1,3,2)$，$(3,2,1)$，$(2,3,1)$，$(3,2,1)$。所以共有 $5$ 种不同的结果。

#### 样例输入 2
```plain
10 5
2 3 4 3 2
```
#### 样例输出 2
```plain
1003811
```
#### 样例 3
见附加文件。

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点 | $n$ | $m$ | 数据特点 |
|:-:|:-:|:-:|:-:|
| $1$ | $\le 6$ | $\le 6$ | 无 |
| $2,3$ | $\le 10$ | $\le 10$ | 无 |
| $4$ | $\le 500$ | $=2$ | 无 |
| $5$ | $\le 500$ | $=3$ | 无 |
| $6,7$ | $\le 500$ | $\le 500$ | $c_1=c_2=\ldots =c_m=n$ |
| $8\sim 10$ | $\le 50$ | $\le 50$ | 无 |
| $11\sim 14$ | $\le 200$ | $\le 200$ | 无 |
| $15\sim 20$ | $\le 500$ | $\le 500$ | 无 |

<!-- Migrated from original HTML table:
<table><thead>
  <tr>
    <th style='text-align: center'>测试点</th>
    <th style='text-align: center'> $n$ </th>
    <th style='text-align: center'> $m$ </th>
    <th style='text-align: center'>数据特点</th>
  </tr></thead><tbody>
  <tr>
    <td style='text-align: center'> $1$ </td>
    <td style='text-align: center'> $\le 6$ </td>
    <td style='text-align: center'> $\le 6$ </td>
    <td rowspan="4" style='text-align: center'>无</td>
  </tr>
  <tr>
    <td style='text-align: center'> $2,3$ </td>
    <td style='text-align: center'> $\le 10$ </td>
    <td style='text-align: center'> $\le 10$ </td>
  </tr>
  <tr>
    <td style='text-align: center'> $4$ </td>
    <td style='text-align: center'> $\le 500$ </td>
    <td style='text-align: center'> $=2$ </td>
  </tr>
  <tr>
    <td style='text-align: center'> $5$ </td>
    <td style='text-align: center'> $\le 500$ </td>
    <td style='text-align: center'> $=3$ </td>
  </tr>
  <tr>
    <td style='text-align: center'> $6,7$ </td>
    <td style='text-align: center'> $\le 500$ </td>
    <td style='text-align: center'> $\le 500$ </td>
    <td style='text-align: center'> $c_1=c_2=\ldots =c_m=n$ </td>
  </tr>
  <tr>
    <td style='text-align: center'> $8\sim 10$ </td>
    <td style='text-align: center'> $\le 50$ </td>
    <td style='text-align: center'> $\le 50$ </td>
    <td rowspan="3" style='text-align: center'>无</td>
  </tr>
  <tr>
    <td style='text-align: center'> $11\sim 14$ </td>
    <td style='text-align: center'> $\le 200$ </td>
    <td style='text-align: center'> $\le 200$ </td>
  </tr>
  <tr>
    <td style='text-align: center'> $15\sim 20$ </td>
    <td style='text-align: center'> $\le 500$ </td>
    <td style='text-align: center'> $\le 500$ </td>
  </tr></tbody>
</table>
-->

<!-- END: Migrated markdown table -->

