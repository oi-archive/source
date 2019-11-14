# 

 
 # 题目背景 
Fated&nbsp;Me原创 

 
 # 题目描述 
YO-GI-OH中有这么一张魔法卡——力量。它会根据某种方法给予被装备者强大的力量。这张卡上写着，dota中所有有拓扑关系（若x与y有拓扑关系，并且y与z有拓扑关系，则x与z也有拓扑关系）的生物会组成一个佣兵团（很可惜他们的名字都是数字…）。其中LYD(鉴于LYD出题经常拿我(比如GF和猫咪的玩具那题)开涮，今天我也得反过来T_T)所在的佣兵团中的成员根据名字分为2个党派：质数党和非质数党（应wwwwodddd要求添加了这么有数论气息的名词..）。质数党中的每个生物可以和非质数党中的任意生物用硅酸钠粘到一起而成为一个称为互补金属合金氧化物半导体（BIOS）的东西。而互补金属合金氧化物半导体（BIOS）的数量就是这张魔法卡能提供的力量。 

 
 # 输入格式 
输入数据：第一行n,m，表示一共有n个生物（名字为1-n），和m对拓扑关系。<BR>以下m行每行2个整数x,y，代表x,y有拓扑关系。<BR>最后一行：LYD的名字（一个整数）。 

 
 # 输出格式 
输出数据：最大互补金属合金氧化物半导体（BIOS）即力量的数量。（一个整数）。 

 
 # 提示 
注释：本题难点在于理解。<BR>数据范围：50％的数据，M,N&lt;=100<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;100％的数据，M,N&lt;=4000Fated&nbsp;Me 
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
<tr><td>2 1
1 2
1
</td><td>1</td></tr></table>
