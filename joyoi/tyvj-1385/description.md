# 

 
 # 题目背景 
『恶魔收敛了漆黑邪恶的羽翼<BR>&nbsp;&nbsp;在天使面前温柔地保持安静<BR>&nbsp;&nbsp;牧师拥抱祭坛断续祈祷<BR>&nbsp;&nbsp;不停询问与阿斯嘉特还有多少距离。』<BR><BR>————《瓦尔基里福音书·第三乐章：信仰》———— 

 
 # 题目描述 
Bifrost是连结神国Asgard和人类世界Midgard的桥梁，由三色——冰、火和空气——构成。Odin和Aser神族为了考验勇士Tristan，在Asgard的N个浮空岛屿之间建了M座虚无的三色虹桥Biforst。每座Bifrost的两端都各有一柄有两种状态【出鞘】和【封印】的魔法剑。Odin给Tristan留下的难题是：要给所有的魔法剑定下一个状态，使每个岛上处于两种不同状态的魔法剑数量相等，且每座桥两边的魔法剑必须处于不同状态。奥丁神还规定，第一座输入的Bifrost连结的编号较小浮空岛那端的剑已设置为【出鞘】状态且不可更改。 

 
 # 输入格式 
输入第一行一个整数N。表示浮空岛个数N。第2行开始每行3个整数，表示每座Bifrost的编号和两端连结的浮空岛编号。输入0&nbsp;0&nbsp;0表示结束。 

 
 # 输出格式 
按序换行输出每座Bifrost两端魔法剑的状态。Attack表示【出鞘】，Hiding表示【封印】。要求字典序最小，字典序最小指的是输出中所有Attack、Hiding连起来字典序最小。如样例输出的字典序是AttackHidingAttackHiding。无解输出“Your&nbsp;hero&nbsp;has&nbsp;fallen!”（不包括引号）。 

 
 # 提示 
对于100%的数据，1&lt;=N&lt;=200，数据保证所有浮空岛连通，不过两座浮空岛之间不一定只有一座Bifrost。《末世神话：希望之桥》 
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
<tr><td>2
1 1 2
2 2 1
0 0 0</td><td>Attack Hiding
Attack Hiding</td></tr></table>
