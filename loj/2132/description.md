
# 题目描述

> 追逐影子的人，自己就是影子。 ——荷马

Allison 最近迷上了文学。她喜欢在一个慵懒的午后，细细地品上一杯卡布奇诺，静静地阅读她爱不释手的《荷马史诗》。但是由《奥德赛》和《伊利亚特》组成的鸿篇巨制《荷马史诗》实在是太长了，Allison 想通过一种编码方式使得它变得短一些。

一部《荷马史诗》中有 $n$ 种不同的单词，从 $1$ 到 $n$ 进行编号。其中第 $i$ 种单词出现的总次数为 $w_i$。Allison 想要用 $k$ 进制串 $s_i$ 来替换第 $i$ 种单词，使得其满足如下要求：
对于任意的 $1 \leq i,j \leq n, \ i \neq j$，都有：$s_i$ 不是 $s_j$ 的前缀。

现在 Allison 想要知道，如何选择 $s_i$，才能使替换以后得到的新的《荷马史诗》长度最小。在确保总长度最小的情况下，Allison 还想知道最长的 $s_i$ 的最短长度是多少？

一些定义：

一个字符串被称为 $k$ 进制字符串，当且仅当它的每个字符是 $0$ 到 $k−1$ 之间（包括 $0$ 和 $k−1$）的整数。

字符串 $\text{Str}_1$ 被称为字符串 $\text{Str}_2$ 的前缀，当且仅当：存在 $1 \leq t \leq m$，使得 $\text{Str}_1=\text{Str}_2[1 \ldots t]$。其中，$m$ 是字符串 $\text{Str}_2$ 的长度，$\text{Str}_2[1 \ldots t]$ 表示 $\text{Str}_2$ 的前 $t$ 个字符组成的字符串。

# 输入格式

输入文件的第一行包含两个正整数 $n,k$，中间用单个空格隔开，表示共有 $n$ 种单词，需要使用 $k$ 进制字符串进行替换。

接下来 $n$ 行，第 $i+1$ 行包含 $1$ 个非负整数 $w_i$，表示第 $i$ 种单词的出现次数。

# 输出格式

输出文件包括两行。

第一行输出一个整数，为《荷马史诗》经过重新编码以后的最短长度。

第二行输出一个整数，为保证最短总长度的情况下，最长字符串 $s_i$ 的最短长度。

# 样例

#### 样例输入 1
```plain
4 2
1
1
2
2
```

#### 样例输出 1
```plain
12
2
```

#### 样例解释 1
用 $X_{(k)}$ 表示 $X$ 是以 $k$ 进制表示的字符串。

一种最优方案：令 $00_{(2)}$ 替换第一种单词，$01_{(2)}$ 替换第二种单词，$10_{(2)}$ 替换第三种单词，$11_{(2)}$ 替换第四种单词。在这种方案下，编码以后的最短长度为：$1 \times 2+1 \times 2+2 \times 2+2 \times 2=12$，最长字符串 $s_i$ 的长度为 $2$。

一种非最优方案：令 $000_{(2)}$ 替换第一种单词，$001_{(2)}$ 替换第二种单词，$01_{(2)}$ 替换第三种单词，$1_{(2)}$ 替换第四种单词。在这种方案下，编码以后的最短长度为：$1 \times 3+1 \times 3+2 \times 2+2 \times 1=12$，最长字符串 $s_i$ 的长度为 $3$。与最优方案相比，文章的长度相同，但是最长字符串的长度更长一些。

#### 样例输入 2
```plain
6 3
1
1
3
3
9
9
```

#### 样例输出 2
```plain
36
3
```

#### 样例解释 2
一种最优方案：令 $000_{(3)}$ 替换第 $1$ 种单词，$001_{(3)}$ 替换第 $2$ 种单词，$01_{(3)}$ 替换第 $3$ 种单词，$02_{(3)}$ 替换第 $4$ 种单词，$1_{(3)}$ 替换第 $5$ 种单词，$2_{(3)}$ 替换第 $6$ 种单词。

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->
#### 限制与约定

| Case # | $n$ 的规模 | $k$ 的规模 | 附加限制 |
|:-:|:-:|:-:|:-:|
| 1 | $n = 3$ | $k = 2$ | - |
| 2 | $n = 5$ | $k = 2$ | - |
| 3 | $n = 16$ | $k = 2$ | 所有 $w_i$ 均相等 |
| 4 | $n = 1000$ | $k = 2$ | $w_i$ 在取值范围内均匀随机 |
| 5 | $n = 1000$ | $k = 2$ | - |
| 6 | $n = 100000$ | $k = 2$ | - |
| 7 | $n = 100000$ | $k = 2$ | 所有 $w_i$ 均相等 |
| 8 | $n = 100000$ | $k = 2$ | - |
| 9 | $n = 7$ | $k = 3$ | - |
| 10 | $n = 16$ | $k = 3$ | 所有 $w_i$ 均相等 |
| 11 | $n = 1001$ | $k = 3$ | 所有 $w_i$ 均相等 |
| 12 | $n = 99999$ | $k = 4$ | 所有 $w_i$ 均相等 |
| 13 | $n = 100000$ | $k = 4$ | - |
| 14 | $n = 100000$ | $k = 4$ | - |
| 15 | $n = 1000$ | $k = 5$ | - |
| 16 | $n = 100000$ | $k = 7$ | $w_i$ 在取值范围内均匀随机 |
| 17 | $n = 100000$ | $k = 7$ | - |
| 18 | $n = 100000$ | $k = 8$ | $w_i$ 在取值范围内均匀随机 |
| 19 | $n = 100000$ | $k = 9$ | - |
| 20 | $n = 100000$ | $k = 9$ | - |

<!-- Migrated from original HTML table:
<table class="ui table">
    <thead>
        <tr>
            <th style='text-align: center'>Case #</th>
            <th style='text-align: center'> $n$ 的规模</th>
            <th style='text-align: center'> $k$ 的规模</th>
            <th style='text-align: center'>附加限制</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style='text-align: center'>1</td>
            <td style='text-align: center'> $n = 3$ </td>
            <td style='text-align: center'> $k = 2$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>2</td>
            <td style='text-align: center'> $n = 5$ </td>
            <td style='text-align: center'> $k = 2$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>3</td>
            <td style='text-align: center'> $n = 16$ </td>
            <td style='text-align: center'> $k = 2$ </td>
            <td style='text-align: center'>所有 $w_i$ 均相等</td>
        </tr>
        <tr>
            <td style='text-align: center'>4</td>
            <td style='text-align: center'> $n = 1000$ </td>
            <td style='text-align: center'> $k = 2$ </td>
            <td style='text-align: center'> $w_i$ 在取值范围内均匀随机</td>
        </tr>
        <tr>
            <td style='text-align: center'>5</td>
            <td style='text-align: center'> $n = 1000$ </td>
            <td style='text-align: center'> $k = 2$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>6</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 2$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>7</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 2$ </td>
            <td style='text-align: center'>所有 $w_i$ 均相等</td>
        </tr>
        <tr>
            <td style='text-align: center'>8</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 2$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>9</td>
            <td style='text-align: center'> $n = 7$ </td>
            <td style='text-align: center'> $k = 3$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>10</td>
            <td style='text-align: center'> $n = 16$ </td>
            <td style='text-align: center'> $k = 3$ </td>
            <td style='text-align: center'>所有 $w_i$ 均相等</td>
        </tr>
        <tr>
            <td style='text-align: center'>11</td>
            <td style='text-align: center'> $n = 1001$ </td>
            <td style='text-align: center'> $k = 3$ </td>
            <td style='text-align: center'>所有 $w_i$ 均相等</td>
        </tr>
        <tr>
            <td style='text-align: center'>12</td>
            <td style='text-align: center'> $n = 99999$ </td>
            <td style='text-align: center'> $k = 4$ </td>
            <td style='text-align: center'>所有 $w_i$ 均相等</td>
        </tr>
        <tr>
            <td style='text-align: center'>13</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 4$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>14</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 4$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>15</td>
            <td style='text-align: center'> $n = 1000$ </td>
            <td style='text-align: center'> $k = 5$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>16</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 7$ </td>
            <td style='text-align: center'> $w_i$ 在取值范围内均匀随机</td>
        </tr>
        <tr>
            <td style='text-align: center'>17</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 7$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>18</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 8$ </td>
            <td style='text-align: center'> $w_i$ 在取值范围内均匀随机</td>
        </tr>
        <tr>
            <td style='text-align: center'>19</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 9$ </td>
            <td style='text-align: center'> - </td>
        </tr>
        <tr>
            <td style='text-align: center'>20</td>
            <td style='text-align: center'> $n = 100000$ </td>
            <td style='text-align: center'> $k = 9$ </td>
            <td style='text-align: center'> - </td>
        </tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

对于所有数据，保证 $2 \leq n \leq 100000, \ 2 \leq k \leq 9, \ 0 \lt w_i \leq 10^{11}$。选手请注意使用 $64$ 位整数进行输入输出、存储和计算。

#### 评分方式
对于每个测试点：  
若输出文件的第 $1$ 行正确，得到该测试点 $40\%$ 的分数；  
若输出文件完全正确，得到该测试点 $100\%$ 的分数。

