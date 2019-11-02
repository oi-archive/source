# 

 
 # 题目描述 
DotR&nbsp;(Defense&nbsp;of&nbsp;the&nbsp;Robots)&nbsp;Allstars是一个风靡全球的魔兽地图，它的规则简单于同样流行的地图DotA&nbsp;(Defense&nbsp;of&nbsp;the&nbsp;Ancients)&nbsp;Allstars。DotR里面的英雄只有一个属性——力量。它们需要购买装备来提升自己的力量值。每件装备都可以使佩戴它的英雄的力量值提高固定的点数，所以英雄的力量值等于它购买的所有装备的力量值之和。<BR>装备分为基本装备和高级装备两种，基本装备可以直接从商店里面用金币购买，而高级装备需要用基本装备或者较低级的高级装备来合成，合成不需要附加的金币。装备的合成路线图可以用一棵树来表示，如下图所示。例如，Sange&nbsp;and&nbsp;Yasha的合成需要Sange、Yasha和Sange&nbsp;and&nbsp;Yasha&nbsp;Recipe&nbsp;Scroll三样物品。其中Sange又要用Ogre&nbsp;Axe、Belt&nbsp;of&nbsp;Giant&nbsp;Strength和Sange&nbsp;Recipe&nbsp;Scroll合成。<BR><img src="/source/joyoi/tyvj-1825/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTgyNS9Qcm9ibGVtSW1nLzE4MjUtMS5qcGc=.jpg" border=0 align=middle><BR>每件基本装备都有数量限制，这限制了你不能无限制地合成某些性价比很高的装备。<BR>现在，英雄Spectre有&nbsp;M个金币，它想用这些钱购买装备使自己的力量值尽量高。你能帮帮它吗？它会教你魔法Haunt（幽灵附体）作为回报的。<BR> 

 
 # 输入格式 
输入文件的第一行包含两个整数N&nbsp;(1&nbsp;≤&nbsp;N&nbsp;≤&nbsp;51)和M&nbsp;(0&nbsp;≤&nbsp;M&nbsp;≤&nbsp;2,000)。分别表示装备的种类数和金币数。装备用1到N的整数编号。<BR>接下来的N行，按照从装备1到装备N的顺序，每行描述一种装备。每一行的第一个正整数表示这个装备贡献的力量值。接下来的非空字符表示这种装备是基本装备还是高级装备，A表示高级装备，B表示基本装备。如果是基本装备，紧接着的两个正整数分别表示它的单价（单位为金币）和数量限制（不超过100）。如果是高级装备，后面紧跟2C个数，表示合成这种装备需要C种低级的装备。第2I&nbsp;–&nbsp;1个数表示这个合成方案中第I种装备的编号，第2I个数表示该装备所需的个数。<BR><BR> 

 
 # 输出格式 
输出文件的第一行包含一个整数S，表示最多可以提升多少点力量值。接下来的N行，每行一个整数，描述你提供的方案。第I行的整数表示你提供的方案中编号为I的装备的购买数目。<BR>输入数据保证正确的S不会超过231&nbsp;–&nbsp;1。如果有多种方案都能获得最大的力量值，输出任意一种即可。对于每个测试点，你的答案必须完全正确才能得分。<BR><BR><BR> 

 
 # 提示 
<img src="/source/joyoi/tyvj-1825/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTgyNS9Qcm9ibGVtSW1nLzE4MjUtMi5qcGc=.jpg" border=0 align=middle><BR>JSOI2008江苏省代表队组队第三轮选拔赛&nbsp;本次竞赛共分两试，本试卷为第二试。 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>10 59
5 A 3 6 1 9 2 10 1
1 B 5 3
1 B 4 3
1 B 2 3
8 A 3 2 1 3 1 7 1
1 B 5 3
5 B 3 3
15 A 3 1 1 5 1 4 1
1 B 3 5
1 B 4 3
</td><td>33
0
0
0
2
2
0
0
1
0
0
</td></tr></table>
