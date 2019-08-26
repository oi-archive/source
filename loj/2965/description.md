
# 题目描述

 **译自 [COCI 2010.02](http://hsin.hr/coci/archive/2009_2010/) T6.** ***[PALACINKE](http://hsin.hr/coci/archive/2009_2010/contest4_tasks.pdf)***

安娜有几个同学过来吃可丽饼，然而安娜忘了这事。当安娜发现时，留给她烤可丽饼的时间只剩下 $T$ 分钟了。她马上跑出去采购四样原材料：面粉 `B`，鸡蛋 `J`，牛奶 `M` 和果酱 `P`。

安娜周边有 $N$ 个路口，编号为 $1\ldots N$，还有 $M$ 条单向道路连接它们。已知每条路上的商店会卖哪些材料，保证每条路上的商店至少会卖（上述四种材料中）的一种。

<center><img src="source/loj/2965/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMTIvMzAvNWMyOGQ3N2NiOWJhMS5wbmc=.png" width="200px"/></center>

安娜穿过一条道路时，如果她进入了这条路上的商店（不一定买东西，她可能只是去比比价格），则她通过这条路耗时 $2$ 分钟，否则耗时 $1$ 分钟。

安娜需要在 $T$ 分钟内采购到四种原材料。请问她有多少种「采购方式」，答案对 $5557$ 取模。采购方式包含了她经过的结点的次序，以及她在每条路上买不买材料，但不计她在哪个商店买了什么。例如，当 $T=7$ 时，在上图中有 $5$ 种采购方式：

<table>
<thead>
<tr>
<th>1 min</th>
<th>2 min</th>
<th>3 min</th>
<th>4 min</th>
<th>5 min</th>
<th>6 min</th>
<th>7 min</th>
</tr>
</thead>
<tbody>
<tr>
<td>1→3</td>
<td colspan="2">3→商店→4</td>
<td colspan="2">4→商店→1</td>
<td></td>
<td></td>
</tr>
<tr>
<td colspan="2">1→商店→2</td>
<td colspan="2">2→商店→4</td>
<td colspan="2">4→商店→1</td>
<td></td>
</tr>
<tr>
<td colspan="2">1→商店→3</td>
<td colspan="2">3→商店→4</td>
<td colspan="2">4→商店→1</td>
<td></td>
</tr>
<tr>
<td colspan="2">1→商店→3</td>
<td colspan="2">3→商店→4</td>
<td>4→5</td>
<td colspan="2">5→商店→1</td>
</tr>
<tr>
<td>1→3</td>
<td colspan="2">3→商店→4</td>
<td colspan="2">4→商店→5</td>
<td colspan="2">5→商店→1</td>
</tr>
</tbody>
</table>

# 输入格式

第一行：$N,M$。  
接下来 $N$ 行，每行两个整数 $u,v$ 和一个仅可能包含 `BJMP` 四种字符的字符串 $s$，$u,v$ 表示一条单向道路，$s$ 表示这条道路上的商店会卖哪些材料。保证没有两条单向道路相同（但可能有两条连接的结点相同，而方向相反的道路）。  
第 $N+2$ 行：$T$。

# 输出格式

一行，一个答案，表示安娜有多少种采购方式。

# 样例

#### 样例输入 1
```plain
3 3
1 2 BMJ
2 3 MJP
3 1 JPB
5
```

#### 样例输出 1
```plain
3
```

#### 样例输入 2
```plain
3 4
1 2 B
2 1 P
1 3 J
3 1 M
8
```

#### 样例输出 2
```plain
2
```

#### 样例输入 3
```plain
5 7
1 2 B
2 4 M
1 3 J
3 4 MB
4 1 JP
4 5 J
5 1 P
7
```

#### 样例输出 3
```plain
5
```

# 数据范围与提示

$1\le N\le 25,$ $1\le M\le 500,$ $1\le T\le 10^9$.  
保证没有两条单向道路相同（但可能有两条连接的结点相同，而方向相反的道路）。

