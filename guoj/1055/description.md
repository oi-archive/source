
# 题目描述

蚯蚓幼儿园有$n$只蚯蚓。幼儿园园长神刀手为了管理方便，时常让这些蚯蚓们列队表演。

所有蚯蚓用从 $1$ 到 $n$ 的连续正整数编号。每只蚯蚓的长度可以用一个正整数表示，根据入园要求，所有蚯蚓的长度都不超过 $6$ 。神刀手希望这些蚯蚓排成若干个队伍，初始时，每只蚯蚓各自排成一个仅有一只蚯蚓的队伍，该蚯蚓既在队首，也在队尾。

神刀手将会依次进行 $m$ 次操作，每个操作都是以下三种操作中的一种：

1. 给出 $i$ 和 $j$ ，令 $i$ 号蚯蚓与 $j$ 号蚯蚓所在的两个队伍合并为一个队伍，具体来说，令 $j$ 号蚯蚓紧挨在 $i$ 号蚯蚓之后，其余蚯蚓保持队伍的前后关系不变。

2. 给出 $i$ ，令 $i$ 号蚯蚓与紧挨其后的一只蚯蚓分离为两个队伍，具体来说，在分离之后， $i$ 号蚯蚓在其中一个队伍的队尾，原本紧挨其后的那一只蚯蚓在另一个队伍的队首，其余蚯蚓保持队伍的前后关系不变。

3. 给出一个正整数 $k$ 和一个长度至少为 $k$ 的数字串 $s$ ，对于 $s$ 的每个长度为 $k$ 的连续子串 $t$ （这样的子串共有 $|s|-k+1$ 个，其中 $|s|$ 为 $s$ 的长度），定义函数 $f(t)$ ，询问所有这些$f(t)$的**乘积**对 $998244353$ 取模后的结果。其中$f(t)$的定义如下：

对于当前的蚯蚓队伍，定义某个蚯蚓的**向后 $k$ 数字串**为：从该蚯蚓出发，沿队伍的向后方向，寻找最近的 $k$ 只蚯蚓（包括其自身），将这些蚯蚓的长度视作字符连接而成的数字串；如果这样找到的蚯蚓不足 $k$ 只，则其没有**向后$k$数字串**。例如蚯蚓的队伍为 $10$ 号蚯蚓在队首，其后是 $22$ 号蚯蚓，其后是 $3$ 号蚯蚓（为队尾），这些蚯蚓的长度分别为 $4$ 、 $5$ 、 $6$ ，则 $10$ 号蚯蚓的**向后 $3$ 数字串**为`456`， $22$ 号蚯蚓没有**向后 $3$ 数字串**，但其**向后 $2$ 数字串**为`56`，其**向后 $1$ 数字串**为`5`。

而 $f(t)$ 表示所有蚯蚓中，**向后 $k$ 数字串**恰好为 $t$ 的蚯蚓只数。


# 输入格式

从标准输入读入数据。

输入文件的第一行有两个正整数 $n,m$ ，分别表示蚯蚓的只数与操作次数。

第二行包含 $n$ 个不超过 $6$ 的正整数，依次表示编号为 $1,2,\dots,n$ 的蚯蚓的长度。

接下来 $m$ 行，每行表示一个操作。每个操作的格式可以为：

* `1` $i$ $j$（$1 \leq i, j \leq n$）表示：令 $i$ 号与 $j$ 号蚯蚓**所在**的两个队伍合并为一个队伍，新队伍中， $j$ 号蚯蚓紧挨在 $i$ 号蚯蚓之后。保证在此操作之前， $i$ 号蚯蚓在某个队伍的队尾， $j$ 号蚯蚓在某个队伍的队首，且两只蚯蚓不在同一个队伍中。

* `2` $i$（$1 \leq i \leq n$）表示：令 $i$ 号蚯蚓与紧挨其后一个蚯蚓分离为两个队伍。保证在此操作之前， $i$ 号蚯蚓不是某个队伍的队尾。

* `3` $s$ $k$（$k$为正整数，$s$为一个长度至少为$k$的数字串）表示：询问 $s$ 的每个长度为 $k$ 的子串 $t$ 的 $f(t)$ 的乘积，对998244353取模的结果。 $f(t)$ 的定义见题目描述。

同一行输入的相邻两个元素之间，用恰好一个空格隔开。

输入文件可能较大，请不要使用过于缓慢的读入方式。


# 输出格式

输出到标准输出。

依次对于每个形如`3` $s$ $k$的操作，输出一行，仅包含一个整数，表示询问的结果。


# 样例

#### 样例 1



#### 输入

```plain
5 9
3 1 3 5 3
3 333135 2
3 333135 1
1 1 3
1 2 5
1 3 2
1 5 4
3 333135 2
3 333135 1
3 333135 3

```



#### 输出

```plain
0
81
1
81
0

```


#### 解释

第一次询问：由于每个队伍均只有一只蚯蚓，所以没有任何蚯蚓有**向后2数字串**，答案为 $f($`33`$) \times f($`33`$) \times f($`31`$) \times f($`13`$) \times f($`35`$) = 0 \times 0 \times 0 \times 0 \times 0 = 0$ 。


第二次询问：每个队伍仍只有一只蚯蚓，每只蚯蚓的**向后1数字串**就是将自己的长度视为字符的数字串，即：得到的5个**向后1数字串**为`1`、`3`、`3`、`3`、`5`（不分先后顺序，下同），答案为 $f($`3`$) \times f($`3`$) \times f($`3`$) \times f($`1`$) \times f($`3`$) \times f($`5`$) = 3 \times 3 \times 3 \times 1 \times 3 \times 1 = 81$ 。

接下来进行了若干次队伍的合并操作，使得所有蚯蚓合并成了一个队伍，这个队伍从前到后的蚯蚓依次为： $1$ 号蚯蚓（长度为 $3$ ）、$3$ 号蚯蚓（长度为 $3$ ）、$2$ 号蚯蚓（长度为 $1$ ）、$5$ 号蚯蚓（长度为 $3$ ）、$4$ 号蚯蚓（长度为 $5$ ）。

第三次询问： $4$ 号蚯蚓没有**向后2数字串**，而其他蚯蚓都有。得到的4个**向后2数字串**为`13`、`31`、`33`、`35`，答案为 $f($`33`$) \times f($`33`$) \times f($`31`$) \times f($`13`$) \times f($`35`$) = 1 \times 1 \times 1 \times 1 \times 1 = 1$。

第四次询问：虽然队伍的排列方式改变了，但是每只蚯蚓的**向后1数字串**没有发生改变，所以答案同第二次询问。

第五次询问： $4$ 号蚯蚓、 $5$号蚯蚓没有**向后3数字串**，而其他蚯蚓都有。得到的3个**向后3数字串**为`135`、`331`、`313`，答案为 $f($`333`$) \times f($`331`$) \times f($`313`$) \times f($`135`$) = 0 \times 1 \times 1 \times 1 = 0$。


#### 样例 2



#### 输入

```plain
2 10
6 6
3 666666 1
1 1 2
3 666666 2
3 666666 4
3 666666666666666666666666666666 1
2 1
1 2 1
3 666666 2
3 666666 4
3 666666666666666666666666666666 1

```



#### 输出

```plain
64
1
0
75497471
1
0
75497471

```


#### 解释

对于第四次、第七次询问，输入的 $s$ 为 30 个字符`6`，所有 $f(t)$ 的乘积是 $2^{30} = 1073741824$，输出的结果是这个数对于998244353取模的结果。

#### 样例3

见附加文件下的 *ex_3.in* 与 *ex_3.ans*。

该组样例的数据范围同第5个测试点。

#### 样例4

见附加文件下的 *ex_4.in* 与 *ex_4.ans*。

该组样例的数据范围同第10个测试点。

#### 样例5

见附加文件下的 *ex_5.in* 与 *ex_5.ans*。

该组样例的数据范围同第15个测试点。

#### 样例6

见附加文件下的 *ex_6.in* 与 *ex_6.ans*。

该组样例的数据范围同第20个测试点。


# 数据范围与提示

保证 $n \leq 2 \times 10^{5}$，$m \leq 5 \times 10^{5}$，$k \leq 50$ 。

设 $\sum |s|$ 为某个输入文件中所有询问的 $s$ 的长度总和，则 $\sum |s| \leq 10^{7}$  。

设 $c$ 为某个输入文件中形如`2` $i$的操作的次数，则 $c \leq 10^{3}$ 。

每个测试点的详细信息见下表：

  <!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n$ | $m$ | $k$ | $\sum \|s\|$ | $c$ | 全为$\texttt{1}$ |
|-|-|-|-|-|-|-|
| 1 | $=1$ | $\leq 10^{3}$ | $=1$ | $\leq 10^{3}$ | $=0$ | No |
| 2 | $\leq 20$ | $\leq 40$ | $\leq 10$ | $\leq 10^{3}$ | $=0$ | No |
| 3 | $\leq 150$ | $\leq 2,000$ | $\leq 50$ | $\leq 10^{3}$ | $\leq 10^{3}$ | No |
| 4 | $\leq 500$ | $\leq 600$ | $\leq 50$ | $\leq 10^{3}$ | $=0$ | No |
| 5 | $\leq 10^{3}$ | $\leq 2,000$ | $\leq 50$ | $\leq 10^{3}$ | $\leq 10^{3}$ | No |
| 6 | $\leq 5 \times 10^{4}$ | $\leq 6 \times 10^{4}$ | $\leq 5$ | $\leq 5 \times 10^{4}$ | $\leq 10^{3}$ | No |
| 7 | $\leq 5 \times 10^{4}$ | $\leq 6 \times 10^{4}$ | $\leq 50$ | $\leq 5 \times 10^{4}$ | $=0$ | Yes |
| 8 | $\leq 5 \times 10^{4}$ | $\leq 6 \times 10^{4}$ | $\leq 50$ | $\leq 5 \times 10^{4}$ | $=0$ | No |
| 9 | $\leq 5 \times 10^{4}$ | $\leq 6 \times 10^{4}$ | $\leq 50$ | $\leq 5 \times 10^{4}$ | $\leq 10^{3}$ | No |
| 10 | $\leq 5 \times 10^{4}$ | $\leq 8 \times 10^{4}$ | $\leq 50$ | $\leq 2.5 \times 10^{6}$ | $=0$ | No |
| 11 | $\leq 5 \times 10^{4}$ | $\leq 8 \times 10^{4}$ | $\leq 50$ | $\leq 2.5 \times 10^{6}$ | $\leq 10^{3}$ | No |
| 12 | $\leq 10^{5}$ | $\leq 1.1 \times 10^{5}$ | $\leq 6$ | $\leq 10^{5}$ | $\leq 10^{3}$ | No |
| 13 | $\leq 10^{5}$ | $\leq 1.1 \times 10^{5}$ | $\leq 50$ | $\leq 10^{5}$ | $=0$ | Yes |
| 14 | $\leq 10^{5}$ | $\leq 1.1 \times 10^{5}$ | $\leq 50$ | $\leq 10^{5}$ | $=0$ | No |
| 15 | $\leq 10^{5}$ | $\leq 1.1 \times 10^{5}$ | $\leq 50$ | $\leq 10^{5}$ | $\leq 10^{3}$ | No |
| 16 | $\leq 10^{5}$ | $\leq 1.5 \times 10^{5}$ | $\leq 50$ | $\leq 5 \times 10^{6}$ | $=0$ | No |
| 17 | $\leq 10^{5}$ | $\leq 1.5 \times 10^{5}$ | $\leq 50$ | $\leq 5 \times 10^{6}$ | $\leq 10^{3}$ | No |
| 18 | $\leq 2 \times 10^{5}$ | $\leq 5 \times 10^{5}$ | $=1$ | $\leq 10^{7}$ | $=0$ | No |
| 19 | $\leq 2 \times 10^{5}$ | $\leq 5 \times 10^{5}$ | $=1$ | $\leq 10^{7}$ | $\leq 10^{3}$ | No |
| 20 | $\leq 2 \times 10^{5}$ | $\leq 2.5 \times 10^{5}$ | $\leq 7$ | $\leq 2 \times 10^{5}$ | $\leq 10^{3}$ | No |
| 21 | $\leq 2 \times 10^{5}$ | $\leq 2.5 \times 10^{5}$ | $\leq 50$ | $\leq 2 \times 10^{5}$ | $=0$ | Yes |
| 22 | $\leq 2 \times 10^{5}$ | $\leq 2.5 \times 10^{5}$ | $\leq 50$ | $\leq 2 \times 10^{5}$ | $=0$ | No |
| 23 | $\leq 2 \times 10^{5}$ | $\leq 2.5 \times 10^{5}$ | $\leq 50$ | $\leq 2 \times 10^{5}$ | $\leq 10^{3}$ | No |
| 24 | $\leq 2 \times 10^{5}$ | $\leq 3 \times 10^{5}$ | $\leq 50$ | $\leq 10^{7}$ | $=0$ | No |
| 25 | $\leq 2 \times 10^{5}$ | $\leq 3 \times 10^{5}$ | $\leq 50$ | $\leq 10^{7}$ | $\leq 10^{3}$ | No |

<!-- Migrated from original HTML table:
<table class="ui celled center aligned table">  <thead>  <tr>  <th rowspan="1"> 测试点编号 </th>  <th rowspan="1"> $n$ </th>  <th rowspan="1"> $m$ </th>  <th rowspan="1"> $k$ </th>  <th rowspan="1"> $\sum |s|$ </th>  <th rowspan="1"> $c$ </th>  <th rowspan="1"> 全为$\texttt{1}$ </th>  </tr>  </thead>  <tbody>  <tr>  <td rowspan="1"> 1 </td>  <td rowspan="1"> $=1$ </td>  <td rowspan="1"> $\leq 10^{3}$ </td>  <td rowspan="1"> $=1$ </td>  <td rowspan="5"> $\leq 10^{3}$ </td>  <td rowspan="2"> $=0$ </td>  <td rowspan="6"> No </td>  </tr>  <tr>  <td rowspan="1"> 2 </td>  <td rowspan="1"> $\leq 20$ </td>  <td rowspan="1"> $\leq 40$ </td>  <td rowspan="1"> $\leq 10$ </td>  </tr>  <tr>  <td rowspan="1"> 3 </td>  <td rowspan="1"> $\leq 150$ </td>  <td rowspan="1"> $\leq 2,000$ </td>  <td rowspan="3"> $\leq 50$ </td>  <td rowspan="1"> $\leq 10^{3}$ </td>  </tr>  <tr>  <td rowspan="1"> 4 </td>  <td rowspan="1"> $\leq 500$ </td>  <td rowspan="1"> $\leq 600$ </td>  <td rowspan="1"> $=0$ </td>  </tr>  <tr>  <td rowspan="1"> 5 </td>  <td rowspan="1"> $\leq 10^{3}$ </td>  <td rowspan="1"> $\leq 2,000$ </td>  <td rowspan="2"> $\leq 10^{3}$ </td>  </tr>  <tr>  <td rowspan="1"> 6 </td>  <td rowspan="6"> $\leq 5 \times 10^{4}$ </td>  <td rowspan="4"> $\leq 6 \times 10^{4}$ </td>  <td rowspan="1"> $\leq 5$ </td>  <td rowspan="4"> $\leq 5 \times 10^{4}$ </td>  </tr>  <tr>  <td rowspan="1"> 7 </td>  <td rowspan="5"> $\leq 50$ </td>  <td rowspan="2"> $=0$ </td>  <td rowspan="1"> Yes </td>  </tr>  <tr>  <td rowspan="1"> 8 </td>  <td rowspan="5"> No </td>  </tr>  <tr>  <td rowspan="1"> 9 </td>  <td rowspan="1"> $\leq 10^{3}$ </td>  </tr>  <tr>  <td rowspan="1"> 10 </td>  <td rowspan="2"> $\leq 8 \times 10^{4}$ </td>  <td rowspan="2"> $\leq 2.5 \times 10^{6}$ </td>  <td rowspan="1"> $=0$ </td>  </tr>  <tr>  <td rowspan="1"> 11 </td>  <td rowspan="2"> $\leq 10^{3}$ </td>  </tr>  <tr>  <td rowspan="1"> 12 </td>  <td rowspan="6"> $\leq 10^{5}$ </td>  <td rowspan="4"> $\leq 1.1 \times 10^{5}$ </td>  <td rowspan="1"> $\leq 6$ </td>  <td rowspan="4"> $\leq 10^{5}$ </td>  </tr>  <tr>  <td rowspan="1"> 13 </td>  <td rowspan="5"> $\leq 50$ </td>  <td rowspan="2"> $=0$ </td>  <td rowspan="1"> Yes </td>  </tr>  <tr>  <td rowspan="1"> 14 </td>  <td rowspan="7"> No </td>  </tr>  <tr>  <td rowspan="1"> 15 </td>  <td rowspan="1"> $\leq 10^{3}$ </td>  </tr>  <tr>  <td rowspan="1"> 16 </td>  <td rowspan="2"> $\leq 1.5 \times 10^{5}$ </td>  <td rowspan="2"> $\leq 5 \times 10^{6}$ </td>  <td rowspan="1"> $=0$ </td>  </tr>  <tr>  <td rowspan="1"> 17 </td>  <td rowspan="1"> $\leq 10^{3}$ </td>  </tr>  <tr>  <td rowspan="1"> 18 </td>  <td rowspan="8"> $\leq 2 \times 10^{5}$ </td>  <td rowspan="2"> $\leq 5 \times 10^{5}$ </td>  <td rowspan="2"> $=1$ </td>  <td rowspan="2"> $\leq 10^{7}$ </td>  <td rowspan="1"> $=0$ </td>  </tr>  <tr>  <td rowspan="1"> 19 </td>  <td rowspan="2"> $\leq 10^{3}$ </td>  </tr>  <tr>  <td rowspan="1"> 20 </td>  <td rowspan="4"> $\leq 2.5 \times 10^{5}$ </td>  <td rowspan="1"> $\leq 7$ </td>  <td rowspan="4"> $\leq 2 \times 10^{5}$ </td>  </tr>  <tr>  <td rowspan="1"> 21 </td>  <td rowspan="5"> $\leq 50$ </td>  <td rowspan="2"> $=0$ </td>  <td rowspan="1"> Yes </td>  </tr>  <tr>  <td rowspan="1"> 22 </td>  <td rowspan="4"> No </td>  </tr>  <tr>  <td rowspan="1"> 23 </td>  <td rowspan="1"> $\leq 10^{3}$ </td>  </tr>  <tr>  <td rowspan="1"> 24 </td>  <td rowspan="2"> $\leq 3 \times 10^{5}$ </td>  <td rowspan="2"> $\leq 10^{7}$ </td>  <td rowspan="1"> $=0$ </td>  </tr>  <tr>  <td rowspan="1"> 25 </td>  <td rowspan="1"> $\leq 10^{3}$ </td>  </tr>  </tbody>  </table>
-->

<!-- END: Migrated markdown table -->  
如果一个测试点的“全为`1`”的一列为“Yes”，表示该测试点的所有蚯蚓的长度均为1，并且所有询问串$s$的每一位也均为`1`。

