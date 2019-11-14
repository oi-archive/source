# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2384/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjM4NC9wcm9ibGVtc19pbWFnZXMvMjc3Ny8xNTAyXzEuanBn.jpg"></p> 

 
 # 输入格式 
<p>
文件的第1行包含一个整数n和一个实数alpha，表示柠檬树的层数和月亮的光线与地面夹角(单位为弧度)。<br>第2行包含n+1个实数h0,h1,h2,…,hn，表示树离地的高度和每层的高度。<br>第3行包含n个实数r1,r2,…,rn，表示柠檬树每层下底面的圆的半径。<br>上述输入文件中的数据，同一行相邻的两个数之间用一个空格分隔。<br>输入的所有实数的小数点后可能包含1至10位有效数字。<br><br></p> 

 
 # 输出格式 
<p>
输出1个实数，表示树影的面积。四舍五入保留两位小数。<br><br></p> 

 
 # 提示 
<p>
1≤n≤500，0.3<alpha<π/2，0<hi≤100，0<ri≤100。<br>10%的数据中，n=1。<br>30%的数据中，n≤2。<br>60%的数据中，n≤20。<br>100%的数据中，n≤500。<br></p> 
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
<tr><td>2 0.7853981633
10.0 10.00 10.00
4.00 5.00
</td><td>171.97</td></tr></table>
