
# Content

从前,有Z与Q两个太阳骑士,相爱相杀的他们决定用"太阳骑士の昆特牌"一分高下.

太阳骑士の昆特牌规则如下:

Z手中初始持有一张有数字$a$的牌,Q手中初始持有一张有数字$b$的牌

桌上有一叠$n$张牌,每张牌有一个数字$A_i$($A_1$为牌顶)

从Z开始,交替实行下列行为直到游戏结束:从牌顶抽取**不少于**一张牌,抽完后,只保留最后一张抽到的牌,舍弃手中其余牌.

当牌被抽完时,游戏结束.

游戏的最终得分为结束时 Z与Q手中两张牌上数字之差的绝对值.

Z想要最终得分尽量大,Q想要最终得分尽量小.

他们想知道最终得分,**在双方都采用最佳策略的情况下**,你能编写程序帮他们算出最终得分为多少吗?

# Standard Input

第一行输入三个整数表示:$n,a,b$  
第二行$n$个整数表示:$A_1,A_2,A_3,\cdots,A_n$  
$1\leq n\leq 2500,1\leq A_i,a,b \leq 10^9$

# Standard Output

最终得分是多少

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
<tr><td>1 1 1
100000000</td><td>99999999</td></tr><tr><td>5 2 2
2 2 2 2 2</td><td>0</td></tr><tr><td>3 1000 10000
100 1000 1000</td><td>9000</td></tr></table>


# Constraints



# Note



# Source


