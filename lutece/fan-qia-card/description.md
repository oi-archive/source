
# Content

电子科大本部食堂的饭卡有一种很诡异的设计，即在购买之前判断余额。如果购买一个商品之前，卡上的剩余金额大于或等于$5$元，就一定可以购买成功（即使购买后卡上余额为负），否则无法购买（即使金额足够）。所以大家都希望尽量使卡上的余额最少。

某天，食堂中有$n$种菜出售，每种菜可购买一次。已知每种菜的价格以及卡上的余额，问最少可使卡上的余额为多少。

# Standard Input

多组数据。对于每组数据：
* 第一行为正整数$n$，表示菜的数量。$n\leq 1000$。
* 第二行包括$n$个正整数，表示每种菜的价格。价格不超过$50$。
* 第三行包括一个正整数$m$，表示卡上的余额。$m\leq 1000$。

$n=0$表示数据结束。

# Standard Output

对于每组输入,输出一行,包含一个整数，表示卡上可能的最小余额。

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
<tr><td>1
50
5
10
1 2 3 2 1 1 2 3 2 1
50
0</td><td>-45
32</td></tr></table>


# Constraints



# Note



# Source


