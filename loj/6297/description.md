
# 题目描述

为了总结过去一段时间的命题工作，王队长组织了“我最喜欢的题目”评选活动，并邀请各位选手给题目进行投票。

具体来说，每道题目有一个正整数作为它的编号，一共有 $n$ 名选手给它们进行投票，每位选手投且仅投给一道题，其中第 $i$ 位选手所投票的题目编号为 $a_i$。

由于投票的选手众多，所以王队长请你来帮忙统计得票数。你需要找出收获选手投票最多的**题目数量**与**他们的编号**，并按**从小到大**的顺序列出这些编号。但这里有一个**例外情况**：如果所有被投票的题目得票数都相同，则王队长认为这次活动比较失败，你应该**输出`-1`**。

# 输入格式

输入数据第一行包含一个正整数 $T$，表示测试数据的组数，各组数据之间没有空行。

接下来 $2T$ 行，依次描述每组数据：

每组数据包含两行，其中第一行包含一个正整数 $n$，表示参与这次活动的选手人数。第二行包含 $n$ 个由空格隔开的正整数 $a_1\sim a_n$，其中第 $i$ 个数 $a_i$ 表示第 $i$ 位选手所投票的题目编号。

# 输出格式

输出应由 $T$ 组数据组成，各组数据之间没有空行。对于每一组数据：

若没有出现题面所述的例外情况，则这组测试数据输出两行，其中第一行输出一个正整数 $m$，表示收获选手投票最多的题目数量，第二行按**从小到大**的顺序输出 $m$ 个正整数，表示这些题目的编号。

若出现题面所述的例外情况，则这组测试数据输出一行，请**输出`-1`**。

# 样例

#### 样例输入 1

```plain
3
10
2 6 1 2 1 1 2 6 7 1
10
10 3 6 6 3 10 6 6 6 2
10
8 8 10 10 10 10 8 5 8 8
```

#### 样例输出 1

```plain
1
1
1
6
1
8
```

#### 样例输入 2

```plain
3
10
1 4 3 1 8 8 7 2 8 7
10
1 10 9 1 3 2 9 9 2 1
10
4 1 5 4 1 9 5 5 4 1
```

#### 样例输出 2

```plain
1
8
2
1 9
3
1 4 5
```

#### 样例输入 3

```plain
3
10
3 3 10 8 8 3 10 8 10 3
10
2 2 8 6 8 4 2 4 4 8
10
6 2 5 6 7 5 7 10 2 10
```

#### 样例输出 3

```plain
1
3
3
2 4 8
-1
```

# 数据范围与提示

对于所有的数据，保证 $1\leq T\leq 5$，$1\leq a_i\leq 10^9$，其它数据规模与约定请见下表。

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n$的范围 | $a_i$的范围 | 特殊约定 |
|-|-|-|-|
| 1 | $=2000$ | $\leq n$ | 得票数最多的题目唯一 |
| 2 | $=2000$ | $\leq n$ | 得票数最多的题目唯一 |
| 3 | $=2000$ | $\leq 10^9$ | 得票数最多的题目唯一 |
| 4 | $=2000$ | $\leq n$ | 不会出现例外情况 |
| 5 | $=2000$ | $\leq n$ | 不会出现例外情况 |
| 6 | $=2000$ | $\leq 10^9$ | 不会出现例外情况 |
| 7 | $=2000$ | $\leq n$ | 无 |
| 8 | $=2000$ | $\leq n$ | 无 |
| 9 | $=2000$ | $\leq 10^9$ | 无 |
| 10 | $=2000$ | $\leq 10^9$ | 无 |
| 11 | $=100000$ | $\leq n$ | 得票数最多的题目唯一 |
| 12 | $=100000$ | $\leq n$ | 得票数最多的题目唯一 |
| 13 | $=100000$ | $\leq 10^9$ | 得票数最多的题目唯一 |
| 14 | $=100000$ | $\leq n$ | 不会出现例外情况 |
| 15 | $=100000$ | $\leq n$ | 不会出现例外情况 |
| 16 | $=100000$ | $\leq 10^9$ | 不会出现例外情况 |
| 17 | $=100000$ | $\leq n$ | 无 |
| 18 | $=100000$ | $\leq n$ | 无 |
| 19 | $=100000$ | $\leq 10^9$ | 无 |
| 20 | $=100000$ | $\leq 10^9$ | 无 |

<!-- Migrated from original HTML table:
<table class="ui center aligned celled table"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n$的范围</th><th rowspan="1">$a_i$的范围</th><th rowspan="1">特殊约定</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="10">$=2000$ </td><td rowspan="2">$\leq n$ </td><td rowspan="3">得票数最多的题目唯一</td></tr><tr><td rowspan="1">2</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$\leq 10^9$ </td></tr><tr><td rowspan="1">4</td><td rowspan="2">$\leq n$ </td><td rowspan="3">不会出现例外情况</td></tr><tr><td rowspan="1">5</td></tr><tr><td rowspan="1">6</td><td rowspan="1">$\leq 10^9$ </td></tr><tr><td rowspan="1">7</td><td rowspan="2">$\leq n$ </td><td rowspan="4">无</td></tr><tr><td rowspan="1">8</td></tr><tr><td rowspan="1">9</td><td rowspan="2">$\leq 10^9$ </td></tr><tr><td rowspan="1">10</td></tr><tr><td rowspan="1">11</td><td rowspan="10">$=100000$ </td><td rowspan="2">$\leq n$ </td><td rowspan="3">得票数最多的题目唯一</td></tr><tr><td rowspan="1">12</td></tr><tr><td rowspan="1">13</td><td rowspan="1">$\leq 10^9$ </td></tr><tr><td rowspan="1">14</td><td rowspan="2">$\leq n$ </td><td rowspan="3">不会出现例外情况</td></tr><tr><td rowspan="1">15</td></tr><tr><td rowspan="1">16</td><td rowspan="1">$\leq 10^9$ </td></tr><tr><td rowspan="1">17</td><td rowspan="2">$\leq n$ </td><td rowspan="4">无</td></tr><tr><td rowspan="1">18</td></tr><tr><td rowspan="1">19</td><td rowspan="2">$\leq 10^9$ </td></tr><tr><td rowspan="1">20</td></tr></tbody></table>
-->

<!-- END: Migrated markdown table --> 

<hr style='color: #ddd; margin-bottom: 1em'>

来自 CodePlus 2018 3 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。  
Credit：idea/何昊天　命题/何昊天　验题/丁子钧  
Git Repo：https://git.thusaac.org/publish/CodePlus3  
感谢腾讯公司对此次比赛的支持。

