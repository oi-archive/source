# 

 
 # 题目描述 
<p>
由于Micky Mouse在Disney Land的出色表现，国王准备给他分一块地，使他能够有一个足够的空间发展自己。但是，国王也要趁机考一下Micky。他没直接给出地的范围，而是给了Micky地图上的一些点(没有三个点在同一直线上)，要求Micky任选三个点，Micky所得到的地就是过这三点的一个圆。Micky想知道，他怎样选择三点，可以使圆的面积最大。<br></p> 

 
 # 输入格式 
<p>
第一行有一个整数n，表示点的总数，接下来n行，每行两个整数，为国王给出的点的坐标。<br><br>1≤n≤655，0≤坐标值≤32767，<br></p> 

 
 # 输出格式 
<p>
你所得到的圆的半径(精确到小数点后3位)。</p> 
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
<tr><td>4
0 0
1 0
1 1
3 1	</td><td>3.536
说明：选(0,0),(1,0),(3,1)三点。</td></tr></table>
