# 

 
 # 题目描述 
有一个m*m（m&lt;=20）的方格纸，其中有n*n个（n&lt;=m，n&lt;=6）放个标有“*”的记号，标有“*”的方格是联通的。<BR>所谓的联通是指：假设有一个“车”在一个标有“*”的方格上，每次移动只能移动与原方格垂直相邻或水平相邻的标有“*”的方格上，经过有限次移动，“车”车可以到达任意另一个标有“*”的方格。（如下图）<BR><img src="/source/joyoi/tyvj-1829/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTgyOS9Qcm9ibGVtSW1nLzE4MjlfMS5qcGc=.jpg" border=0 align=middle><BR>现在要把这标有“*”的n*n方格分成A、B两部分，每部分都是联通的，而且这两部分经过旋转，翻转或平移之后可以拼成n*n的正方形。（若有多解，请给出任何一个）<BR>例如上例，可以分成如下两部分，且这两部分可以拼成4*4正方形。<BR><img src="/source/joyoi/tyvj-1829/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTgyOS9Qcm9ibGVtSW1nLzE4MjlfMi5qcGc=.jpg" border=0 align=middle> 

 
 # 输入格式 
文件第一行有一个整数m，以下m行每行各有m个字符：“.”代表空格，“*”代表标有“*”记号方格。 

 
 # 输出格式 
共m行每行为m个字符：“.”代表空格，“A”、“B”分别代表分割成两部分的组成方格。 
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
<tr><td>8
........
....*...
..*.*...
..***...
..****..
..*..*..
..****..
........
</td><td>........
....B...
..B.B...
..BBB...
..AABA..
..A..A..
..AAAA..
........
</td></tr></table>
