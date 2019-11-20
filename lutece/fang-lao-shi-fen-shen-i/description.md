
# Content

方老师为了开更多讲座，于是他分身了！早上他都在某一个教室分身，然后各个分身分别赶去各个不同的$n$个教室（当然每个教室都要有且只有一个分身）。晚上各个分身都赶回之前分身时的教室，合并成一个人（不需要同时回去）。但是教室间的路十分崎岖，而且是单向的。当然即便只是方老师的分身，那也是相当厉害的，每个分身都会走花费时间最少的路径。方老师想知道他往返走路时间最长的那个分身所花在走路上的时间。题目保证有路可走。

# Standard Input

第一行输入三个整数 $n$, $m$, $x$（$1\leq n\leq 1000$, $1\leq m\leq 100,000$, $1\leq x\leq n$）。表示有$n$个教室，$m$条路，$x$为方老师分身的地方。

接下来$m$行，每行三个数，$u$, $v$, $t$表示从教室$u$到教室$v$存在一条单向边，花费时间$t$（$1\leq t\leq 100$）。

# Standard Output

输出一个整数，往返中走路时间最长的分身所花费的时间。

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
<tr><td>4 8 2
1 2 4
1 3 2
1 4 7
2 1 1
2 3 5
3 1 2
3 4 4
4 2 3</td><td>10</td></tr></table>


# Constraints



# Note



# Source


