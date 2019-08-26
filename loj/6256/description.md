
# 题目描述

“CodePlus 比赛的时候在做什么？有没有空？能来解决停机问题吗？” qmqmqm 这样问 sublinekelzrip。

当然，sublinekelzrip 并不会停机问题，所以 qmqmqm 改为提出了另一个题目，现在请你帮助 sublinekelzrip 解决这个题目。

<hr style='color: #ddd; margin-bottom: 1em'>

这个问题是这样的：

对于任何一个 $n$ 阶方阵，若任意从其中选择 $n$ 个不同行不同列的位置，其上的权值之和均相等，则我们称这个矩阵是巧妙的。注意对于 $n=1$ 的任何矩阵都是巧妙的。
例如矩阵 $\begin{matrix}1&2&3\\4&5&6\\7&8&9\end{matrix}$ 是巧妙的，因为 $1+5+9$ $=$ $1+6+8$ $=$ $2+4+9$ $=$ $2+6+7$ $=$ $3+5+7$ $=$ $3+4+8$ $=15$，而矩阵 $\begin{matrix}1&2\\2&1\end{matrix}$ 不巧妙，因为 $1+1 \neq 2+2$ 。

现在有一个 $n \times m$ 大小的矩阵 $M$ 以及 $T$ 个询问，每次询问其一个子方阵是否是巧妙的。

# 输入格式

从标准输入读入数据。

输入第一行包含三个正整数 $n,m,T$。

之后 $n$ 行每行 $m$ 个空格分割的非负整数，表示矩阵 $M$。

之后 $T$ 行每行 $3$ 个正整数 $x,y,k$，表示询问第 $x$ 行第 $y$ 列为左上角的 $k$ 阶方阵是否是巧妙的。保证这个矩阵完全位于 $M$ 之中。

# 输出格式

输出到标准输出。

输出包含 $T$ 行每行一个字符 `Y` 或者 `N` 。`Y` 表示被询问的方阵是巧妙的，`N` 表示不是。

# 样例

##### 样例输入

```plain
3 3 4
1 1 1
1 1 1
1 1 2
1 1 2
1 1 3
2 2 2
2 1 2

```

##### 样例输出

```plain
Y
N
N
Y

```

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点 | $\max(n,m)$ | $T$ | 其他 |
|-|-|-|-|
| 1 | $=5$ | $=5$ | 无 |
| 2 | $=100$ | $=20$ | 无 |
| 3 | $=100$ | $=20$ | 无 |
| 4 | $=100$ | $=20$ | 无 |
| 5 | $=500$ | $=20$ | 无 |
| 6 | $=500$ | $=20$ | 无 |
| 7 | $=500$ | $=100000$ | 矩阵$M$的元素在值域内等概率随机 |
| 8 | $=500$ | $=100000$ | 无 |
| 9 | $=500$ | $=100000$ | 无 |
| 10 | $=500$ | $=100000$ | 无 |

<!-- Migrated from original HTML table:
<table class="ui center aligned celled table">
<thead>
  <tr>
    <th rowspan="1">测试点</th>
    <th rowspan="1">$\max(n,m)$ </th>
    <th rowspan="1">$T$ </th>
    <th rowspan="1">其他</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="1">1</td>
    <td rowspan="1">$=5$ </td>
    <td rowspan="1">$=5$ </td>
    <td rowspan="6">无</td>
  </tr>
  <tr>
    <td rowspan="1">2</td>
    <td rowspan="3">$=100$ </td>
    <td rowspan="5">$=20$ </td>
  </tr>
  <tr>
    <td rowspan="1">3</td>
  </tr>
  <tr>
    <td rowspan="1">4</td>
  </tr>
  <tr>
    <td rowspan="1">5</td>
    <td rowspan="6">$=500$ </td>
  </tr>
  <tr>
    <td rowspan="1">6</td>
  </tr>
  <tr>
    <td rowspan="1">7</td>
    <td rowspan="4">$=100000$ </td>
    <td rowspan="1">矩阵$M$的元素在值域内等概率随机</td>
  </tr>
  <tr>
    <td rowspan="1">8</td>
    <td rowspan="3">无</td>
  </tr>
  <tr>
    <td rowspan="1">9</td>
  </tr>
  <tr>
    <td rowspan="1">10</td>
  </tr>
</tbody>
</table>
-->

<!-- END: Migrated markdown table --> 

对于所有的数据，$0 \leq M_{ij} \leq 10^9$，$1 \leq x \leq n$，$1 \leq y \leq m$ 。

<hr style='color: #ddd; margin-bottom: 1em'>

来自 CodePlus 2017 12 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。  
Credit：idea/卢政荣　命题/卢政荣　验题/吕时清，王聿中  
Git Repo：https://git.thusaac.org/publish/CodePlus201712  
感谢腾讯公司对此次比赛的支持。

