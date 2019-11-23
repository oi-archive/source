
# Content

![pic](/source/lutece/lu-shi-chuan-shuo/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMTcvelQ5SVhmaVZzdEpvd3lGLmpwZw==.jpg)

Kaiser 在玩炉石传说。现在场上有 $n$ 个随从，Kaiser 想让场面变得干净，所以他决定要消灭所有随从，第 $i$ 个随从的血量为 $a_i$。每回合 Kaiser 可以打出一张旋风斩来对所有随从造成 $X$ 点伤害，或者打出一张火球术来对某一个随从造成 $Y$ 点伤害。如果对某随从的伤害点数大于等于他的血量，则该随从被消灭。

Kaiser 想尽快把所有随从消灭掉，但他要去做作业，所以他把问题抛给了 Fatdog_Jo。但 Fatdog_Jo 不玩炉石传说，所以他把问题抛给了你。请你回答，Kaiser **至少**要多少个回合才能消灭所有随从。

# Standard Input

第一行有一个整数 $n$ ($1 \leq n \leq5000$)。

第二行有两个整数分别为 $X$ , $Y$ ($1 \leq X,Y \leq5000$)。

第三行有 $n$ 个整数 $a_1,a_2,\ldots,a_n$ ($1 \leq a_i \leq5000$)。

# Standard Output

输出一个整数，代表 Kaiser 消灭所有随从需要的**最少**回合数。

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
<tr><td>3
1 2
2 1 3</td><td>3</td></tr><tr><td>4
2 3
3 2 3 4</td><td>2</td></tr></table>


# Constraints



# Note

对于第一个样例，第一回合可以对第三个随从打出一张火球术，第二个回合可以打出一张旋风斩，第三个回合再打出一张旋风斩，此时所有随从都被消灭。（当然对于第一个样例，三个回合消灭所有随从还有其他方法，这里举例出其中一种）

对于第二个样例，第一回合打出一张旋风斩，第二回合再打出一张旋风斩，即可消灭所有随从。

# Source


