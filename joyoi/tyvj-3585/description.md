# 

 
 # 题目描述 
<p>
 <br><br><br>在三角形图上，每个小正三角形的面积都是1。可以在边上走出一个多边形，（即三角形网格图的边界，见下图）使得围成一定的面积。<br><br>我们可以用编码来表示走法：（即从一条边到下一条边的方向改变量）<br><br>a左转120°<br><br>b左转60°<br><br>c直走<br><br>d右转60°<br><br>e右转120°<br><img border="0" src="/source/joyoi/tyvj-3585/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzU4NS9wcm9ibGVtc19pbWFnZXMvMjQzMy8xMTM0LmpwZw==.jpg"> <br><br>可以描述为cdddcddd 或dddcdddc，cbbbcbbb<br><br>对于描述同样形状的图形的不同序列，我们只用字典序最小的，即bbbcbbbc<br><br> <br><br>两个多边形在几何的概念上全等即看做等价。显然等价的图形用字母路径表示出来是一样的。<br><br> <br><br>你的任务有两个：<br><br>1． 对于给定的N输出所有面积为N的可以走出来的图形的编码<br><br>2． 对于给定的形状序列，求出其面积K并计算在这个图形基础上加一个小三角形可以组成哪些可编码图形。<br><br>每个测试点 询问不超过5次<br><br>数据保证 N,K ≤ 10<br><br> <br></p> 

 
 # 输入格式 
<p>
第一行数据总数t， t≤5<br><br>每个询问以“N”开头则表示任务1，接下来一个整数N<br><br>以“K”开头则表示任务2，接下来是一个字符串。<br><br> <br></p> 

 
 # 输出格式 
<p>
对于每个任务，输出两行，<br><br>第一行表示满足要求的方案总数，<br><br>第二行按字典序输出所有序列，两个序列之间用一个空格隔开。<br></p> 
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

K adeccecced

N 5
</td><td>5

acedccecced addebcecced adebebecced adecbedcced cceccecce

4

aeddde bdecdde bececde ccedcde</td></tr></table>
