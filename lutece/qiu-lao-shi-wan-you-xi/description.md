
# Content

邱老师最近在玩一种战略游戏，在一个地图上，有N座城堡，每座城堡都有一定的宝物，在每次游戏中邱老师允许攻克M个城堡并获得里面的宝物。

但由于地理位置原因，有些城堡不能直接攻克，要攻克这些城堡必须先攻克其他某一个特定的城堡。你能帮邱老师算出要获得尽量多的宝物应该攻克哪M个城堡吗？

# Standard Input

每个测试实例首先包括2个整数，N,M.(1 <= M <= N <= 200);

在接下来的N行里，每行包括2个整数，a,b. 

在第 i 行，a 代表要攻克第 i 个城堡必须先攻克第 a 个城堡，如果 a = 0 则代表可以直接攻克第 i 个城堡。b 代表第 i 个城堡的宝物数量, b >= 0。

当N = 0, M = 0输入结束。

# Standard Output

对于每个测试实例，输出一个整数，代表邱老师攻克M个城堡所获得的最多宝物的数量。

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
<tr><td>3 2
0 1
0 2
0 3
7 4
2 2
0 1
0 4
2 1
7 1
7 6
2 2
0 0</td><td>5
13 </td></tr></table>


# Constraints



# Note



# Source


