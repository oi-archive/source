
# Content

oydy又开始坏球旅行了，不过这次oydy采取了低调一些的做法，他想去每个城市旅游，并且经过一条路时付过路费（而不是买下这条路）。城市$i$以坐标$(x_i,y_i)$的形式给出，每两个城市之间的过路费为他们之间的曼哈顿距离（PS：$(x_i,y_i)$和$(x_j,y_j)$之间的曼哈顿距离为$|x_i-x_j|+|y_i-y_j|$），现在oydy要预算一下，从城市$s$出发，遍历所有城市，所花费的路费最少是多少，oydy并不关心旅行在哪里结束，因为不管在哪里结束都会开启下一段旅程。

# Standard Input

第一行两个正整数$n\leq17,s\leq n$表示有$n$个城市，oydy要从城市s出发，城市从1开始标号。
接下来$n$行每行两个整数$x_i,y_i（|x_i|,|y_i|\leq10^9）$表示第i个城市的坐标。
保证不会出现两个城市坐标一样的情况。

# Standard Output

一行一个整数表示最小花费。

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
<tr><td>4 1
0 0
1 0
1 2
2 1</td><td>5</td></tr></table>


# Constraints



# Note

按照$(0,0)->(1,0)->(2,1)->(1,2)或(0,0)->(1,0)->(1,2)->(2,1)$的顺序即可。

# Source


