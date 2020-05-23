
# Content

《无头骑士异闻录》准备拍摄新篇，并决定更换女主为`巴麻美`，可是与麻美学姐的合同却谈崩了，麻美学姐认为自己遭到了迫害不愿意参演，于是剧组就把学姐给掳走了。麻美学姐对于鹿目圆来说是一名深受信赖的前辈，于是小圆召集了一众魔法少女决定去营救麻美学姐。

参与营救活动的魔法少女共有 $x$ 名。现在她们正连续地站在一条狭长走廊的一端，我们把走廊划分为n个区域，则可以把魔法少女众看作分别站在第 $1, 2,...,x$ 个区域中，整个过程中没有两个魔法少女站在同一区域内。她们的目标是移动到第 $n-x+1, n-x+2,...,n$ 个区域内，从而以完美的阵容营救学姐。

魔法少女的移动方式主要靠的是魔力跃迁，一次跃迁最多能向前移动 $k$ 个单位长度，即若一个魔法少女站在 $i$ 位置，她能移动到 $i+1,i+2,...,i+k$ 的位置上，每次消耗 $c_1,c_2,...,c_k$ 点灵魂力量。在路途中她们可能遭遇 $q$ 个魔女结界，第 $i$ 个分布在第 $pos_i$ 个区域，若魔法少女跃迁到了$pos_i$中则需要发生战斗。在魔女结界中战斗可能消耗 $v_i$ 能量，其中 $v_i$ 可能为负数，若 $v_i$ 为负数，即意味着她们战胜魔女后获得了悲叹之种可以补充战斗中消耗的力量并额外储存 $|v_i|$ 的灵魂力量。

为了防止有魔女偷袭，她们还制订了一套行动准则，就是每次让最左边的一名魔法少女进行跃迁。

她们想在最终消耗灵魂能量最少的情况下成功营救学姐，她们最少消耗的灵魂能量是多少呢？（答案可能为负数）



麻美学姐知道小圆来救她，感到很安心：”**已经没有什么好怕的了！**“

![mami](/source/lutece/yi-jing-mei-you-shi-yao-hao-pa-de-liao/img/aHR0cHM6Ly9hZTAxLmFsaWNkbi5jb20va2YvSDA2MThiYTliYjgwZTQ3OGQ4YWQyOWEwMmEzMTgzYTdjNC5qcGc=.jpg)

# Standard Input

第一行包括四个数，分别是 $x, ~k, ~n,~q$   ($1 \leq x \leq k \leq 8, ~k \leq n \leq 10^8, ~0\leq q \leq \min(25, ~n-x)$)，分别代表魔法少女数量，每一次跃迁最远距离，走廊长度和魔女结界个数。

第二行包含 $k$ 个数，第 $i$ 个数代表跳跃距离为 $i$ 时消耗的灵魂力量 $c_i$ ($1 \leq c_i \leq 10^9$)

接下来 $q$ 行，每行包含两个数，$pos_i，~v_i$  ($x+1\leq pos_i \leq n,~|v_i| \leq 10^9$)，保证每个 $pos_i$ 各不相同

# Standard Output

输出消耗的灵魂力量最小是多少

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
<tr><td>2 3 10 2
1 2 3
5 -10
6 1000
</td><td>6
</td></tr></table>


# Constraints



# Note



# Source


