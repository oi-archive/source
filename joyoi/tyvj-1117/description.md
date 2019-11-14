# 

 
 # 题目背景 
天好热……Tina顶着那炎炎的烈日，向Ice-cream&nbsp;home走去……<BR>可是……停电了……<BR>冰淇淋们躺在Ice-cream&nbsp;home的冰柜里，慢慢地……慢慢地……融化…………<BR>你说，她能赶在冰淇淋融化完之前赶到Ice-cream&nbsp;home去吗？ 

 
 # 题目描述 
给你一张坐标图，s为Tina的初始位置，m为Ice-cream&nbsp;home的位置，‘.’为路面，Tina在上面，每单位时间可以移动一格；‘#’为草地，Tina在上面，每两单位时间可以移动一格（建议不要模仿—毕竟Tina还小）；‘o’是障碍物，Tina不能在它上面行动。也就是说，Tina只能在路面或草地上行走，必须绕过障碍物，并到达冰淇淋店。但是…………不保证到达时，冰淇淋还未融化，所以……就请聪明的你……选择最佳的方案啦…………如果，Tina到的时候，冰淇淋已经融化完了，那她可是会哭的。 

 
 # 输入格式 
依次输入冰淇淋的融化时间t(0&lt;t&lt;1000)，坐标图的长x,宽y(5&lt;=x,y&lt;=25){太长打起来好累……}，和整张坐标图。<BR> 

 
 # 输出格式 
判断按照最优方案是否可以赶在冰淇淋融化之前到达冰淇淋店（注：当T=最优方案所用时间，则判断为未赶到），如赶到，输出所用时间；如未赶到，输出Tina的哭声——“55555”（不包括引号）。 
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
<tr><td>11
10
8
......s...
..........
#ooooooo.o
#.........
#.........
#.........
#.....m...
#.........</td><td>10</td></tr></table>
