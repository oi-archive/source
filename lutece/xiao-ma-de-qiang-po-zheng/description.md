
# Content

小马跟坏小兔子学坏了，因为小马现在也会在上课的时候选择摸鱼。

今天上课，小马自己发现了一款神奇的游戏。

这款游戏会给你 $n$ 个带有编号的方块，编号为 $1,2,\cdots,n$，每个方块的编号各不相同。

但是方块的初始顺序是不确定的，这让有强迫症的小马很恼火。(╯▔皿▔)╯

有强迫症的小马希望在最短时间内将方块重新排列成升序（即 $1,2,\cdots,n$ ）。

小马可以进行如下两种操作：

1. 选择其中一个方块，并把它放在任意位置。
2. 选择 $k(k>1)$ 个位置连续的方块，并把它们放在任意位置。

每次操作都要花费 1s 时间，请你帮小马计算，最快多长时间能将这些方块排列好。

# Standard Input

第一行输入一个数 $n$，表示一共有 $n$ 个方块。
第二行有 $n$ 个数，第 $i$ 个数 $a_i$ 表示第 $i$ 个方块的标号。

# Standard Output

输出一个数，表示答案。

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
<tr><td>2
1 2</td><td>0</td></tr><tr><td>4
1 3 4 2</td><td>1</td></tr></table>


# Constraints

$1 \leq n \leq 9$
$a_1, a_2, \ldots, a_n$ 为 $1$ 到 $n$ 的一种排列。

# Note

样例 2 解释：
小马既可以选择第一种方式，即选择 $2$ 号方块，并把它放在 $1$ 和 $3$ 之间，总共耗费 1s。
也可以选择第二种方式，即选择连续的 $3,4$ 号方块，并把它们按之前的顺序放在 $2$ 的后面，总共耗费 1s。

# Source


