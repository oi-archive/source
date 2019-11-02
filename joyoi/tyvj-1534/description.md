# 

 
 # 题目描述 
还是宇宙时间公元5.5亿年，maxingc联盟用微子来攻击yun联盟。愤怒的yun联盟决定反戈一击，他们准备使用加农炮来反击。<BR>yun联盟的将军们打算在N*M的网格地图上部署他们的炮兵部队。一个N*M的地图由N行M列组成，地图的每一格可能是山地（用"H"&nbsp;表示），也可能是平原（用"P"表示），在每一格平原地形上最多可以布置一支炮兵部队（山地上不能够部署炮兵部队）：&nbsp;它能够攻击到的区域：沿横向左右各两格，沿纵向上下各两格。炮兵的攻击范围不受地形的影响。&nbsp;<BR>现在，将军们规划如何部署炮兵部队，在防止误伤的前提下（保证任何两支炮兵部队之间不能互相攻击，即任何一支炮兵部队都不在其他支炮兵部队的攻击范围内），在整个地图区域内最多能够摆放多少我军的炮兵部队。<BR> 

 
 # 输入格式 
第一行包含两个由空格分割开的正整数，分别表示N和M；&nbsp;<BR>接下来的N行，每一行含有连续的M个字符('P'或者'H')，中间没有空格。按顺序表示地图中每一行的数据。N&nbsp;&lt;=&nbsp;100；M&nbsp;&lt;=&nbsp;10。<BR> 

 
 # 输出格式 
仅一行，包含一个整数K，表示最多能摆放的炮兵部队的数量。 
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
<tr><td>5 4
PHPP
PPHH
PPPP
PHPP
PHHP
</td><td>6</td></tr></table>
