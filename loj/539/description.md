
# 题目描述

T 城是一个旅游城市，具有 $n$ 个景点和 $m$ 条道路，所有景点编号为 $1,2,...,n$。每条道路连接这 $n$ 个景区中的某两个景区，道路是**单向通行**的。每条道路都有一个长度。

为了方便旅游，每个景点都有一个加油站。第 $i$ 个景点的加油站的费用为 $p_i$，加油量为 $c_i$。若汽车在第 $i$ 个景点加油，则需要花费 $p_i$ 元钱，之后车的油量将**被加至**油量上限与 $c_i$ 中的较小值。不过如果加油前汽车油量已经不小于 $c_i$，则不能在该景点加油。

小 C 准备来到 T 城旅游。他的汽车油量上限为 $C$。旅游开始时，汽车的油量为 $0$。在旅游过程中：

1、当汽车油量大于 $0$ 时，汽车可以沿从当前景区出发的任意一条道路**到达**另一个景点（不能只走道路的一部分），汽车油量将减少 $1$；

2、当汽车在景点 $i$ 且当前油量小于 $c_i$ 时，汽车可以在当前景点加油，加油需花费 $p_i$ 元钱，这样汽车油量将变为 $\min\{c_i,C\}$。

一次旅游的总花费等于每次加油的花费之和，旅游的总路程等于每次经过道路的长度之和。注意多次在同一景点加油，费用也要计算多次，同样地，多次经过同一条道路，路程也要计算多次。

小 C 计划旅游 $T$ 次，每次旅游前，小 C 都指定了该次旅游的起点和目标路程。由于行程不同，每次出发前带的钱也不同。为了省钱，小 C 需要在旅游前先规划好旅游路线（包括旅游的路径和加油的方案），使得从起点出发，按照该旅游路线旅游结束后总路程不小于目标路程，且剩下的钱尽可能多。请你规划最优旅游路线，计算这 $T$ 次旅游每次结束后最多可以剩下多少钱。

# 输入格式

输入第一行包含四个正整数 $n$，$m$，$C$，$T$，每两个整数之间用一个空格隔开，分别表示景点数、道路数、汽车油量上限和旅行次数。

接下来 $n$ 行，每行包含两个正整数 $p_i$，$c_i$，每两个整数之间用一个空格隔开，按编号顺序依次表示编号为 $1,2,...,n$ 的景点的费用和油量。

接下来 $m$ 行，每行包含三个正整数 $a_i$，$b_i$，$l_i$，每两个整数之间用一个空格隔开，表示一条从编号为 $a_i$ 的景点到编号为 $b_i$ 的景点的道路，道路的长度为 $l_i$。保证 $a_i\ne b_i$，但从一个景点到另一个景点可能有多条道路。

最后 $T$ 行，每行包含三个正整数 $s_i$，$q_i$，$d_i$，描述一次旅游计划，旅游的起点为编号为 $s_i$ 的景点，出发时带了 $q_i$ 元钱，目标路程为 $d_i$。

# 输出格式

输出 $T$ 行，每行一个整数，第 $i$ 行的整数表示第 $i$ 次旅游结束后最多剩下多少元钱。如果旅游无法完成，也就是说不存在从景点 $s_i$ 出发用不超过 $q_i$ 元钱经过不小于 $d_i$ 的路程的路线，则该行输出 $-1$。

# 样例

#### 样例输入 1
```plain
6 6 3 2
4 1
6 2
2 1
8 1
5 4
9 1
1 2 1
1 3 1
2 4 1
3 5 1
4 6 1
5 6 1
1 12 3
1 9 3
```

#### 样例输出 1
```plain
2
-1
```

#### 样例解释

T 城的景区和道路如下图所示：

![](source/loj/539/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTEvMDMvNTlmYmMwYTQxY2U1Mi5wbmc=.png)

由图可知，从景点 $1$ 出发，路程为 $3$ 的路线有两条：$1\rightarrow 2\rightarrow 4\rightarrow 6$ 和 $1\rightarrow 3\rightarrow 5\rightarrow 6$。

第 $1$ 次旅游，最优路线为先在景点 $1$ 加油，花费 $4$ 元，此时油量为 $1$，然后到景点 $2$，此时油量为 $0$，在景点 $2$ 加油，花费 $6$ 元，此时油量为 $2$，接着到景点 $4$，此时油量为 $1$，最后到景点 $6$，总路程为 $3$，最后剩余 $12-4-6=2$ 元。

第 $2$ 次旅游，只用 $9$ 元无论如何也无法走 $3$ 的路程，因此旅游无法完成。

#### 样例 2

见附加文件（在页面上方下载）中的选手目录下的 `trip2.in` 与 `trip2.ans`。

# 数据范围与提示

所有测试数据的范围和特点如下表所示：

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n$ | $m$ | $C$ | $T$ | $p_i, \ c_i$ | 特殊性质 |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| 1 | $\le 10$ | $=n-1$ | $\le 10$ | $=1$ | $\le 10$ | 1, 2 |
| 2 | $\le 10$ | $=n-1$ | $\le 10$ | $\le 10$ | $\le 10$ | 1, 2 |
| 3 | $\le 10$ | $=n-1$ | $\le 10$ | $\le 10$ | $\le 10$ | 1, 2 |
| 4 | $\le 10$ | $=n-1$ | $\le 10$ | $\le 10$ | $\le 10$ | 1, 2 |
| 5 | $=10$ | $=10$ | $\le 10$ | $\le 10$ | $\le 10$ | 2 |
| 6 | $=15$ | $=15$ | $\le 10$ | $\le 20$ | $\le 10$ | 2 |
| 7 | $=20$ | $=20$ | $\le 10$ | $\le 20$ | $\le 10$ | 2 |
| 8 | $\le 100$ | $=n-1$ | $\le 10^3$ | $\le 50$ | $\le 100$ | 1, 3 |
| 9 | $\le 100$ | $=n-1$ | $\le 10^3$ | $\le 50$ | $\le 100$ | 1, 3 |
| 10 | $\le 100$ | $=n-1$ | $\le 10^3$ | $\le 50$ | $\le 100$ | 1, 3 |
| 11 | $\le 40$ | $\le 400$ | $\le 10^3$ | $\le 50$ | $\le 100$ | 3 |
| 12 | $\le 40$ | $\le 400$ | $\le 10^3$ | $\le 50$ | $\le 100$ | 3 |
| 13 | $\le 60$ | $\le 600$ | $\le 10^3$ | $\le 50$ | $\le 10^3$ | 无 |
| 14 | $\le 60$ | $\le 600$ | $\le 10^3$ | $\le 50$ | $\le 10^3$ | 无 |
| 15 | $\le 80$ | $\le 800$ | $\le 10^3$ | $\le 50$ | $\le 10^3$ | 无 |
| 16 | $\le 80$ | $\le 800$ | $\le 10^5$ | $\le 10^3$ | $\le 10^5$ | 无 |
| 17 | $\le 90$ | $\le 900$ | $\le 10^5$ | $\le 10^3$ | $\le 10^5$ | 无 |
| 18 | $\le 90$ | $\le 900$ | $\le 10^5$ | $\le 10^3$ | $\le 10^5$ | 无 |
| 19 | $\le 100$ | $\le 1000$ | $\le 10^5$ | $\le 10^3$ | $\le 10^5$ | 无 |
| 20 | $\le 100$ | $\le 1000$ | $\le 10^5$ | $\le 10^5$ | $\le 10^5$ | 无 |

<!-- Migrated from original HTML table:
<table class='ui table'>
    <thead>
        <tr>
            <th style='text-align: center'> 测试点编号 </th>
            <th style='text-align: center'> $n$ </th>
            <th style='text-align: center'> $m$ </th>
            <th style='text-align: center'> $C$ </th>
            <th style='text-align: center'> $T$ </th>
            <th style='text-align: center'> $p_i, \ c_i$ </th>
            <th style='text-align: center'> 特殊性质 </th>
        </tr>
    </thead>
    <tbody>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 1 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='4'> $\le 10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='4'> $=n-1$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='7'> $\le 10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $=1$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='7'> $\le 10$ </td>
            <td style='text-align: center' rowspan='4'> 1, 2 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 2 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='4'> $\le 10$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 3 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 4 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 5 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $=10$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $=10$ </td>
            <td style='text-align: center' rowspan='3'> 2 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 6 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $=15$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $=15$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 20$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 7 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $=20$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $=20$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 8 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> $\le 100$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> $=n-1$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='8'> $\le 10^3$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='8'> $\le 50$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='5'> $\le 100$ </td>
            <td style='text-align: center' rowspan='3'> 1, 3 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 9 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 10 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 11 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 40$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 400$ </td>
            <td style='text-align: center' rowspan='2'> 3 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 12 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 13 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 60$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 600$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> $\le 10^3$ </td>
            <td style='text-align: center' rowspan='8'> 无 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 14 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 15 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 80$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 800$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 16 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='5'> $\le 10^5$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='4'> $\le 10^3$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='5'> $\le 10^5$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 17 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 90$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 900$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 18 </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 19 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 100$ </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 1000$ </td>
    	</tr>
    	<tr>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> 20 </td>
            <td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 10^5$ </td>
    	</tr>
    </tbody>
</table>
-->

<!-- END: Migrated markdown table -->

其中，“特殊性质”一列中的数字意义如下：

* 特殊性质 1：所有 $a_i=i$，$b_i=i+1$，$l_i=1$。

* 特殊性质 2：所有 $d_i\le 10^3$。

* 特殊性质 3：所有 $q_i\le 100$。

对于所有数据，$2\le n\le 100$，$1\le m\le 1000$，$1\le C,T\le 10^5$，$1\le a_i,b_i,l_i\le n$，$1\le p_i,c_i\le 10^5$，$1\le s_i\le n$，$1\le q_i\le n^2$，$1\le d_i\le 10^9$。

