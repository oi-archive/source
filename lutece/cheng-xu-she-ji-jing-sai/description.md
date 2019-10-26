
# Content

“你动规无力，图论不稳，数据结构松散，贪心迟钝，没一样像样的，就你还想和我同台竞技，做你的美梦！今天这场比赛，就是要让你知道你是多么的无能！！”

不训练，无以为战。有$n$项能力是`ACM`竞赛要求的，训练则能提升，忽略则会荒废。

这$m$天，你能做到如何。

# Standard Input

第一行两个整数$n$，$m$,分别表示有$n$项能力要求，共有$m$天。

第二行$n$个整数，第$i$个整数$a\_i$表示第$i$项能力的数值。

接下来$m$行，每行开始先读入一个整数$s\_i$，表明这是一次询问还是一次能力变化。

$s\_i = 0$，表明这是一次询问，然后读入两个整数$l\_i,r\_i$，表示询问在$[l\_i，r\_i]$区间中任选一段连续序列，这段序列中所有能力值之和最大能是多少。

$s\_i = 1$，表明这是一次能力变化，然后读入两个整数$x\_i, w\_i$，表示第$x\_i$项能力变为了$w\_i$。

$1 \leq n,m \leq 100000,-10000 \leq a\_i \leq 10000,1 \leq l\_i \leq r\_i \leq n, 1 \leq x\_i \leq n,-10000 \leq w\_i \leq 10000$

# Standard Output

有多少询问就输出多少行，每行输出一个整数，作为对该询问的回答。

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
<tr><td>4 4
1 2 3 4
0 1 3
1 3 -3
0 2 4
0 3 3</td><td>6
4
-3</td></tr></table>


# Constraints



# Note



# Source


