# 

 
 # 题目描述 
<p>
给定一颗树，树中每个结点有一个邮递员，每个邮递员要沿着唯一的路径走向capital(1号结点)，每到一个城市他可以有两种选择：<br>1.继续走到下个城市<br>2.让这个城市的邮递员替他出发。<br>每个邮递员出发需要一个准备时间W[I]，他们的速度是V[I]，表示走一公里需要多少分钟。<br>现在要你求出每个城市的邮递员到capital的最少时间(不一定是他自己到capital，可以是别人帮他）<br><br>N<=100000<br><br>3 ≤  N ≤  100 000 <br>0 ≤  Si≤ 10^9<br> <br>1 ≤  Vi≤ 10^9<br> <br>The length of each road will not exceed 10 000 <br>For 20% of the tests, N ≤  2 500 <br>For 50% of the tests, each town will have at most 2 adjacent roads (i.e., the graph of <br>roads will be a line) </p> 

 
 # 输入格式 
<p>
N<br>以下N-1行A,B,C三个数表示A,B之间有一条长为C的边。<br>再N行每行两数Wi,Vi<br>输出有一行N-1个数表示如题所述。<br></p> 

 
 # 输出格式 
<p>
</p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2599/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjU5OS9wcm9ibGVtc19pbWFnZXMvMzA0MC8xNzY3LmpwZw==.jpg"> <br></p> 
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
<tr><td>5 
1 2 20 
2 3 12 
2 4 1 
4 5 3 
26 9 
1 10 
500 2 
2 30 </td><td>206 321 542 328 </td></tr></table>
