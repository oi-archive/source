
# Content

![pic](/source/lutece/tian-qi-zhi-zi/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMTcvc0d3VktZWHpTUVJEeTJqLnBuZw==.png)

最近去看《天气之子》了吗？这是一部由新海诚执导的动画电影。

**PE**STC 十分重视学生的身体素质，接下来的 $n$ 天是 PESTC 的运动会，但是天气预报预测接下来 $n$ 天并不都是晴天，有一些天是晴天，另一些天会下小雨，剩下一些天会下大雨。具体来说，第 $i$ 天的降雨量为 $h_i$。所以 Vingying 请来了 Amano Hina —— $100\%$ 晴女。

因为 PESTC 的学生大多习惯了潮湿的气候，所以 Vingying 想请 Hina 让开运动会的这 $n$ 天不下大雨。这里定义某天将下大雨当且仅当该天预报的降雨量大于 $w$ 毫米。

如果第 $i$ 天会下大雨，Hina 可以在当天花 $h_i-w$ 分钟祈祷，让第 $i$ 天不下大雨。然而祈祷是有代价的，如果让第 $i$ 天不下大雨，那么第 $i$ 天之后的每一天，降雨量都会增加 $k$，也就是说原本不会下大雨的一天也可能因为祈祷过多而下大雨。祈祷必须按照时间顺序，比如不能先在第二天祈祷后在第一天祈祷。

Vingying 想知道如果让这 $n$ 天都不下大雨，Hina 一共要花多少分钟祈祷。

# Standard Input

第一行包含三个整数 $n,w,k$ ($1\le n\le 2\times 10^5,0\le w,k\le 10^4$)。

第二行包含 $n$ 个整数，第 $i$ 个整数为 $h_i$ ($0\le h_i\le 10^4$)，表示第 $i$ 天的降雨量。

# Standard Output

输出一个整数，表示所求答案。

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
<tr><td>4 2 1
3 1 0 5</td><td>5</td></tr></table>


# Constraints



# Note

样例解释：

Hina 在第一天花 $1$ 分钟使得这一天不下大雨，所以接下来三天的降雨量分别变为 $2,1,6$。

第二天 Hina 不需要祈祷，所以接下来两天的降雨量仍为 $1,6$。

第三天 Hina 不需要祈祷，所以接下来一天的降雨量仍为 $6$。

最后一天 Hina 花费 $4$ 分钟使得这一天不下大雨，所以总时间为 $1+0+0+4=5$ 分钟。

# Source


