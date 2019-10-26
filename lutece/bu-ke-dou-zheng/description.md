
# Content

通信学院的zhong_wang和电工学院的cfeitong是形影不离的好朋友，两人一起上课，一起吃饭，还一起玩ACM，关系十分亲密。有一天，两人相约英语角，英语角的主题是"The Beauty of Poker".到了英语角的教室，两人看见桌上摆了各种各样精美漂亮的扑克牌，可这时zhong_wang的目光却被旁边一位小酒窝、长睫毛的女孩所吸引,没想到cfeitong却抢先一步,拿起一张红桃Q，走到女孩面前，问道:"Do you want to be my queen?"女孩看出了两人的心思，觉得两人都很可爱，于是决定让两人通过
打一盘牌的方式来竞争。女孩是通信学院的学生，对zhong_wang有所偏爱，所以她制定了一个很奇怪的游戏规则：

两人从一堆不含大小鬼的扑克牌中抓牌，zhong_wang抓2张，cfeitong抓13张，**如果手中有相同点数的牌，则只留该点数的牌一张，多余的丢掉。**牌只能一张一张地出，每一轮本方可选出比对方所出更大的牌（牌的大小：3<4<5<6<7<8<9<10<J<Q<K<A<2),或选择不出。若对方选择不出后，本方可任意出牌。先出完自己手中牌的一方获胜。为了防止两人作弊，两人的牌必须摊在桌上打，因此双方也可以看到对方的牌。两人对女孩好感有加，都会使用最佳策略来争取胜利。**现给出两人抓完牌并完成丢弃过程之后的牌序列**，第一轮由zhong_wang先出，请你判断谁会获得胜利。

# Standard Input

输入共两行。

第一行一个字符串，表示zhong_wang手中的牌序列。

第二行一个字符串，表示cfeitong手中的牌序列。

**牌序列保证从左到右按点数从小到大排列,点数10用字母T代替。**

# Standard Output

仅一行，输出胜利者的名字。

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
2</td><td>zhong_wang</td></tr><tr><td>48
6T</td><td>cfeitong</td></tr></table>


# Constraints



# Note



# Source


