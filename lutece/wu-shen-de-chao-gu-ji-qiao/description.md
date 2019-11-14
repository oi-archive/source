
# Content

吴神很神,所以吴神玩啥啥牛逼.最近吴神开始玩股票了,果然没玩多久吴神就赚到了无限多的钱.为了维持股票市场的平衡性,管理员对吴神作出了一些限制如下:

1. 吴神的股票总持有量不得超过$mp$.
2. 吴神的两个交易日之间必须间隔$w$天,也就是说,如果吴神在第$i$天做了交易,下一次交易必须在第$i+w$天之后. 
3. 吴神在一天只能作出一种操作,即要不买入要不卖出,或者什么也不做.
4. 吴神在第$i$天最多只能买入$B\_i股,或者卖出$S\_i$股.

不过吴神表示这些限制根本难不倒他,他仍然能在$t$天内赚到最多的钱.

# Standard Input

第一行为$T$,数据组数

每组数据的第一行为$t,mp,w$, 接下来$t$行,每行为$S\_i,B\_i,Sp\_i,Bp\_i$表示当天卖出和买入限制，卖出和买入每股的价钱。

$0\leq t,mp,w,s\_i,b\_i,sp\_i,sb\_i\leq 1985$

# Standard Output

每组数据单独一行输出，吴神在t天内最多能赚到多少钱。

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
9 5 5
9 7 0 7
9 4 9 4
6 4 5 7
1 8 2 9
8 5 1 3
0 9 1 7
4 1 6 6
2 0 8 1
3 4 3 1</td><td>8</td></tr></table>


# Constraints



# Note



# Source


