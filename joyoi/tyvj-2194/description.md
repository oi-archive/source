# 

 
 # 题目描述 
<p>
给你凸包上的N个点（保证是很普通的凸包）。给你M条直线，每次询问你这条直线把凸包切成的两部分中，较小的一部分的面积。如果这条直线没把凸包切成两部分，则输出0。 <br>输入文件： <br>第一行一个数N。如题所述。(n<=100000) <br>接下来N行，每行两个实数，表示一个凸包上的点的坐标。 <br>一个数M。如题所述。（m<=100000） <br>接下来M行，每行4个实数x1,y1,x2,y2，描述一条经过(x1,y1),(x2,y2)的直线。 <br></p> 

 
 # 输入格式 
<p>
M行，对于每条直线<br></p> 

 
 # 输出格式 
<p>
给出询问的答案，保留6位小数。 <br><br></p> 
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
1 1
0 1
1 0
2
-1 -1 2 2
0.5 -1 0.5 1

</td><td>
0.500000
0.500000

</td></tr></table>
