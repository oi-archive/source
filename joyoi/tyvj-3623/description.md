# 

 
 # 题目描述 
<p>
在一个无限大小的网格上有N个矩形，给定每个矩形的坐标x1,y1,x2,y2。在源点处有油渗出，时刻0时覆盖(0,0)格，之后每秒钟会向周围8个方向各延伸1格。给定M个询问，回答相应时刻时所有矩形被覆盖的面积之和。若同一格被不同矩形覆盖，则需要多次计算。没有矩形覆盖(0,0)格。<br>N,M≤100000。<br>-1000000≤x1≤x2≤1000000，-1000000≤y1≤y2≤1000000。<br>询问的时刻不超过1000000。<br><br></p> 

 
 # 输入格式 
<p>
</p> 

 
 # 输出格式 
<p>
</p> 
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
<tr><td>3
-2 1 1 2
1 0 2 1
-3 -3 -2 0
2
1 2
</td><td>
5
15
</td></tr></table>
