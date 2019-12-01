
# 题目描述

在马路边有一排整齐的 $n$ 棵樱花树，每棵树的高度都恰好为 $h$。某天，一只可爱的小猫偶然跑到树上来玩，但是这只小猫有些对樱花过敏，所以她现在想赶快离开这些樱花树。

具体来说，现在小猫位于第 $x$ 棵樱花树上高度为 $y$ 的位置，她可以通过两种跳跃来离开樱花树：

**轻轻跳**：向左或向右移动 $a$ 棵樱花树的同时，所在高度下降 $b$，即一次轻轻跳可以从起点移动到第 $x+a$ 或 $x−a$ 棵树上高度为 $y−b$ 的位置，注意当小猫所在高度不大于 $b$ 时不可以使用轻轻跳。

**使劲跳**：向左或向右移动 $a$ 棵樱花树的同时，所在高度上升 $b$，即一次使劲跳可以从起点移动到第 $x+a$ 或 $x−a$ 棵树上高度为 $y+b$ 的位置，注意当小猫所在高度大于 $h−b$ 时不可以使用使劲跳。

为了离开这片樱花树，小猫需要移动到第 $1$ 或第 $n$ 棵树上，高度为 $h$ 或 $1$ 的位置（这样她可以呼吸新鲜空气或者直接走开樱花树）。现在小猫想知道，自己最少需要多少次跳跃才能达成目标。由于她是一只可爱的小猫，所以希望由你来告诉她。

# 输入格式

从标准输入读入数据。

输入数据第一行包含一个正整数 $T$，表示测试数据的组数，各组数据之间没有空行。

接下来 $T$ 行，依次描述每组数据：

每组数据包含一行，包含六个正整数 $n,h,x,y,a,b$，其含义见题目描述。

# 输出格式

输出到标准输出。

输出由 $T$ 组数据组成，各组数据之间没有空行。对于每一组数据：

若小猫可以成功离开樱花树，请输出她需要的最少跳跃次数。

若小猫无法通过给定的跳跃方法离开樱花树，**请输出`-1`**。

# 样例

#### 样例输入 1

```plain
3
5 5 3 3 2 2
5 7 3 5 2 2
5 7 4 6 1 1
```

#### 样例输出 1

```plain
1
1
1
```

#### 样例输入 2

```plain
3
5 5 3 3 3 2
5 7 1 4 2 2
5 7 1 2 1 2
```

#### 样例输出 2

```plain
-1
-1
-1
```

#### 样例输入 3

```plain
4
999999999999 999999999999 454545454545 454545454545 1 1
777777777777 777777777777 343434343434 343434343434 1 1
777777777777 999999999999 343434343434 454545454545 1 1
999999999999 777777777777 454545454545 343434343434 1 1
```

#### 样例输出 3

```plain
454545454544
343434343433
-1
-1
```

# 数据范围与提示

对于所有的数据，保证 $1\leq T\leq 100$，$1\leq x,a\leq n$，$1\leq y,b\leq h$，其它数据规模与约定请见下表。

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n,h$ 的范围 | 特殊约定 |
|-|-|-|
| 1 | $\leq 10$ | $b=1$ |
| 2 | $\leq 10$ | $b=1$ |
| 3 | $\leq 10$ | $a=b=1$ |
| 4 | $\leq 10$ | $a=b=1$ |
| 5 | $\leq 10$ | 无 |
| 6 | $\leq 10$ | 无 |
| 7 | $\leq 10$ | 无 |
| 8 | $\leq 10$ | 无 |
| 9 | $\leq 500$ | $b=1$ |
| 10 | $\leq 500$ | $b=1$ |
| 11 | $\leq 500$ | $a=b=1$ |
| 12 | $\leq 500$ | $a=b=1$ |
| 13 | $\leq 500$ | 无 |
| 14 | $\leq 500$ | 无 |
| 15 | $\leq 500$ | 无 |
| 16 | $\leq 10^5$ | $h \leq 10$ |
| 17 | $\leq 10^5$ | $h \leq 10$ |
| 18 | $\leq 10^5$ | 无 |
| 19 | $\leq 10^5$ | 无 |
| 20 | $\leq 10^5$ | 无 |
| 21 | $\leq 10^{15}$ | $h \leq 10$ |
| 22 | $\leq 10^{15}$ | $h \leq 10$ |
| 23 | $\leq 10^{15}$ | 无 |
| 24 | $\leq 10^{15}$ | 无 |
| 25 | $\leq 10^{15}$ | 无 |

<!-- Migrated from original HTML table:
<table class="ui center aligned celled table"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n,h$ 的范围</th><th rowspan="1">特殊约定</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="8">$\leq 10$ </td><td rowspan="2">$b=1$ </td></tr><tr><td rowspan="1">2</td></tr><tr><td rowspan="1">3</td><td rowspan="2">$a=b=1$ </td></tr><tr><td rowspan="1">4</td></tr><tr><td rowspan="1">5</td><td rowspan="4">无</td></tr><tr><td rowspan="1">6</td></tr><tr><td rowspan="1">7</td></tr><tr><td rowspan="1">8</td></tr><tr><td rowspan="1">9</td><td rowspan="7">$\leq 500$ </td><td rowspan="2">$b=1$ </td></tr><tr><td rowspan="1">10</td></tr><tr><td rowspan="1">11</td><td rowspan="2">$a=b=1$ </td></tr><tr><td rowspan="1">12</td></tr><tr><td rowspan="1">13</td><td rowspan="3">无</td></tr><tr><td rowspan="1">14</td></tr><tr><td rowspan="1">15</td></tr><tr><td rowspan="1">16</td><td rowspan="5">$\leq 10^5$ </td><td rowspan="2">$h \leq 10$ </td></tr><tr><td rowspan="1">17</td></tr><tr><td rowspan="1">18</td><td rowspan="3">无</td></tr><tr><td rowspan="1">19</td></tr><tr><td rowspan="1">20</td></tr><tr><td rowspan="1">21</td><td rowspan="5">$\leq 10^{15}$ </td><td rowspan="2">$h \leq 10$ </td></tr><tr><td rowspan="1">22</td></tr><tr><td rowspan="1">23</td><td rowspan="3">无</td></tr><tr><td rowspan="1">24</td></tr><tr><td rowspan="1">25</td></tr></tbody></table>
-->

<!-- END: Migrated markdown table -->

<hr style='color: #ddd; margin-bottom: 1em'>

来自 [CodePlus](https://cp.thusaac.com/) 第 4 次月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。  
Credit：idea 与命题/何昊天　验题/钟皓曦  
Git Repo：https://git.thusaac.org/publish/CodePlus4  
感谢腾讯公司对此次比赛的支持。

