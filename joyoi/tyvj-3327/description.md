# 

 
 # 题目描述 
<p>
【问题描述】<br>　　在直角坐标系上，有一个小球开始从坐标(x,y) x > 0,y > 0 处直线下落，每一秒钟一个单位距离，一直到X轴为止。然而，它可能在下落过程中碰到一些障碍物。障碍物可以看成是一些平行于X轴的水平线段，如果小球的Y坐标和障碍物的Y坐标相等，而X坐标在障碍物的两个端点X坐标之间（包括两个端点），这样小球就会延时5秒然后从障碍物的右端继续下落。<br>　　现给出小球的初始坐标 (x,y) ，以及每个障碍物的数据（三个整数 y x1 x2，分别表示这个障碍物的Y坐标，左、右端点的X坐标），编程求小球要几称钟才能到达X轴上。<br></p> 

 
 # 输入格式 
<p>
　　第一行有两个整数x y表示小球初始坐标，1 <= x,y <= 1000。第二行有一个整数n(n < 100),表示有n个障碍物。<br>下面有n行，每行三个整数（都在1到999之间），分别表示一个障碍物的数据(y x1 x2)，其中x1<=x2。障碍物的高度都不相同。<br></p> 

 
 # 输出格式 
<p>
　　只一个整数，小球下落到X轴的秒数。<br></p> 

 
 # 提示 
<p>
【输入输出样例2】<br>fall.in<br>15 12<br>3<br>10 10 20<br>15 10 20<br>5 20 50<br><br>fall.out<br>22<br><br><br>【输入输出样例3】<br>fall.in<br>50 80<br>3<br>20 001 100<br>10 100 100<br>5 100 200<br><br>fall.out<br>95<br></p> 
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
<tr><td>fall.in
15 10
1
5 10  20
</td><td>fall.out
15</td></tr></table>
