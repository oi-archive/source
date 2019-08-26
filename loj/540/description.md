
# 题目描述

小 L 计划进行 $n$ 场游戏，每场游戏使用一张地图，小 L 会同时使用三辆车在该地图上完成游戏。

小 L 的赛车有三辆，分别用大写字母 A、B、C 表示。地图是一张无向简单图（没有重边或自环），每次他会在地图中选择不同的三个点 $i$，$j$，$k$，满足 $i<j<k$，且两两之间均有边。此时他会让 A 从 $i$ 到 $j$ ，B 从 $j$ 到 $k$，C从 $k$ 到 $i$，完成一场游戏。他记得有一张地图使得他恰好能完成 $n$ 场不同的游戏，且这个地图顶点数不超过 $500$，请你帮他找到这张地图。

有时候小 $L$ 会记得地图的一些特点，他会把这些告诉你以帮助你找到地图。

也就是说，给一个正整数 $n$，请你构造一个无向简单图使得其三元环个数为 $n$。

# 输入格式

输入第一行一个正整数 $n$。

# 输出格式

输出第一行一个正整数 $x$ 表示地图中点的个数。满足 $1\le x\le 500$。  
接下来输出你找到的地图的上三角邻接矩阵。具体来说格式如下：  
这部分一共输出 $x-1$ 行，其中第 $i$ 行共 $x-i$ 个数，第 $i$ 行第 $j$ 个数表示点 $i$ 和点 $i+j$ 是否有边，只能为 $0$ 或 $1$：为 $1$ 表示有，为 $0$ 表示没有。

检验你的输出时，我们读取 $x$ 之后的 $\frac{x(x-1)}{2}$ 个整数，多余的空白或输出将被忽略。

# 样例

#### 样例输入 1
```plain
3
```

#### 样例输出 1
```plain
5
1 0 1 0
1 1 1
0 1
1
```

#### 样例解释 1
样例输出描述的图如下：  
![](/problem/1/testdata/download/p1.png)

#### 更多样例
请从页面上方的附加文件处下载。


# 数据范围与提示

对于所有数据，$1\le n\le 2\times 10^6$。

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n$ 的限制 | 特殊限制 |
|:-:|:-:|:-:|
| 1 | $\le 10$ | - |
| 2 | $\le 20$ | - |
| 3 | $\le 30$ | - |
| 4 | $\le 100$ | - |
| 5 | $\le 100$ | - |
| 6 | $\le 200$ | - |
| 7 | $\le 400$ | - |
| 8 | $\le 1000$ | - |
| 9 | $\le 1000$ | - |
| 10 | $\le 3000$ | - |
| 11 | $\le 10^4$ | - |
| 12 | $\le 10^4$ | - |
| 13 | $\le 3\times 10^4$ | - |
| 14 | $\le 10^5$ | - |
| 15 | $\le 3\times 10^5$ | - |
| 16 | $\le 10^6$ | $n$ 是某个正整数的立方 |
| 17 | $\le 10^6$ | 存在一个完全图满足条件 |
| 18 | $\le 10^6$ | - |
| 19 | $\le 1.5\times 10^6$ | - |
| 20 | $\le 2\times 10^6$ | - |

<!-- Migrated from original HTML table:
<table class='ui table'>
	<thead>
		<tr>
			<th style='text-align: center'> 测试点编号 </th>
			<th style='text-align: center'> $n$ 的限制 </th>
			<th style='text-align: center'> 特殊限制 </th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>1</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 10$ </td>
			<td style='text-align: center' rowspan='15'> - </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>2</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 20$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>3</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 30$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>4</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 100$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>5</td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>6</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 200$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>7</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 400$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>8</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 1000$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>9</td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>10</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 3000$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>11</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> $\le 10^4$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>12</td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>13</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 3\times 10^4$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>14</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 10^5$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>15</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 3\times 10^5$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>16</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> $\le 10^6$ </td>
			<td style='text-align: center'> $n$ 是某个正整数的立方 </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>17</td>
			<td style='text-align: center'> 存在一个完全图满足条件 </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>18</td>
			<td style='text-align: center' rowspan='3'> - </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>19</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 1.5\times 10^6$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>20</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $\le 2\times 10^6$ </td>
		</tr>
	</tbody>
</table>
-->

<!-- END: Migrated markdown table -->

