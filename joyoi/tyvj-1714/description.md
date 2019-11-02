# 

 
 # 题目描述 
DaA有一个弹性小球，小球有一个能量值E。<BR>DaA走进一个M*N房间，房间有M行N列。<BR>一开始在左上角，以向右下角45°的方向弹射小<BR>球。小球有两个性质：<BR>1.小球在运动过程中不会损失能量，只有在碰壁或碰角的时候才会损失能量，能量&lt;=0了小球就停止运动了；<BR>2.小球弹射遵循反射定律，小球碰角会原路返回（请参照右边图画）。<BR>请聪明的你告诉DaA弹性小球在这个房间中的运动轨迹。<BR><img src="/source/joyoi/tyvj-1714/img/aHR0cDovL2Zhcm04LnN0YXRpY2ZsaWNrci5jb20vNzAxMC82NzA1ODQzNDkzX2E2YzlmZTE0NDZfbS5qcGc=.jpg" border=0 align=middle> 

 
 # 输入格式 
第一行三个整数M、N、E，表示房间的行数和列数、小球的初始能量。<BR>第二行八个整数，分别是小球撞到上（北）、右（东）、下（南）、左（西）、左上（西北）、右上（东北）、右下（东南）、左下（西南）损失的能量。 

 
 # 输出格式 
输出一张小球运动的轨迹图（详见样例）。轨迹图要求如下：<BR>1.&nbsp;整个(M+2)*(N+2)的图，外面要有边框，上下各N&nbsp;个'-'，左右各M&nbsp;个'|'；<BR>2.&nbsp;小球运动轨迹用'/'和'\'表示，其他部分用'&nbsp;'表示。 

 
 # 提示 
【数据规模】<BR>30%的数据&nbsp;1&lt;=M,N&lt;=10，0&lt;E&lt;=30。<BR>100%的数据&nbsp;1&lt;=M,N&lt;=100，0&lt;E&lt;=10^9。 
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
<tr><td>Sample Input 1:
2 2 5
2 3 4 6 1 1 3 9

Sample Input 2:
3 5 6
1 1 1 1 1 1 1 1</td><td>Sample Output 1:
--
|\ |
| \|
--

Sample Output 2:
-----
|\/ /\|
|/\/ /|
|\/\/ |
-----</td></tr></table>
