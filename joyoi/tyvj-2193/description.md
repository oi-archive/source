# 

 
 # 题目描述 
<p>
平面上最开始只包含3个点，然后还会依次出现N个点。每新增一个点，请你求出包含这些点的周长最小的多边形的面积（也就是凸包的面积）。 <br><br></p> 

 
 # 输入格式 
<p>
第一行为6个整数，表示最初的三个点的坐标(x1,y1),(x2,y2),(x3,y3)。 <br>第二行仅一个数N。 <br>以下N行，每行两个整数(xi,yi)，表示新增的点的坐标。 <br><br></p> 

 
 # 输出格式 
<p>
对于每次新增点的操作，请你输出新增完此点后当前的凸包的面积的两倍。 <br><br></p> 

 
 # 提示 
<p>
N<=100000<br>点的坐标巨大,目测在[-10^9,10^9]</p> 
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
<tr><td>0 0 0 2 2 0
3
2 2
1 1
2 4

</td><td>
8
8
12

</td></tr></table>
