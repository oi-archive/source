
# 题目描述

曾经有一款流行的游戏，叫做 ***Infinity Loop***，先来简单的介绍一下这个游戏:    

游戏在一个 $n \times m$ 的网格状棋盘上进行，其中有些小方格中会有水管，水管可能在方格某些方向的边界的中点有接口，所有水管的粗细都相同，所以如果两个相邻方格的公共边界的中点都有接头，那么可以看作这两个接头互相连接。水管有以下 $15$ 种形状：

<img width = 39% src="source/loj/2321/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMDQvNWEyNTIwNDVkYzU3Zi5wbmc=.png" alt="Screen Shot 2017-12-04 at 18.13.48.png" title="Screen Shot 2017-12-04 at 18.13.48.png" />
<img width = 40% src="source/loj/2321/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMTIvMDQvNWEyNTIwNDYzODQ3Ni5wbmc=.png" alt="Screen Shot 2017-12-04 at 18.13.55.png" title="Screen Shot 2017-12-04 at 18.13.55.png" />

游戏开始时，棋盘中水管可能存在漏水的地方。  

形式化地:如果存在某个接头，没有和其它接头相连接，那么它就是一个漏水的地方。  

玩家可以进行一种操作：选定一个含有**非直线型**水管的方格，将其中的水管绕方格中心顺时针或逆时针旋转 $90$ 度。  

直线型水管是指左图里中间一行的两种水管。  

现给出一个初始局面，请问最少进行多少次操作可以使棋盘上不存在漏水的地方。




# 输入格式

第一行两个正整数 $n,m$，代表网格的大小。  

接下来 $n$ 行每行 $m$ 个数，每个数是 $[0,15]$ 中的一个，你可以将其看作一个 $4$ 位的二进制数，从低到高每一位分别代表初始局面中这个格子上、右、下、左方向上是否有 水管接头。  

特别地，如果这个数是 $0$，则意味着这个位置没有水管。  

比如 $3(0011_{(2)})$ 代表上和右有接头，也就是一个 L 型，而 $12(1100_{(2)})$ 代表下和左有接头，也就是将 L 型旋转 $180$ 度。

# 输出格式

输出共一行，表示最少操作次数。如果无法达成目标，输出 $-1$.


# 样例

#### 样例输入 1
```plain 
2 3
3 14 12
3 11 12
```

#### 样例输出 1
```plain 
2 
```

#### 样例输入 2
```plain 
3 2 
1 8 
5 10 
2 4
```

#### 样例输出 2
```plain 
-1
```
#### 样例输入 3
```plain 
3 3
9 11 3
13 15 7 
12 14 6
```

#### 样例输出 3
```plain 
16
```

# 数据范围与提示

<!-- BEGIN: Migrated markdown table -->

| 测试点编号 | $n\times m$ 的范围 | 特殊约定 |
|:-:|:-:|:-:|
| 1 | $n\times m \le 16$ | 无特殊要求 |
| 2 | $n\times m \le 16$ | 无特殊要求 |
| 3 | $n \times m \le 2000$ | $\min(n,m) \le 15$ |
| 4 | $n \times m \le 2000$ | $\min(n,m) \le 15$ |
| 5 | $n \times m \le 2000$ | $\min(n,m) \le 15$ |
| 6 | $n \times m \le 2000$ | $\min(n,m) \le 15$ |
| 7 | $n \times m \le 2000$ | $\min(n,m) \le 15$ |
| 8 | $n \times m \le 2000$ | $\min(n,m) \le 15$ |
| 9 | $n \times m \le 2000$ | 无特殊要求 |
| 10 | $n \times m \le 2000$ | 无特殊要求 |
| 11 | $n \times m \le 2000$ | 无特殊要求 |
| 12 | $n \times m \le 2000$ | 无特殊要求 |
| 13 | $n \times m \le 2000$ | 无特殊要求 |
| 14 | $n \times m \le 2000$ | 无特殊要求 |
| 15 | $n \times m \le 2000$ | 无特殊要求 |
| 16 | $n \times m \le 2000$ | 无特殊要求 |
| 17 | $n \times m \le 2000$ | 无特殊要求 |
| 18 | $n \times m \le 2000$ | 无特殊要求 |
| 19 | $n \times m \le 2000$ | 无特殊要求 |
| 20 | $n \times m \le 2000$ | 无特殊要求 |

<!-- Migrated from original HTML table:
<table><thead>
<tr>
<th style='text-align:center'>测试点编号</th><th style='text-align:center'>$n\times m$ 的范围</th><th style='text-align:center'>特殊约定</th></tr>
</thead><tbody>
<tr>
<td style='text-align:center'>1</td><td style='text-align:center' rowspan='2'>$n\times m \le 16$ </td><td style='text-align:center' rowspan='2'>无特殊要求</td></tr>
<tr>
<td style='text-align:center'>2</td></tr>
<tr>
<td style='text-align:center'>3</td><td style='text-align:center' rowspan='18'>$n \times m \le 2000$ </td><td style='text-align:center' rowspan='6'>$\min(n,m) \le 15$ </td></tr>
<tr>
<td style='text-align:center'>4</td></tr>
<tr>
<td style='text-align:center'>5</td></tr>
<tr>
<td style='text-align:center'>6</td></tr>
<tr>
<td style='text-align:center'>7</td></tr>
<tr>
<td style='text-align:center'>8</td></tr>
<tr>
<td style='text-align:center'>9</td><td style='text-align:center' rowspan='12'>无特殊要求</td></tr>
<tr>
<td style='text-align:center'>10</td></tr>
<tr>
<td style='text-align:center'>11</td></tr>
<tr>
<td style='text-align:center'>12</td></tr>
<tr>
<td style='text-align:center'>13</td></tr>
<tr>
<td style='text-align:center'>14</td></tr>
<tr>
<td style='text-align:center'>15</td></tr>
<tr>
<td style='text-align:center'>16</td></tr>
<tr>
<td style='text-align:center'>17</td></tr>
<tr>
<td style='text-align:center'>18</td></tr>
<tr>
<td style='text-align:center'>19</td></tr>
<tr>
<td style='text-align:center'>20</td></tr>
</tbody></table>
-->

<!-- END: Migrated markdown table -->


