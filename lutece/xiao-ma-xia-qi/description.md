
# Content

小狗在讲 DP 专题的时候，小马和小兔子听不懂，于是便开始摸鱼。

小马在应用商店里找到一款游戏，游戏规则如下：
有一块 $n×n$ 的棋盘，第 $i$ 行第 $i$ 个格子上的有数字 $a_{ij}$，游戏共有 $k$ 个回合，每一回合游戏双方依次选择一块 $2×2$ 的区域（不能超出棋盘），这个区域的数字之和会计入总分，并逆时针旋转 $90$ 度。

如：
$1\ 2\ 3\ \ \ \ \to \ \ \ \ 2\ 5\ 3\\ 4\ 5\ 6\ \ \ \ \to \ \ \ \ 1\ 4\ 6\\ 7\ 8\ 9\ \ \ \ \to \ \ \ \ 7\ 8\ 9$
(这是一个 $3\times 3$ 的棋盘，若选择左上角的 $2\times 2$ 区域，获得 $12$ 分，并逆时针旋转 $90$ 度)

在此游戏中小马的目标是使总分数最大，小兔子的目标是使总分数最小，假如小马和小兔子都采用最佳策略的话，现在小马先手，求所得到的总分数。

# Standard Input

第一行两个数 $n$，$k$。
接下来 $n$  行，每一行有 $n$ 个数。

# Standard Output

输出一个整数，代表得到的总分数。

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
<tr><td>3 1
1 1 1
1 9 9
1 9 9</td><td>48</td></tr></table>


# Constraints

$2 \leq n \leq 5$
$1 \leq k \leq 4$
$1 \leq a_{ij} \leq 1000$

# Note



# Source


