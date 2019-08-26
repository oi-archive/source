
# 题目描述

小Y是一个心灵手巧的OIer，她有许多二叉树模型。

小Y的二叉树模型中，每个结点都具有一个编号，小Y把她最喜欢的一个二叉树模型挂在了墙上，树根在最上面，左右子树分别在树根的左下方与右下方，且他们也都满足这样的悬挂规则。为了让这个模型更加美观，小Y选择了一种让这棵二叉树的中序遍历序列最小的悬挂方法。所谓中序遍历最小，就是指中序遍历的结点编号序列的字典序最小。

一天，这个模型不小心被掉在了地上，幸运的是，所有结点和边都没摔坏，但是她想不起这个模型原来是怎么悬挂的了，也就是说：她想不起来树根节点的编号了。

小Y最近忙于准备清华集训，所以没太多时间处理别的事情，她只好找到同样心灵手巧的你帮忙复原她的二叉树模型。

给定小Y的二叉树模型，结点的编号为 $1$ ~ $n$ ，你需要给出其可能的最小的中序遍历，方便小Y更快的摆好她的模型。

# 输入格式

第一行为一个正整数 $n$ ，表示点的个数。

后接 $n$ 行，每行若干个整数：

第 $i+1$ 行的第一个整数为 $k_i$ ，表示编号为 $i$ 的结点的度数，后接 $k_i$ 个整数 $a_{i,j}$ ，表示编号为 $i$ 的结点与编号为 $a_{i,j}$ 的结点之间有一条边。

同一行输入的相邻两个元素之间，用恰好一个空格隔开。

# 输出格式

输出共一行， $n$ 个整数，表示字典序最小的中序遍历。

# 样例

#### 样例输入1
```plain
4
3 2 3 4
1 1
1 1
1 1
```

#### 样例输出1
```plain
2 1 3 4
```


#### 样例解释

样例的一组最优解如下：

![explanation.png](source/loj/2324/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMTAvNWEyYzk1NGY1ODM2NS5wbmc=.png)

其中结点$4$为根，结点$1$为结点$4$的左儿子，结点$2,3$分别为结点$1$的左右儿子。

# 数据范围与提示

本题共20个测试点，每个测试点5分。各个测试点的数据范围如下：

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n \le$ | $k_i$ | 特殊条件 |
|:-:|:-:|:-:|:-:|
| 1 | 5 | 1,2,3 | 无 |
| 2 | 10 | 1,2,3 | 无 |
| 3 | 15 | 1,2,3 | 无 |
| 4 | 20 | 1,2,3 | 无 |
| 5 | 100 | 1,2,3 | 无 |
| 6 | 1000 | 1,2,3 | 无 |
| 7 | 2000 | 1,2,3 | 无 |
| 8 | 5000 | 1,2,3 | 无 |
| 9 | 1000000 | 1,2 | 结点 $i$ 与结点 $i-1$ 相连 |
| 10 | 100000 | 1,2 | 无 |
| 11 | 300000 | 1,2 | 无 |
| 12 | 1000000 | 1,2 | 无 |
| 13 | 100000 | 1,3 | 保证数据随机 |
| 14 | 1000000 | 1,3 | 无 |
| 15 | 20000 | 1,2,3 | 保证数据随机 |
| 16 | 200000 | 1,2,3 | 保证数据随机 |
| 17 | 100000 | 1,2,3 | 无 |
| 18 | 500000 | 1,2,3 | 无 |
| 19 | 800000 | 1,2,3 | 无 |
| 20 | 1000000 | 1,2,3 | 无 |

<!-- Migrated from original HTML table:
<table><thead>
<tr>
<th style='text-align:center'>测试点编号</th><th style='text-align:center'>$n \le$ </th><th style='text-align:center'>$k_i$ </th><th style='text-align:center'>特殊条件</th></tr>
</thead><tbody>
<tr>
<td style='text-align:center'>1</td><td style='text-align:center'>5</td><td style='text-align:center' rowspan='8'>1,2,3</td><td style='text-align:center' rowspan='8'>无</td></tr>
<tr>
<td style='text-align:center'>2</td><td style='text-align:center'>10</td></tr>
<tr>
<td style='text-align:center'>3</td><td style='text-align:center'>15</td></tr>
<tr>
<td style='text-align:center'>4</td><td style='text-align:center'>20</td></tr>
<tr>
<td style='text-align:center'>5</td><td style='text-align:center'>100</td></tr>
<tr>
<td style='text-align:center'>6</td><td style='text-align:center'>1000</td></tr>
<tr>
<td style='text-align:center'>7</td><td style='text-align:center'>2000</td></tr>
<tr>
<td style='text-align:center'>8</td><td style='text-align:center'>5000</td></tr>
<tr>
<td style='text-align:center'>9</td><td style='text-align:center'>1000000</td><td style='text-align:center' rowspan='4'>1,2</td><td style='text-align:center'>结点 $i$ 与结点 $i-1$ 相连</td></tr>
<tr>
<td style='text-align:center'>10</td><td style='text-align:center'>100000</td><td style='text-align:center' rowspan='3'>无</td></tr>
<tr>
<td style='text-align:center'>11</td><td style='text-align:center'>300000</td></tr>
<tr>
<td style='text-align:center'>12</td><td style='text-align:center'>1000000</td></tr>
<tr>
<td style='text-align:center'>13</td><td style='text-align:center'>100000</td><td style='text-align:center' rowspan='2'>1,3</td><td style='text-align:center'>保证数据随机</td></tr>
<tr>
<td style='text-align:center'>14</td><td style='text-align:center'>1000000</td><td style='text-align:center'>无</td></tr>
<tr>
<td style='text-align:center'>15</td><td style='text-align:center'>20000</td><td style='text-align:center' rowspan='6'>1,2,3</td><td style='text-align:center' rowspan='2'>保证数据随机</td></tr>
<tr>
<td style='text-align:center'>16</td><td style='text-align:center'>200000</td></tr>
<tr>
<td style='text-align:center'>17</td><td style='text-align:center'>100000</td><td style='text-align:center' rowspan='4'>无</td></tr>
<tr>
<td style='text-align:center'>18</td><td style='text-align:center'>500000</td></tr>
<tr>
<td style='text-align:center'>19</td><td style='text-align:center'>800000</td></tr>
<tr>
<td style='text-align:center'>20</td><td style='text-align:center'>1000000</td></tr>
</tbody></table>
-->

<!-- END: Migrated markdown table -->


随机数据的生成方式如下：

对于第13个测试点，从一棵两个结点的树开始，每次随机一个树上的度数为1的结点（即叶结点），并生成两个与之直接相连的结点，直到这棵树上有 $n$ 个结点。显然，在这个测试点中，$n$ 是一个偶数。

对于第15和第16个测试点，从一棵一个结点的树开始，每次随机一个树上的度数不超过2的结点，并生成一个与之直接相连的结点，直到这棵树上有 $n$ 个结点。

我们提供了一个只包含输入和输出功能的程序 `binary\sample.cpp`。
关于该程序的说明，见 `readme.txt`。
你可以在答题时使用该程序的代码，也可以不使用，这将与你的得分无关。

