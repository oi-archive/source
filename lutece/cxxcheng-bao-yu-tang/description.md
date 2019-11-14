
# Content

这一天ydy要跨过山和大海去找cxx玩，地图上一共有$n$个城市，$m$条双向道路，每条道路连接两个城市，ydy从城市$s$出发，cxx在城市$t$，每条道路上都有一个农夫，当ydy经过一条道路时，就会被农夫劝着去他的鱼塘钓鱼，然后花费$w$的钱。霸气的cxx知道了之后，给了ydy k个鱼塘的承包权，也就是说，ydy可以选择$k$个鱼塘，承包下来，这样他就不用在那里缴纳钓鱼的费用了。由于ydy钱包紧，他想知道他的最小花费是多少。

# Standard Input

第一行三个正整数$n(\leq 10000),m(\leq200000),k(\leq20)$表示城市数量，道路的数量，以及鱼塘承包权的数量。
第二行两个整数$s,t$表示ydy会从城市$s$出发，cxx在城市$t$。
接下来$m$行每行三个整数$u,v,w$表示从点$u$到点$v$有一条道路，如果不承包该条路径上的鱼塘的话，ydy会花掉$w$的钱$(1\leq u,v\leq n，1\leq w\leq 10^9)$。

可能会存在重边,保证所有城市联通

# Standard Output

一行一个整数表示ydy的最少路费

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
<tr><td>4 4 1
1 4
1 2 3
2 3 4
3 4 5
1 3 10</td><td>5</td></tr></table>


# Constraints



# Note

走1->3->4的路线，并且承包1->3的鱼塘

# Source


