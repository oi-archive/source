# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2616/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYxNi9wcm9ibGVtc19pbWFnZXMvMzA1Ny8xNzg0XzEuanBn.jpg"> <br><br><img border="0" src="/source/joyoi/tyvj-2616/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYxNi9wcm9ibGVtc19pbWFnZXMvMzA1Ny8xNzg0XzIuanBn.jpg"> <br><br><img border="0" src="/source/joyoi/tyvj-2616/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYxNi9wcm9ibGVtc19pbWFnZXMvMzA1Ny8xNzg0XzMuanBn.jpg"> <br>一个字符矩阵，'.'为海洋，'A'为主岛，'x'为其它岛，保证所有'A'构成一个联通块，画一个圈，使得所有的'A'在圈内，所有的'x'在圈外，更具体的看样例，求这样的圈的最小周长</p> 

 
 # 输入格式 
<p>
Line 1: Two space-separated integers: H and W<br><br>* Lines 2..H+1: Line i+1 contains contains W characters that are the<br>        elements of map row i (all '.' or 'x' or 'A')<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The minimum length of a path that Farmer John's cruise ship<br>        can take<br></p> 
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
<tr><td>12 19
...................
...................
.....A.............
.....A..x..........
..x..A.....AAAA....
.....A.....A..A....
.....AAAAAAAA.A....
........A.....A....
.xx...AAA...x.A....
......A............
...AAAAAAAAAAAAA...
...................


</td><td>62</td></tr></table>
