
# 题目描述

一年一度的「幻影阁夏日品酒大会」隆重开幕了。大会包含品尝和趣味挑战两个环节，分别向优胜者颁发「首席品酒家」和「首席猎手」两个奖项，吸引了众多品酒师参加。

在大会的晚餐上，调酒师 Rainbow 调制了 $n$ 杯鸡尾酒。这 $n$ 杯鸡尾酒排成一行，其中第 $i$ 杯酒 （$1 \leq i \leq n$） 被贴上了一个标签 $s_i$，每个标签都是 $26$ 个小写英文字母之一。设 $\mathrm{Str}(l, r)$ 表示第 $l$ 杯酒到第 $r$ 杯酒的 $r − l + 1$ 个标签顺次连接构成的字符串。若 $\mathrm{Str}(p, p_0) = \mathrm{Str}(q, q_0)$，其中 $1 \leq p \leq p_0 \leq n$，$1 \leq q \leq q_0 \leq n$，$p \neq q$，$p_0 − p + 1 = q_0 − q + 1 = r$，则称第 $p$ 杯酒与第 $q$ 杯酒是「$r$ 相似」的。当然两杯「$r$ 相似」（$r > 1$）的酒同时也是「$1$ 相似」、「$2$ 相似」、$\dots$、「$(r − 1)$ 相似」的。特别地，对于任意的 $1 \leq p, q \leq n$，$p \neq q$，第 $p$ 杯酒和第 $q$ 杯酒都是「$0$ 相似」的。

在品尝环节上，品酒师 Freda 轻松地评定了每一杯酒的美味度，凭借其专业的水准和经验成功夺取了「首席品酒家」的称号，其中第 $i$ 杯酒 （$1 \leq i \leq n$） 的美味度为 $a_i$。现在 Rainbow 公布了挑战环节的问题：本次大会调制的鸡尾酒有一个特点，如果把第 $p$ 杯酒与第 $q$ 杯酒调兑在一起，将得到一杯美味度为 $a_p \cdot a_q$ 的酒。现在请各位品酒师分别对于 $r = 0, 1, 2, \dots, n − 1$，统计出有多少种方法可以选出两杯「$r$ 相似」的酒，并回答选择两杯「$r$ 相似」的酒调兑可以得到的美味度的最大值。

# 输入格式

输入文件的第一行包含一个正整数 $n$，表示鸡尾酒的杯数。  
第二行包含一个长度为 $n$ 的字符串 $S$，其中第 $i$ 个字符表示第 $i$ 杯酒的标签。  
第三行包含 $n$ 个整数，相邻整数之间用单个空格隔开，其中第 $i$ 个整数表示第 $i$ 杯酒的美味度 $a_i$。

# 输出格式

输出文件包括 $n$ 行。第 $i$ 行输出两个整数，中间用单个空格隔开。第一个整数表示选出两杯「$(i − 1)$ 相似」的酒的方案数，第二个整数表示选出两杯「$(i − 1)$ 相似」的酒调兑可以得到的最大美味度。若不存在两杯「$(i − 1)$ 相似」的酒，这两个数均为 $0$。

# 样例

#### 样例输入 1
```plain
10
ponoiiipoi
2 1 4 7 4 8 3 6 4 7
```

#### 样例输出 1
```plain
45 56
10 56
3 32
0 0
0 0
0 0
0 0
0 0
0 0
0 0
```

#### 样例解释 1
用二元组 $(p, q)$ 表示第 $p$ 杯酒与第 $q$ 杯酒。
* $0$ 相似：所有 $45$ 对二元组都是 $0$ 相似的，美味度最大的是 $8 \times 7 = 56$。
* $1$ 相似：$(1,8)$ $(2,4)$ $(2,9)$ $(4,9)$ $(5,6)$ $(5,7)$ $(5,10)$ $(6,7)$ $(6,10)$ $(7,10)$，美味度最大的是 $8 \times 7 = 56$。
* $2$ 相似：$(1,8)$ $(4,9)$ $(5,6)$，美味度最大的是 $4 \times 8 = 32$。
* 没有 $3, 4, 5, \dots, 9$ 相似的两杯酒，故均输出 $0$。

#### 样例输入 2
```plain
12
abaabaabaaba
1 -2 3 -4 5 -6 7 -8 9 -10 11 -12
```

#### 样例输出 2
```plain
66 120
34 120
15 55
12 40
9 27
7 16
5 7
3 -4
2 -4
1 -4
0 0
0 0
```

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| Case # | $n$ 的规模 | $a_i$ 的规模 | 备注 |
|:-:|:-:|:-:|:-:|
| 1 | $n = 100$ | $\lvert a_i \rvert \leq 10000$ | - |
| 2 | $n = 200$ | $\lvert a_i \rvert \leq 10000$ | - |
| 3 | $n = 500$ | $\lvert a_i \rvert \leq 10000$ | - |
| 4 | $n = 750$ | $\lvert a_i \rvert \leq 10000$ | - |
| 5 | $n = 1000$ | $\lvert a_i \rvert \leq 1000000000$ | - |
| 6 | $n = 1000$ | $\lvert a_i \rvert \leq 1000000000$ | - |
| 7 | $n = 2000$ | $\lvert a_i \rvert \leq 1000000000$ | - |
| 8 | $n = 2000$ | $\lvert a_i \rvert \leq 1000000000$ | - |
| 9 | $n = 99991$ | $\lvert a_i \rvert \leq 1000000000$ | 不存在「$10$ 相似」的酒 |
| 10 | $n = 99991$ | $\lvert a_i \rvert \leq 1000000000$ | 不存在「$10$ 相似」的酒 |
| 11 | $n = 100000$ | $\lvert a_i \rvert \leq 1000000$ | 所有 $a_i$ 的值都相等 |
| 12 | $n = 200000$ | $\lvert a_i \rvert \leq 1000000$ | 所有 $a_i$ 的值都相等 |
| 13 | $n = 300000$ | $\lvert a_i \rvert \leq 1000000$ | 所有 $a_i$ 的值都相等 |
| 14 | $n = 300000$ | $\lvert a_i \rvert \leq 1000000$ | 所有 $a_i$ 的值都相等 |
| 15 | $n = 100000$ | $\lvert a_i \rvert \leq 1000000000$ | - |
| 16 | $n = 100000$ | $\lvert a_i \rvert \leq 1000000000$ | - |
| 17 | $n = 200000$ | $\lvert a_i \rvert \leq 1000000000$ | - |
| 18 | $n = 200000$ | $\lvert a_i \rvert \leq 1000000000$ | - |
| 19 | $n = 300000$ | $\lvert a_i \rvert \leq 1000000000$ | - |
| 20 | $n = 300000$ | $\lvert a_i \rvert \leq 1000000000$ | - |

<!-- Migrated from original HTML table:
<table class='ui table'>
    <thead style='text-align: center'>
        <tr>
            <th style='text-align: center'>Case #</th>
            <th style='text-align: center'> $n$ 的规模</th>
            <th style='text-align: center'> $a_i$ 的规模</th>
            <th style='text-align: center'>备注</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style='text-align: center'>1</td>
            <td style='text-align: center'> $n = 100$ </td>
            <td style='text-align: center' rowspan='4'> $\lvert a_i \rvert \leq 10000$ </td>
            <td style='text-align: center' rowspan='8'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>2</td>
            <td style='text-align: center'> $n = 200$ </td>
        </tr>
        <tr>
            <td style='text-align: center'>3</td>
            <td style='text-align: center'> $n = 500$ </td>
        </tr>
        <tr>
            <td style='text-align: center'>4</td>
            <td style='text-align: center'> $n = 750$ </td>
        </tr>
        <tr>
            <td style='text-align: center'>5</td>
            <td style='text-align: center' rowspan='2'> $n = 1000$ </td>
            <td style='text-align: center' rowspan='4'> $\lvert a_i \rvert \leq 1000000000$ </td>
        </tr>
        <tr>
            <td style='text-align: center'>6</td>
        </tr>
        <tr>
            <td style='text-align: center'>7</td>
            <td style='text-align: center' rowspan='2'> $n = 2000$ </td>
        </tr>
        <tr>
            <td style='text-align: center'>8</td>
        </tr>
        <tr>
            <td style='text-align: center'>9</td>
            <td style='text-align: center' rowspan='2'> $n = 99991$ </td>
            <td style='text-align: center' rowspan='2'> $\lvert a_i \rvert \leq 1000000000$ </td>
            <td style='text-align: center' rowspan='2'>不存在「$10$ 相似」的酒</td>
        </tr>
        <tr>
            <td style='text-align: center'>10</td>
        </tr>
        <tr>
            <td style='text-align: center'>11</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center' rowspan='4'> $\lvert a_i \rvert \leq 1000000$ </td>
            <td style='text-align: center' rowspan='4'>所有 $a_i$ 的值都相等</td>
        </tr>
        <tr>
            <td style='text-align: center'>12</td>
            <td style='text-align: center'> $n = 200000$ </td>
        </tr>
        <tr>
            <td style='text-align: center'>13</td>
            <td style='text-align: center' rowspan='2'> $n = 300000$ </td>
        </tr>
        <tr>
            <td style='text-align: center'>14</td>
        </tr>
        <tr>
            <td style='text-align: center'>15</td>
            <td style='text-align: center' rowspan='2'> $n = 100000$ </td>
            <td style='text-align: center' rowspan='6'> $\lvert a_i \rvert \leq 1000000000$ </td>
            <td style='text-align: center' rowspan='6'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>16</td>
        </tr>
        <tr>
            <td style='text-align: center'>17</td>
            <td style='text-align: center' rowspan='2'> $n = 200000$ </td>
        </tr>
        <tr>
            <td style='text-align: center'>18</td>
        </tr>
        <tr>
            <td style='text-align: center'>19</td>
            <td style='text-align: center' rowspan='2'> $n = 300000$ </td>
        </tr>
        <tr>
            <td style='text-align: center'>20</td>
        </tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->


