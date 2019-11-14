
# Content

M大爷和E大爷觉得比口算能力并不展现其真正的技术，只有策略类游戏才能展现真正的实力。他们将n个题库编号1-n，按顺序摆在他们面前，每个题库中有ai个题目。每个大爷轮流切题，每次选择三个题库i,j,k，其中i<j<=k。从i题库中取出一道题并切掉，在j和k题库中分别加入一个题目，如果轮到某位大爷时没有题目能切，那么他就输了。M大爷和E大爷都觉得先手有必胜策略。两人争执不下谁先手，你作为裁判，需要知道先手是不是有必胜策略，但你没有大爷们厉害，所以你需要编写个代码去计算是否有必胜策略。大爷们每一步都会采用最优策略。同时你还需要去回答必胜策略中先手第一步有多少种取法。不同的三元组（i,j,k）视为不同的方案。

# Standard Input

第一行输入一个整数n，表示有n个瓶子在桌上。
第二行输入n个整数，表示每个题库中的题目数量。

# Standard Output

第一行输出YES/NO，表示先手是否有必胜策略。
如果第一行是YES，第二行也输出一个整数，表示先手必胜的第一步方案数。

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
<tr><td>4
1 0 1 5000
</td><td>YES
1
</td></tr></table>


# Constraints



# Note

1<n<=21
0<=a[i]<=10000

# Source


