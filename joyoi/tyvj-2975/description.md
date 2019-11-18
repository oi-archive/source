# 

 
 # 题目描述 
<p>
给出平面上n个点的坐标，你可以安放一个探照灯。探照灯可以照亮一个夹角为π/6（30度），半径为d的扇形区域。你可以从给出的n个点中选择任意一个作为圆心，以任意角度摆放。问最多能照亮多少个点（包括圆心）。</p> 

 
 # 输入格式 
<p>
输入包含多组数据，以EOF结束。<br>对于每组数据，第一行是两个整数n和d。接下来n行每行有两个整数x和y，表示一个点的坐标。1 ≤ n ≤ 1000, 0 < d < 40000, -10000 ≤ x, y ≤ 10000。<br></p> 

 
 # 输出格式 
<p>
对于每组数据，输出一行，能照亮的点的最大值。</p> 
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
<tr><td>3 10
1 1
1 0
2 1
4 10
1 1
1 0
2 1
3 1
</td><td>2
4</td></tr></table>
