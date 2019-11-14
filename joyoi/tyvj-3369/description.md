# 

 
 # 题目描述 
<p>
战略游戏（Strategi.pas\c\cpp） <br><br>【题目描述】 <br>　　Bob喜欢玩电脑游戏，特别是战略游戏。但是他经常无法找到快速玩过游戏的办法。现在他有个问题。他要建立一个古城堡，城堡中的路形成一棵树。他要在这棵树的结点上放置最少数目的士兵，使得这些士兵能了望到所有的路。注意，某个士兵在一个结点上时，与该结点相连的所有边将都可以被了望到。<br>　　请你编一程序，给定一树，帮Bob计算出他需要放置最少的士兵。<br></p> 

 
 # 输入格式 
<p>
　　输入文件Strategi.in中数据表示一棵树，描述如下：<br>　　第一行 N，表示树中结点的数目。<br>　　第二行至第N+1行，每行描述每个结点信息，依次为：该结点标号i，k(后面有k条边与结点I相连)，接下来k个数，分别是每条边的另一个结点标号r1，r2，...，rk。<br>　　对于一个n(0 < n <= 1500)个结点的树，结点标号在0到n-1之间，在输入文件中每条边只出现一次。<br></p> 

 
 # 输出格式 
<p>
　　输出文件仅包含一个数，为所求的最少的士兵数目。<br>　　例如，对于如下图所示的树：<br>　　答案为1（只要一个士兵在结点1上）。<br><br><center><img src="/source/joyoi/tyvj-3369/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM2OS9wcm9ibGVtc19pbWFnZXMvMjE1Ni8xLmpwZw==.jpg"></img></center></p> 
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
<tr><td>【输入样例1】
4
0 1 1
1 2 2 3
2 0
3 0

【输入样例2】
5
3 3 1 4 2
1 1 0
2 0
0 0
4 0
</td><td>【输出样例1】
1

【输出样例2】
2</td></tr></table>
