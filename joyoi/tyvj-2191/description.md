# 

 
 # 题目描述 
<p>
Mickey坐在已经升空的飞机上俯瞰大地，他发现土地被分成了很多个不同的矩形状，且由于覆盖的植被不同而显出不同的颜色。Mickey想寻找一个最大的矩形，它里面只显出一种颜色。在以下几张图中你可以看见样例中的几幅图，其中最终的答案区域已经被标记了出来。<br> <br><img border="0" src="/source/joyoi/tyvj-2191/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjE5MS9wcm9ibGVtc19pbWFnZXMvMjUzOS8xMjQ1XzEuanBn.jpg"><br>请你编写一个程序计算一下所能看到的这样的矩形的面积，当然你可以放心，没有任何两块会互相重叠，然而二个矩形之间允许有共同点或公共边。<br><br></p> 

 
 # 输入格式 
<p>
输入文件的第一行将包含一个数字N, 1 ≤ N ≤ 2500,它代表着土地上一共有N个矩形块。<br>接下来的N行中，每行都将有5个整数，依次记作X1,Y1,X2,Y2和C，其中X1<X2,Y1<Y2。<br>这些数字描绘了由(X1,Y1),(X2,Y2)围成的这样一个矩形块里显示出了颜色C, 1 ≤ C ≤ 100。我们保证X1,Y1,X2,Y2的值都在0到1,000,000,000之间（包含0和1,000,000,000）。<br><br></p> 

 
 # 输出格式 
<p>
输出文件应该只有一行，请输出如上题描述中的最大的矩形的面积。<br><br>注意<br>得出的答案数据范围在64位整型数以内，也就是Pascal的int64，C/C++的long long 以内。<br><br></p> 
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
<tr><td>5 
1 1 3 3 1 
3 1 5 3 1 
1 4 3 6 1 
3 4 5 6 1 
0 3 6 4 2

</td><td>
8 
</td></tr></table>
