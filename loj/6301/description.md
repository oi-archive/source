
# 题目描述

> 莫斯科吹的寒风 / 仿佛昨日那场梦 / 啊 你还会记得我吗 

> 1941.12.

> 寒冷刺骨的天气、疲惫不堪的军队……包围首都的作战计划陷入了困境。空军或许是拯救战况的最后希望了，元首 Adolf 想道。

在一个 $n \times m$ 的网格区域中存在一个陆军单位需要补给，区域中的每个格子为**空地**或**障碍物**中的一种。航空舰队需要派遣若干运输机前往此区域，每一架运输机可以向两个相邻（有一条公共边）的**空地**投放物资。为防止不必要的损坏，一个标记为**空地**的格子至多只能得到一次投放。

由于天气原因，陆军单位所在的确切位置并不能确定。因此元首想知道，对于每个**空地**格子，当陆军单位在其中（视作**障碍物**）时，用若干（可以为 $0$）架运输机向其余**空地**投放任意数量的物资的不同方案数。两个投放方案不同，当且仅当存在一个格子在一个方案中被投放而另一方案中未被投放，**或**存在两个被投放的格子，在一个方案中被同一架运输机投放而在另一方案中非然。若仍有疑问，请参考「样例 1 解释」。

你需要编写程序帮助元首计算这些值对 $10^9+7$ 取模的结果。

# 输入格式

从标准输入读入数据。

* 第 $1$ 行：两个空格分隔的正整数 $n, m$ —— 网格区域的行数和列数。
* 接下来 $n$ 行：其中第 $i$ 行包含 $m$ 个空格分隔的整数 $A_{i1}, A_{i2}, \ldots, A_{im}$ —— 其中 $A_{ij} = 0$ 表示第 $i$ 行第 $j$ 列的格子为**空地**；$A_{ij} = 1$ 表示该格为**障碍物**。

# 输出格式

输出到标准输出。

对于每组数据输出 $n$ 行，第 $i$ 行包含 $m$ 个空格分隔的整数 $B_{i1}, B_{i2}, \ldots, B_{im}$ —— 若第 $i$ 行第 $j$ 列的格子为**空地**，$B_{ij}$ 为该格变为**障碍物**后投放的方案数；否则 $B_{ij} = 0$。

# 样例

#### 样例 1 输入

```plain
2 4
0 0 0 0
0 0 0 1
```

#### 样例 1 输出

```plain
14 13 10 22
15 11 17 0
```

#### 样例 1 解释

以第 $2$ 行第 $1$ 列的**空地**格为例，其变为**障碍物**后的网格如下图，其中白色格子代表**空地**，黑色格子代表**障碍物**。

![Sample Grid](https://oj.thusaac.org/staticdata/publicfile.te4XJXbxvIXGwXES.sample_grid.png/sample_grid.png)

$15$ 种方案如下图所示，不同颜色代表不同运输机的投放位置。

![Sample Ways](https://oj.thusaac.org/staticdata/publicfile.Qi7PBcz2ZqEmCXJd.sample_ways.png/sample_ways.png)

#### 样例 2 输入

```plain
4 5
0 0 0 1 1
1 0 0 0 1
1 0 0 0 0
0 0 0 0 0
```

#### 样例 2 输出

```plain
1882 827 1523 0 0
0 1189 791 1529 0
0 1106 979 823 1315
1810 899 1136 1075 1189
```

# 数据范围与提示

#### 子任务

对于所有数据，有 $1 \leq n, m \leq 17$，$A_{ij} \in \{0, 1\}$。

<!-- BEGIN: Migrated markdown table -->

| 子任务编号 | 分值 | $n$ | $m$ |
|-|-|-|-|
| 1 | 10 | $\leq 2$ | $\leq 17$ |
| 2 | 8 | $\leq 5$ | $\leq 5$ |
| 3 | 6 | $\leq 9$ | $\leq 9$ |
| 4 | 9 | $\leq 12$ | $\leq 12$ |
| 5 | 17 | $\leq 15$ | $\leq 15$ |
| 6 | 17 | $\leq 16$ | $\leq 16$ |
| 7 | 33 | $\leq 17$ | $\leq 17$ |

<!-- Migrated from original HTML table:
<table class="ui celled center aligned table"><thead><tr><th rowspan="1">子任务编号</th><th rowspan="1">分值</th><th rowspan="1">$n$ </th><th rowspan="1">$m$ </th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">10</td><td rowspan="1">$\leq 2$ </td><td rowspan="1">$\leq 17$ </td></tr><tr><td rowspan="1">2</td><td rowspan="1">8</td><td rowspan="1">$\leq 5$ </td><td rowspan="1">$\leq 5$ </td></tr><tr><td rowspan="1">3</td><td rowspan="1">6</td><td rowspan="1">$\leq 9$ </td><td rowspan="1">$\leq 9$ </td></tr><tr><td rowspan="1">4</td><td rowspan="1">9</td><td rowspan="1">$\leq 12$ </td><td rowspan="1">$\leq 12$ </td></tr><tr><td rowspan="1">5</td><td rowspan="1">17</td><td rowspan="1">$\leq 15$ </td><td rowspan="1">$\leq 15$ </td></tr><tr><td rowspan="1">6</td><td rowspan="1">17</td><td rowspan="1">$\leq 16$ </td><td rowspan="1">$\leq 16$ </td></tr><tr><td rowspan="1">7</td><td rowspan="1">33</td><td rowspan="1">$\leq 17$ </td><td rowspan="1">$\leq 17$ </td></tr></tbody></table>
-->

<!-- END: Migrated markdown table --> 

> “_Von allem Anfang an bin ich nur verraten und betrogen worden!_” 

题面与史实不尽相符。

<hr style='color: #ddd; margin-bottom: 1em'>

来自 CodePlus 2018 3 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。  
Credit：idea/吕时清　命题/吕时清　验题/吕欣，王聿中  
Git Repo：https://git.thusaac.org/publish/CodePlus3  
感谢腾讯公司对此次比赛的支持。

