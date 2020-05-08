
# Content

***吾名惠惠，红魔族第一的魔法师兼爆裂魔法的操纵者，好好见识我的力量吧！Ex——plo——sion————！！！***
![](/source/lutece/hong-mo-zu-shou-qu-yi-zhi-noda-mo-fa-shi/img/aHR0cHM6Ly9maWxlcy5jYXRib3gubW9lLzBraDcyai5wbmc=.png)
红魔之里因魔王军干部合成兽西尔维娅的袭击被破坏得很彻底。但是好在红魔族人均大魔法师，可以使用各种高级魔法帮助重建红魔之里。红魔族首屈一指的大魔法师，惠惠，负责搬运重建红魔之里所需的建筑材料。可是惠惠所有的技能点都点到了爆裂魔法强化上，她并不会传送 (Teleport) 魔法，所以惠惠只能搭其他红魔族的传送魔法。红魔之里由 $N$ 座房屋构成，其他红魔族总是在两座房屋之间施展传送魔法，这时惠惠可以通过搭这位红魔族的传送魔法在 $A,B$ 之间往来。红魔族们都富有智慧，两座房屋之间如果能够通过传送魔法互相到达，那他们就不会在这两座房屋之间施展传送魔法。有时某位红魔族开始在 $A,B$ 两座房屋之间使用传送魔法；有时某位红魔族停止在 $A,B$ 两座房屋之间使用传送魔法。惠惠很累，刚刚结束和魔王军干部的战斗的她不想走路。惠惠会时不时会询问 $A,B$ 两座房屋之间是否可以通过若干次传送魔法到达而无需走动。

你，一个一般通过红魔族，打算回答惠惠的询问。这样惠惠父亲制作的魔道具可以打折提供给你。

# Standard Input

第一行为两个正整数 $N$ 和 $M$，分别表示房屋和事件的数量。
之后 $M$ 行，每行一个字符 $c_i$ 和两个正整数 $a_i,b_i$。
若 $c_i$ 为 '+'，则表示有一个红魔族开始在 $a_i$ 和 $b_i$ 之间施展传送魔法。
若 $c_i$ 为 '-'，则表示有一个红魔族停止在 $a_i$ 和 $b_i$ 之间施展传送魔法。
若 $c_i$ 为 '?'，则表示惠惠询问你 $a_i$ 和 $b_i$ 两座房屋之间是否能通过传送魔法到达。

# Standard Output

对于惠惠的每次询问，若两座房屋之间能通过通过传送魔法到达则输出 "Yes"，否则输出 "No"。（不含双引号）

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
<tr><td>233 8
+ 233 332
+ 111 222
? 111 233
? 233 332
+ 222 332
? 111 233
- 111 222
? 111 233</td><td>No
Yes
Yes
No</td></tr></table>


# Constraints

$1≤N,a_i,b_i≤10000,1≤M≤200000$

# Note



# Source


