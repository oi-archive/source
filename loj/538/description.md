
# 题目描述

sosusosu 虐爆 OI 之后成为了一名文化课选手。一天，他做作业碰到了一堆数列问题，每道题给出的数列都是以下形式：

> 给定一个下标从 $0$ 开始，无限长的整数列 $\{a_i\},\ i\in \mathbb{N}$，已知 $a_0,a_1$ 的值，以及递推式 $a_{i+2}=k a_{i+1}+a_i,\ i\in\mathbb{N},k\in {\mathbb{N}^+}$。

sosusosu 研究了这些数列，发现它们十分优美充满人类智慧，于是决定出一道 OI 题。

sosusosu 给了你一个集合 $S\subset \mathbb{N}$，他想问你对于 $S$ 中的每个数 $s_i$，使得 $a_{s_i}$ 最大的 $s_i$ 和使得 $a_{s_i}$ 最小的 $s_i$ 分别是多少。如果这样的 $s_i$ 有多个，请你回答最小的一个。

另外，sosusosu 准备对他作业中碰到的每个数列都让你回答一次，不过每次的集合 $S$ 是一样的。

# 输入格式

输入第一行一个整数 $m$ 表示 $S$ 中元素个数。  
第二行 $m$ 个整数 $s_1,s_2,\cdots ,s_m$ 表示 $S$ 中的元素。保证它们是非负整数且严格递增（即 $s_i<s_{i+1}$）。  
第三行一个整数 $n$ 表示询问的数列个数。  
接下来 $n$ 行每行三个整数 $a_0, a_1, k$ 描述一个数列。

# 输出格式

输出共 $n$ 行，每行依次输出两个整数 $\mathrm{maxsi},\mathrm{minsi}$，依次表示 $S$ 的元素 $s_i$ 中，使得 $a_{s_i}$ 最大的 $s_i$ 和使得 $a_{s_i}$ 最小的 $s_i$ 的值。如果这样的 $s_i$ 有多个，请你回答最小的一个。

# 样例

#### 样例输入 1
```plain
8
1 2 3 4 5 6 7 8
2
10 -6 1
0 0 1
```

#### 样例输出 1
```plain
2 1
1 1
```

#### 样例解释 1
第一个数列的前 $9$ 项分别为 $10,-6,4,-2,2,0,2,2,4$，使得 $a_{s_i}$ 最大的 $s_i$ 为 $2$ 和 $8$（$a_2=a_8=4$）其中 $2$ 较小，使得 $a_{s_i}$ 最小的 $s_i$ 为 $1$（$a_1=-6$）。  
第二个数列每项都等于 $0$，因此 $S$ 中的每个元素 $s_i$ 都既使 $a_{s_i}$ 最大也使 $a_{s_i}$ 最小，故答案是 $S$ 中最小元素。

#### 样例输入 2
```plain
3
0 1 2
2
-2 3 1
3 -2 2
```

#### 样例输出 2
```plain
1 0
0 1
```

#### 样例解释 2
第一个数列的前 $4$ 项分别为 $-2,3,1,4$，使得 $a_{s_i}$ 最大的 $s_i$ 为 $1$（$a_1=3$），使得 $a_{s_i}$ 最小的 $s_i$ 为 $0$（$a_0=-2$）。  
第二个数列的前 $4$ 项分别为 $3,-2,-1,-4$，使得 $a_{s_i}$ 最大的 $s_i$ 为 $0$（$a_0=3$），使得 $a_{s_i}$ 最小的 $s_i$ 为 $1$（$a_1=-2$）。  

#### 样例输入 3
```plain
29
2 4 8 16 32 64 128 256 512 1024 2048 4096 8192 16384 32768 65536 131072 262144 524288 1048576 2097152 4194304 8388608 16777216 33554432 67108864 134217728 268435456 536870912
4
10000000 10000000 100
9999984 -6180330 1
9999984 -6180329 1
-10000000 4142135 2
```

#### 样例输出 3
```plain
536870912 2
2 536870912
536870912 16
8 536870912
```

#### 更多样例
见附加文件（在页面上方下载）。其中除了前 3 个样例外还有约定分别和测试点 1, 9, 14 相同的样例各一个。

# 数据范围与提示

对于所有数据，$1\le n\le 3\times 10^5$，$1\le m\le 10^5$，$0\le s_i\le 10^9$，$-10^7\le a_0,a_1\le 10^7$，$1\le k\le 5\times 10^3$，保证 $s_i$ 严格单调递增。

**注意，本题输入规模较大，请使用较快的方式读入。LOJ 上 C 语言的 `scanf`、C++ 的[关闭同步](http://en.cppreference.com/w/cpp/io/ios_base/sync_with_stdio)的 `cin`、Pascal 的 `read` 读入此题数据时间均在 50 ~ 200 毫秒之间。**

所有测试数据的范围和特点如下表所示：  
（未标明的以上述所有数据的限制为准）
<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n,m$ 的限制 | $a_0,a_1,k$ 的范围 | 特殊限制 |
|:-:|:-:|:-:|:-:|
| 1 | $n,m\le 100$ | $-100\le a_0,a_1\le 100,k\le 10$ | $s_m\le 10$ |
| 2 | $n,m\le 100$ | $-100\le a_0,a_1\le 100,k\le 10$ | $s_m\le 10$ |
| 3 | $n,m\le 100$ | $-100\le a_0,a_1\le 100,k\le 10$ | $s_m\le 10$ |
| 4 | $n\le 10^5$ | $k=1$ | - |
| 5 | $n\le 10^5$ | $k=1$ | - |
| 6 | $n\le 10^5$ | $k=1$ | - |
| 7 | $n\le 10^5$ | - | $a_0\cdot a_1\ge 0$（即 $a_0,a_1$ 不会一正一负） |
| 8 | $n\le 10^5$ | - | $\|a_1\|\ge\|a_0\|$ |
| 9 | $n\le 10^5$ | - | $S$ 中元素都是偶数 |
| 10 | $n\le 10^5$ | - | $S$ 中元素都是偶数 |
| 11 | $n\le 10^5$ | - | $S$ 中元素都是偶数 |
| 12 | $n\le 10^5$ | $k\le 10$ | $S$ 中元素都是偶数 |
| 13 | $n\le 10^5$ | $k\le 100$ | $S$ 中元素都是偶数 |
| 14 | $n\le 10^5$ | $k\le 1000$ | - |
| 15 | $n\le 10^5$ | - | - |
| 16 | $n\le 1.5\times 10^5$ | $k\le 10$ | - |
| 17 | $n\le 2\times 10^5$ | $k\le 100$ | - |
| 18 | $n\le 2.5\times 10^5$ | $k\le 1000$ | - |
| 19 | - | - | - |
| 20 | - | - | - |

<!-- Migrated from original HTML table:
<table class='ui table'>
	<thead>
		<tr>
			<th style='text-align: center'> 测试点编号 </th>
			<th style='text-align: center'> $n,m$ 的限制 </th>
			<th style='text-align: center'> $a_0,a_1,k$ 的范围 </th>
			<th style='text-align: center'> 特殊限制 </th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>1</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> $n,m\le 100$ </td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> $-100\le a_0,a_1\le 100,k\le 10$ </td>
			<td style='text-align: center' rowspan='3'> $s_m\le 10$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>2</td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>3</td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>4</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='12'> $n\le 10^5$ </td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='3'> $k=1$ </td>
			<td style='text-align: center' rowspan='3'> - </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>5</td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>6</td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>7</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='5'> - </td>
			<td style='text-align: center'> $a_0\cdot a_1\ge 0$（即 $a_0,a_1$ 不会一正一负） </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>8</td>
			<td style='text-align: center'> $|a_1|\ge|a_0|$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>9</td>
			<td style='text-align: center' rowspan='5'> $S$ 中元素都是偶数 </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>10</td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>11</td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>12</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $k\le 10$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>13</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $k\le 100$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>14</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $k\le 1000$ </td>
			<td style='text-align: center' rowspan='7'> - </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>15</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> - </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>16</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $n\le 1.5\times 10^5$ </td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $k\le 10$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>17</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $n\le 2\times 10^5$ </td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $k\le 100$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>18</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $n\le 2.5\times 10^5$ </td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'> $k\le 1000$ </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>19</td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> - </td>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;' rowspan='2'> - </td>
		</tr>
		<tr>
			<td style='text-align: center; border-right: rgba(34, 36, 38, 0.1) 1px solid;'>20</td>
		</tr>
	</tbody>
</table>
-->

<!-- END: Migrated markdown table -->

