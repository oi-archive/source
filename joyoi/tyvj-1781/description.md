# 

 
 # 题目描述 
【问题描述】：	lxhgww最近迷上了一款游戏，在游戏里，他拥有很多的装备，每种装备都有2个属性，这些属性的值用[1,10000]之间的数表示。当他使用某种装备时，他只能使用该装备的某一个属性。并且每种装备最多只能使用一次。<BR>	游戏进行到最后，lxhgww遇到了终极boss，这个终极boss很奇怪，攻击他的装备所使用的属性值必须从1开始连续递增地攻击，才能对boss产生伤害。也就是说一开始的时候，lxhgww只能使用某个属性值为1的装备攻击boss，然后只能使用某个属性值为2的装备攻击boss，然后只能使用某个属性值为3的装备攻击boss……以此类推。<BR>现在lxhgww想知道他最多能连续攻击boss多少次？<BR> 

 
 # 输入格式 
【输入格式】<BR>&nbsp;&nbsp;&nbsp;	输入的第一行是一个整数N，表示lxhgww拥有N种装备<BR>	接下来N行，是对这N种装备的描述，每行2个数字，表示第i种装备的2个属性值<BR><BR><BR> 

 
 # 输出格式 
【输出格式】<BR>&nbsp;	输出一行，包括1个数字，表示lxhgww最多能连续攻击的次数。<BR> 

 
 # 提示 
【数据范围】<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于30%的数据，保证N&lt;=1000<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，保证N&lt;=1000000SCOI2010 
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
<tr><td>【样例输入】
	3
	1 2
	3 2
	4 5</td><td>【样例输出】
	2</td></tr></table>
