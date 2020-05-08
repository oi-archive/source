
# Content

在与拉菲、标枪等人相遇几次之后，綾波心里有些烦恼。一天，她独自在港区玩一个既有趣又能提升自己的能力的游戏，在这个游戏中，她面对一面长墙，墙上排列着 $n$ 个点（编号 $1\sim n$），每个点都带有一个数值（可能为负数），同时，还有一个一定要记住的数值 $k$。

在每一轮游戏中，綾波需要使用鱼雷击中在一个区间（$[l,r]$）内的所有对 $k$ 取模（取**非负最小**剩余）后数值与 $c$ 对 $k$ 取模（同样取**非负最小**剩余）相等的点，每次击中每个点需要一枚鱼雷。

作为港区鱼雷能力最强的驱逐舰，綾波当然不可能因为没有命中而浪费鱼雷。

每轮游戏结束后，该轮目标区间内的所有点的值将增加 $d$（$d$ 可能为负数）。

![PID:80457661](/source/lutece/ling-bo-de-you-xi-i/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvODA0NTc2NjFfcDBfcmVzaXplLnBuZw==.png)

*Pixiv ID: 80457661，Author: 伊奈，使用已经过作者授权。*

尽管如此，在知道了墙面上各点初始数值和每轮的任务后，綾波还是希望指挥官能帮她计算她各轮需要的鱼雷数量的说。呐，快来帮帮綾波吧。

# Standard Input

第一行，两个整数 $n,\ k$，表示墙面上的点个数和取模时使用的模数。
第二行，$n$ 个整数，依次表示各点的初始数值。
第三行，整数 $m$，表示游戏的轮数。
后面 $m$ 行，每行四个整数 $l$，$r$，$c$，$d$ 表示目标区间 $[l,r]$ 、目标值 $c$、本轮游戏后增加的值 $d$。

# Standard Output

$m$ 行，每行一个整数，表示每轮需要消耗的鱼雷数量。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>5 10
123 2 42 46 -248
3
1 5 2 3
1 5 5 -11
5 5 4 0</td><td>3
3
1</td></tr></table>


# Constraints

$0<n,m,k\leq 10^5$
$1\leq l\le r \leq n$
其他数均在 $int$ 范围内，即 $-2^{31}\leq others < 2^{31}$

# Note

模数取非负最小剩余（大于等于 $0$，小于模数），比如 $-2$ 模 $10$ 要取 $8$。

hint1：请勿滥用 long long
hint2：正解复杂度不带 log

# Source


