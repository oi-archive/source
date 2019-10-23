
# 题目描述

威摄纪元公元 2233 年，人类掌握了一项新的科技：基于量子力学原理，在地球表面上的宇宙广播能够超光速地将信号传播到这个点坐标所在的、与地球相切的平面中。

自从万有引力号广播了坐标之后，它带着人类文明的种子，远离太阳系飞向了宇宙深处。

DX3906 星系黑域纪元公元 3333 年，万有引力号找到了一个十分庞大的 X 星系，直径数光年，其中有 3 个适合人类居住的星球，分布在 X 星系不同的角落中。经过商讨之后，万有引力号的部分成员选择留在这三个星球上定居。

对于定居的人类而言，实时通讯是十分必要的，因此一千一百年前发明的那套装置在这时候就派上了用场。显然，三个星球能够互相通讯，当且仅当三个宇宙广播的工作切平面完全重合。

现在，星球球长阿米巴找到了善于编程的你，希望你能够通过编程计算得出所有能够建立宇宙广播的方案。

在你承担了这个任务之后，你在心里说了一句，「这算啥，我 ygg 分分钟搞定」，然而善于读心的阿米巴马上把你叫了回来，语重心长的跟你说，人类文明还要延续，把 $K$ 维空间的 $K$ 个星球的建站方案一起解决了。球长也没太为难你，只要你求 $K\le 10$ 的情况，这是因为宇宙加上时间维之后是 $11$ 维的。

当你用 $3$ 分钟写完程序之后，阿米巴看了看，送给你一张二向箔——因为你没有在程序里考虑到这个情况。

给定坐标维数 $K\ge 2$，以及在 $K$ 维坐标下的 $K$ 个球（**可退化成点**，即半径可以为零），求出这 $K$ 个球的**所有公切面**。

数据保证不会出现无解或无穷多组解的情况，但不保证所有球都是相离的。

以下是一些定义：

- 距离：在 $K$ 维空间中，设有两个点 $A(a_0,a_1,\cdots,a_{K-1}),~B(b_0,b_1,\cdots,b_{K-1})$，则 $AB$ 之间的距离 $\displaystyle |AB|=\sqrt{\sum_{i=0}^{K-1} (a_i-b_i)^2}$；

- 球：在 $K$ 维空间中，与定点 $A$ 的距离为常数 $r$ 的点集，并同时称点 $A$ 为球心，$r$ 为该球半径；

  ​	当$K=2$时，即为大家在中学所熟知的圆。

- 超平面：到 $K$ 维空间中某两个点 $A,~B$ 距离相等的点集；在 $K$ 维空间中，超平面的维数为 $K-1$；

  ​	当 $K=2$ 时，即为大家在中学所熟知的直线（垂直平分线）。

- 球的切平面：一个超平面 $P$ 与球 $A$ 有且仅有一个交点；

- 球的公切面：一个超平面 $P$ 是所有球的切平面。

# 输入格式

这是一道提交答案题，共有8组输入数据，这些数据命名为 *1.in* ~ *8.in*。

每个测试点中包含多组数据。对于每个测试点：

- 第一行：测试点包含的数据组数 $T$，保证 $T \le 10$。
- 对于每组数据：
  - 第一行：坐标维数 $K$，保证 $K\le 10$。
  - 接下来 $K$ 行，每行 $K+1$ 个实数。第 $i$ 行的前 $K$ 个数代表第 $i$ 个球的球心所在的坐标，第 $K+1$ 个数代表第 $i$ 个球的半径。

# 输出格式

对于每组输入数据，你需要提交相应的输出文件 *1.out* ~ *8.out*。

对于每个测试点的每组数据：

- 第一行，一个正整数 $S$ ，表示在这组数据中你总共找到了 $S$ 组切平面。**如果没找到任何一组解，请务必输出 $0$，否则将会影响后续数据的评分，造成的后果由选手自行承担**；
- 接下来 $S\times K$ 行，每行 $K$ 个小数，对于相对的第 $S(i-1)+j$  行，表示在输出的第 $i$ 个解中，**对应输入**的第 $j$ 个球上的切点坐标；
- 最后一行，输出一个空行；

**在输出文件的最后，你可以添加任意内容，这不会影响你的得分。我们建议你在此处写一些有意义的内容（如简要方法），以便于我们在考后进行统计分析。单个输出文件大小不得超过 4M**。

# 样例

第一个样例 `0.in/ans` 见附加文件。

按照样例中的顺序，可视化结果如下所示

![01.png](/source/loj/2982/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDEvMTYvNWMzZjNiNjcxZjJjMC5wbmc=.png)
![02.png](/source/loj/2982/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDEvMTYvNWMzZjNiNjczOTcyYS5wbmc=.png)
![03.png](/source/loj/2982/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDEvMTYvNWMzZjNiNjczYjQzMy5wbmc=.png)
![04.png](/source/loj/2982/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDEvMTYvNWMzZjNiNjc1MmJlNC5wbmc=.png)

对于第 $4$ 组数据，由于篇幅原因，$8$ 种方案无法一一呈现到此处；

对于第 $5$ 组数据，限于人类目前科技水平而无法可视化；

在此深表歉意。

# 数据范围与提示

#### 评分标准

- 解的输出顺序没有要求。在一组解中，记输出答案为 $(A_0,A_1,\cdots,A_{K-1})$，如果存在一组标准答案 $(B_0,B_1,\cdots,B_{K-1})$，满足 $\displaystyle\sum_{i=0}^{K-1} |A_iB_i|^2\le 10^{-12}$，那么这一组输出答案将会被判定为正确。
- 在每个测试点的同一组数据中，我们会统计被匹配上的标准答案的公切面的个数，每个标准答案只会被匹配至多一次，输出重复的公切面不倒扣分。第 $i$ 组数据回答正确的比例为被匹配上的标准答案的个数除以标准答案的总个数，记为 $rate_i$。
- 对于每个测试点的评分方式：
  1. 如果你的输出格式不合法，或者参数不符合题目约定，或者某一组的答案个数超过该组标准答案个数的两倍以上（不含两倍），则得0分；
  2. 在不违背上述条件的情况下，算对其中任何一组数据的任何一个解就至少有一分；并且所有的答案都算对了，才能得到这个测试点的全部分数；
  3. 在不违背上述条件的情况下，记共有 $T$ 组数据，$rate_i$ 为第 $i$ 组数据回答正确的比例，$score$ 为这个测试点的分值，则 $Yourscore=\frac{score}{T}\cdot \sum_{i=1}^T \sqrt{rate_i}$ 在不违背以上原则的情况下四舍五入输出，即 $Yourscore\in [1,score-1]$。

各测试点分值不同，具体如下表所示：

<!-- BEGIN: Migrated markdown table -->

| 测试点 | $K$ | 分值 |
|:-:|:-:|:-:|
| 1 | $\le 2$ | $5$ |
| 2 | $\le 2$ | $15$ |
| 3 | $\le 3$ | $11$ |
| 4 | $\le 3$ | $14$ |
| 5 | $\le 3$ | $16$ |
| 6 | $\le 4$ | $7$ |
| 7 | $\le 4$ | $9$ |
| 8 | $\le 10$ | $23$ |

<!-- Migrated from original HTML table:
<table><thead>
<tr>
<th rowspan="1" style='text-align:center'>测试点</th>
<th rowspan="1" style='text-align:center'>$K$ </th>
<th rowspan="1" style='text-align:center'>分值</th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="1" style='text-align:center'>1</td>
<td rowspan="2" style='text-align:center'>$\le 2$ </td>
<td rowspan="1" style='text-align:center'>$5$ </td>
</tr>
<tr>
<td rowspan="1" style='text-align:center'>2</td>
<td rowspan="1" style='text-align:center'>$15$ </td>
</tr>
<tr>
<td rowspan="1" style='text-align:center'>3</td>
<td rowspan="3" style='text-align:center'>$\le 3$ </td>
<td rowspan="1" style='text-align:center'>$11$ </td>
</tr>
<tr>
<td rowspan="1" style='text-align:center'>4</td>
<td rowspan="1" style='text-align:center'>$14$ </td>
</tr>
<tr>
<td rowspan="1" style='text-align:center'>5</td>
<td rowspan="1" style='text-align:center'>$16$ </td>
</tr>
<tr>
<td rowspan="1" style='text-align:center'>6</td>
<td rowspan="2" style='text-align:center'>$\le 4$ </td>
<td rowspan="1" style='text-align:center'>$7$ </td>
</tr>
<tr>
<td rowspan="1" style='text-align:center'>7</td>
<td rowspan="1" style='text-align:center'>$9$ </td>
</tr>
<tr>
<td rowspan="1" style='text-align:center'>8</td>
<td rowspan="1" style='text-align:center'>$\le 10$ </td>
<td rowspan="1" style='text-align:center'>$23$ </td>
</tr>
</tbody></table>
-->

<!-- END: Migrated markdown table --> 

