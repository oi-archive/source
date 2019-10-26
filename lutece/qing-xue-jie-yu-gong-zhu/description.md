
# Content

某日，百无聊赖的卿学姐打开了某11区的某魔幻游戏

在这个魔幻的游戏里，生活着一个美丽的公主，但现在公主被关押在了魔王的城堡中。

英勇的卿学姐拔出利刃冲向了拯救公主的道路。

走过了荒野，翻越了高山，跨过了大洋，卿学姐来到了魔王的第一道城关。

在这个城关面前的是魔王的精锐部队，这些士兵成一字排开。

卿学姐的武器每次只能攻击一个士兵，并造成一定伤害，卿学姐想知道某时刻从$L$到$R$这个区间内，从开始到现在累计受伤最严重的士兵受到的伤害。

最开始每个士兵的受到的伤害都是0

# Standard Input

第一行两个整数$N,Q$表示总共有$N$个士兵编号从$1$到$N$，和$Q$个操作。

接下来$Q$行，每行三个整数，首先输入一个$t$，如果$t$是$1$，那么输入$p,x$，表示卿学姐攻击了$p$这个位置的士兵，并造成了$x$的伤害。如果$t$是$2$，那么输入$L,R$，表示卿学姐想知道现在$[L,R]$闭区间内，受伤最严重的士兵受到的伤害。

$1\le N \le 100000$

$1\le Q \le 100000$

$1\le p \le N$

$1\le x \le 100000$

$1\le L \le R \le N$

# Standard Output

对于每个询问，回答相应的值

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
<tr><td>5 4
2 1 2
1 2 4
1 3 5
2 3 3
</td><td>0
5
</td></tr></table>


# Constraints



# Note

注意可能会爆int哦

# Source


