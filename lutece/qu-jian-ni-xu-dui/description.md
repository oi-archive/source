
# Content

UESTC_SaltedFish队有三条咸鱼，这天他们把清水河所有的咸鱼召集起来，让它们排成一列，每条咸鱼有一个咸度值，AutSky_JadeK想知道对于一个区间中的咸鱼，咸度值的逆序对的数量是多少？

即：给定一个正整数序列a,每次询问一个区间[l,r],输出al...ar中的逆序对的数量,强制在线。

# Standard Input

第一行包括一个整数$n(1<=n<=50000)$,表示数列$a$中的元素数。

第二行包括$n$个整数$a1...an$($ai>0$,保证$ai$在int内)。

接下来一行包括一个整数$m(1<=m<=50000)$,表示询问的个数。

接下来$m$行,每行包括$2$个整数$l、r(1<=l<=r<=n)$,表示询问$al...ar$中的逆序对的数量(若$ai>aj$且$i<j$,则为一个逆序对)。

要注意，为了体现强制在线，输入的$l,r$要分别异或上一次询问的答案($lastans$)，才能得到真正的$l,r$是多少。最开始时$lastans=0$。

保证涉及的所有数在int内。

保证每次xor后的l,r都是合法的

# Standard Output

每个询问，输出一个答案。

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
1 4 2 3
1
2 4
</td><td>2
</td></tr></table>


# Constraints



# Note



# Source


