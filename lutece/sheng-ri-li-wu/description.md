
# Content

马上就要是雪菜的生日了，春希摸了摸自己的钱包，发现已经见底。为了给雪菜买生日礼物，春希决定炒股！

知己知彼才能百战百胜，春希通过冬马家的关系知道了股市接下来$n$天的行情。

在第i天，股票的买入价和卖出价分别为$Ap\_i$和$Bp\_i$，并且春希能买入和卖出的股票最多为$As\_i$和$Bs\_i$。

由于毕竟是作弊的关系，被发现就一切都完蛋了，冬马叮嘱春希两次交易(买入和卖出都算作一次交易)的间隔必须大于等于$w$天。也就是说如果第$i$天交易了，最早也要等到第$i+w+1$天才能做交易了，并且告诫他，拥有的股票数绝对不能超过$Maxp$股！

春希最初有无限的钱（冬马借他的，当然是要还的）和零股股票，他想知道，自己在这$n$天最多能赚多少钱。

# Standard Input

第一行一个整数t，表示数据组数。

第二行三个整数，分别为$n,Maxp,w。(0 \leq w<n \leq 2000,1 \leq Maxp \leq2000)$

接下来$n$行，每行$4$个整数，分别为$Ap\_i,Bp\_i,As\_i,Bs\_i。(1 \leq Bp\_i \leq Ap\_i \leq1000,1 \leq As\_i,Bs\_i \leq Maxp)$

# Standard Output

一个整数，表示春希能赚的最多的钱。

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
5 2 0
2 1 1 1
2 1 1 1
3 2 1 1
4 3 1 1
5 4 1 1</td><td>3</td></tr></table>


# Constraints



# Note



# Source


