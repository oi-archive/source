# 

 
 # 题目描述 
<p>
平面上有N个矩形，矩形的边与坐标轴平行。这些矩形之间可以相交或覆盖。每个矩形的顶点都是非负整数，并且横坐标不超过xmax，纵坐标不超过ymax。现在你要寻找一个点B，点B在线段[(0, ymax), (xmax, ymax)]或[(xmax, 0), (xmax, ymax)]上，并且它与(0,0)的连线段与尽量多的矩形相交。如果两个几何图形有公共点，我们就认为它们相交。<br></p> 

 
 # 输入格式 
<p>
输入文件第一行是整数xmax,ymax和N。此后N行，每行描述一个矩形，是矩形左下脚与右上角的坐标。<br></p> 

 
 # 输出格式 
<p>
输出文件仅有一行，为与矩形相交的最大数目。<br></p> 

 
 # 提示 
<p>
对于100%的数据，有0< xmax, ymax <10^9，1<=N<=10000。<br></p> 
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
<tr><td>22 14 8
1 8 7 11
18 10 20 12
17 1 19 7
12 2 16 3
16 7 19 9
8 4 12 11
7 4 9 6
10 5 11 6
</td><td>
5
<img border="0" src="/source/joyoi/tyvj-2201/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjIwMS9wcm9ibGVtc19pbWFnZXMvMjU1MC8xMjU2LmpwZw==.jpg"></td></tr></table>
