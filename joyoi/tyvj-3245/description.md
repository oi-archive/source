# 

 
 # 题目描述 
<p>
地主(landlord.pas/c/cpp)<br><br>【问题描述】<br><br>　 　 在Dukeswood这块土地上生活着一个富有的农庄主和他的几个孩子。在他临终时，他想把他的土地分给他的孩子。他有许多农场，每个农场都是一块矩形土地。他在农场地图上划上一些直线将矩形分成若干块。当他划直线时，他总是从矩形边界上的某一点划到另一个矩形边界上的点，这条线的结束点将成为下一条线的起始点。他划线时从不会让任三线共点。例如图1是某一种划分结果。<br><br><br><center><img src="/source/joyoi/tyvj-3245/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzI0NS9wcm9ibGVtc19pbWFnZXMvMTgwMy9wMS5naWY=.gif"></img></center><br><br>　 　 划分的起始点和结束点均以五角星标记。当他完成划分后，他想要数一下划出的土地的块数以确保每个孩子都有一块地。例如，图1中土地被划分成18块。然而这个庄主由于年迈常会数错，因而他寻求你的帮助。请写一个程序，输入原来的土地尺寸及线段的位置，输出划分出的土地块数。</p> 

 
 # 输入格式 
<p>
输入文件有多组数据组成。每组数据格式如下：<br>第一行输入地图的宽度w (1≤ w ≤1000)和高度 h (1&#61603; h &#61603;1000)，均为整数。<br>第二行输入线段数L (1≤ L ≤50)。<br>以下L+1行每行一个整数坐标(Xi,Yi)，庄主划的线段为(Xi,Yi)-(Xi+1,Yi+1)，i=1,2,…,L。当然(Xi,Yi)必定在矩形的边界上。<br>最后一组数据w=h=0，标志文件结束，不需要处理。<br><br></p> 

 
 # 输出格式 
<p>
对于给定的输入，输出一行仅含一个数，即划分出的土地块数。</p> 
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
<tr><td>18 12
8
2 0
6 12
10 0
18 9
15 12
0 6
14 0
10 12
0 9
7 6
6
2 0
5 6
7 3
0 3
3 0
3 6
0 5
0 0</td><td>18
11</td></tr></table>
