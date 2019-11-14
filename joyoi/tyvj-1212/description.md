# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;一种积木游戏，游戏者有N块编号依次为1，2，...，N的长方体积木。第i块积木过同一顶点三条边的长度为ai，bi，ci，如下图所示：<BR><img src="/source/joyoi/tyvj-1212/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIxMi9Qcm9ibGVtSW1nL3AxMjEyLmpwZw==.jpg" border=0 align=middle><BR>游戏规则如下：<BR>&nbsp;&nbsp;&nbsp;&nbsp;1.从N块积木中选出若干块，并将它们摞成M(1&lt;=M&lt;=N)根柱子，&nbsp;编号依次为1，2，...，M，要求第K&nbsp;根柱子的任意一块积木的编号都必须大于第K-1根柱子任意一块积木的编号(2&lt;=K&lt;=M)。<BR>&nbsp;&nbsp;&nbsp;&nbsp;2.对于每一根柱子，一定要满足下面三个条件：<BR>&nbsp;&nbsp;&nbsp;&nbsp;1)除最顶上的一块积木外，任意一块积木的上表面同且仅同另一块积木的下表面接触；<BR>2)对于任意两块上下表面相接触的积木，若m，n是下面一块积木接触面的两条边(m≥n)，x，y是上面一块积木接触面的两条边(x≥y)，则一定要满足m≥x，n≥y；<BR>3)下面的积木的编号要小于上面的积木的编号。<BR>&nbsp;&nbsp;&nbsp;&nbsp;请你编一程序，寻找一种游戏方案，使得所能摞成的M&nbsp;根柱子的高度之和最大。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;文件的第一行是两个正整数N和M(1≤M≤N&nbsp;≤100)，分别表示积木总数和要求摞成的柱子数。这两个数之间用一个空格符隔开。接下来的N行依次是编号从1到N的&nbsp;N个积木的尺寸，每行有三个1至500之间的整数，分别表示该积木三条边的长度。&nbsp;同一行相邻两个数之间用一个空格符隔开。 

 
 # 输出格式 
&nbsp;文件只有一行，是一个整数，表示所求得的游戏方案中M根柱子的高度之和。 

 
 # 提示 
具体方案为第一个木块为一堆，第2个和第4个为一堆 
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
<tr><td>4 2
10 5 5
8 7 7
2 2 2
6 6 6
</td><td>24</td></tr></table>
