
# 题目描述

实力强大的小 A 被选为了 ION2018 的出题人，现在他需要解决题目的命名问题。

小 A 被选为了 ION2018 的出题人，他精心准备了一道质量十分高的题目，且已经把除了题目命名以外的工作都做好了。

由于 ION 已经举办了很多届，所以在题目命名上也是有规定的，ION 命题手册规定：每年由命题委员会规定一个小写字母字符串，我们称之为那一年的命名串，**要求每道题的名字必须是那一年的命名串的一个非空连续子串，且不能和前一年的任何一道题目的名字相同**。

由于一些特殊的原因，小 A 不知道 ION2017 每道题的名字，但是他通过一些特殊手段得到了 ION2017 的命名串，现在小 A 有 $Q$ 次询问：每次给定 ION2017 的命名串和 ION2018 的命名串，求有几种题目的命名，使得这个名字一定满足命题委员会的规定，即是 ION2018 的命名串的一个非空连续子串且一定不会和 ION2017 的任何一道题目的名字相同。

由于一些特殊原因，所有询问给出的 ION2017 的命名串都是某个串的连续子串，详细可见输入格式。

# 输入格式

从标准输入读入数据。

第一行一个字符串 $S$，之后询问给出的 ION2017 的命名串都是 $S$ 的连续子串。

第二行一个正整数 $Q$，表示询问次数。

接下来 $Q$ 行，每行有一个字符串 $T$ 和两个正整数 $l, r$，表示询问如果 ION2017 的命名串是 $S[l..r]$，ION2018 的命名串是 $T$ 的话，有几种命名方式一定满足规定。

保证输入中给出的字符串都是由小写字母构成的。

# 输出格式

输出到标准输出中。

输出 $Q$ 行，第 $i$ 行一个非负整数表示第 $i$ 个询问的答案。

# 样例

#### 样例输入 1

```plain
scbamgepe
3
smape 2 7
sbape 3 8
sgepe 1 9
```

#### 样例输出 1

```plain
12
10
4
```

#### 样例 2
见附加文件中的 `name2.in` 与 `name2.ans`.

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点 | $\lvert S \rvert \leq$ | $Q \leq$ | $\sum \lvert T \rvert \leq$ | 询问限制 | 其他限制 |
|:-:|:-:|:-:|:-:|:-:|:-:|
| 1 | $200$ | $200$ | $40000$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | $\lvert T \rvert \leq 200$ |
| 2 | $1000$ | $200$ | $40000$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | $\lvert T \rvert \leq 200$ |
| 3 | $1000$ | $200$ | $40000$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | $\lvert T \rvert \leq 200$ |
| 4 | $1000$ | $200$ | $5 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 无 |
| 5 | $1000$ | $200$ | $5 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 无 |
| 6 | $5 \times 10^5$ | $1$ | $5 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 无 |
| 7 | $5 \times 10^5$ | $1$ | $5 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 无 |
| 8 | $10^5$ | $10^5$ | $2 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 无 |
| 9 | $10^5$ | $10^5$ | $2 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 字符串随机 |
| 10 | $2 \times 10^5$ | $10^5$ | $4 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 无 |
| 11 | $2 \times 10^5$ | $10^5$ | $4 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 字符串随机 |
| 12 | $3 \times 10^5$ | $10^5$ | $6 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 无 |
| 13 | $3 \times 10^5$ | $10^5$ | $6 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 字符串随机 |
| 14 | $4 \times 10^5$ | $10^5$ | $8 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 无 |
| 15 | $4 \times 10^5$ | $10^5$ | $8 \times 10^5$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 字符串随机 |
| 16 | $5 \times 10^5$ | $10^5$ | $10^6$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 无 |
| 17 | $5 \times 10^5$ | $10^5$ | $10^6$ | 对于所有询问有 $l = 1, r = \lvert S \rvert$ | 字符串随机 |
| 18 | $2 \times 10^5$ | $10^5$ | $10^6$ | 无 | 无 |
| 19 | $3 \times 10^5$ | $10^5$ | $10^6$ | 无 | 无 |
| 20 | $4 \times 10^5$ | $10^5$ | $10^6$ | 无 | 无 |
| 21 | $5 \times 10^5$ | $10^5$ | $10^6$ | 无 | 无 |
| 22 | $5 \times 10^5$ | $10^5$ | $10^6$ | 无 | 无 |
| 23 | $5 \times 10^5$ | $10^5$ | $10^6$ | 无 | 无 |
| 24 | $5 \times 10^5$ | $10^5$ | $10^6$ | 无 | 无 |
| 25 | $5 \times 10^5$ | $10^5$ | $10^6$ | 无 | 无 |

<!-- Migrated from original HTML table:
<table><thead>
<tr>
<th style='text-align:center'>测试点</th><th style='text-align:center'>$\lvert S \rvert \leq$ </th><th style='text-align:center'>$Q \leq$ </th><th style='text-align:center'>$\sum \lvert T \rvert \leq$ </th><th style='text-align:center'>询问限制</th><th style='text-align:center'>其他限制</th></tr>
</thead><tbody>
<tr>
<td style='text-align:center'>1</td><td style='text-align:center'>$200$ </td><td style='text-align:center' rowspan='5'>$200$ </td><td style='text-align:center' rowspan='3'>$40000$ </td><td style='text-align:center' rowspan='17'>对于所有询问有 $l = 1, r = \lvert S \rvert$ </td><td style='text-align:center' rowspan='3'>$\lvert T \rvert \leq 200$ </td></tr>
<tr>
<td style='text-align:center'>2</td><td style='text-align:center' rowspan='4'>$1000$ </td></tr>
<tr>
<td style='text-align:center'>3</td></tr>
<tr>
<td style='text-align:center'>4</td><td style='text-align:center' rowspan='4'>$5 \times 10^5$ </td><td style='text-align:center' rowspan='5'>无</td></tr>
<tr>
<td style='text-align:center'>5</td></tr>
<tr>
<td style='text-align:center'>6</td><td style='text-align:center' rowspan='2'>$5 \times 10^5$ </td><td style='text-align:center' rowspan='2'>$1$ </td></tr>
<tr>
<td style='text-align:center'>7</td></tr>
<tr>
<td style='text-align:center'>8</td><td style='text-align:center' rowspan='2'>$10^5$ </td><td style='text-align:center' rowspan='18'>$10^5$ </td><td style='text-align:center' rowspan='2'>$2 \times 10^5$ </td></tr>
<tr>
<td style='text-align:center'>9</td><td style='text-align:center'>字符串随机</td></tr>
<tr>
<td style='text-align:center'>10</td><td style='text-align:center' rowspan='2'>$2 \times 10^5$ </td><td style='text-align:center' rowspan='2'>$4 \times 10^5$ </td><td style='text-align:center'>无</td></tr>
<tr>
<td style='text-align:center'>11</td><td style='text-align:center'>字符串随机</td></tr>
<tr>
<td style='text-align:center'>12</td><td style='text-align:center' rowspan='2'>$3 \times 10^5$ </td><td style='text-align:center' rowspan='2'>$6 \times 10^5$ </td><td style='text-align:center'>无</td></tr>
<tr>
<td style='text-align:center'>13</td><td style='text-align:center'>字符串随机</td></tr>
<tr>
<td style='text-align:center'>14</td><td style='text-align:center' rowspan='2'>$4 \times 10^5$ </td><td style='text-align:center' rowspan='2'>$8 \times 10^5$ </td><td style='text-align:center'>无</td></tr>
<tr>
<td style='text-align:center'>15</td><td style='text-align:center'>字符串随机</td></tr>
<tr>
<td style='text-align:center'>16</td><td style='text-align:center' rowspan='2'>$5 \times 10^5$ </td><td style='text-align:center' rowspan='10'>$10^6$ </td><td style='text-align:center'>无</td></tr>
<tr>
<td style='text-align:center'>17</td><td style='text-align:center'>字符串随机</td></tr>
<tr>
<td style='text-align:center'>18</td><td style='text-align:center'>$2 \times 10^5$ </td><td style='text-align:center' rowspan='8'>无</td><td style='text-align:center' rowspan='8'>无</td></tr>
<tr>
<td style='text-align:center'>19</td><td style='text-align:center'>$3 \times 10^5$ </td></tr>
<tr>
<td style='text-align:center'>20</td><td style='text-align:center'>$4 \times 10^5$ </td></tr>
<tr>
<td style='text-align:center'>21</td><td style='text-align:center' rowspan='5'>$5 \times 10^5$ </td></tr>
<tr>
<td style='text-align:center'>22</td></tr>
<tr>
<td style='text-align:center'>23</td></tr>
<tr>
<td style='text-align:center'>24</td></tr>
<tr>
<td style='text-align:center'>25</td></tr>
</tbody></table>
-->

<!-- END: Migrated markdown table -->

对于所有数据，保证 $1 \leq l \leq r \leq \lvert S \rvert$，$1 \leq \lvert T \rvert \leq 5 \times 10^5$

