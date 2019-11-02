# 

 
 # 题目背景 
[noip2000T4]方格取数<BR> 

 
 # 题目描述 
设有N*N的方格图(N&lt;=10,我们将其中的某些方格中填入正整数,而其他的方格中则放入数字0。如下图所示（见样例）：<BR><img src="/source/joyoi/tyvj-1884/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTg4NC8mbmJzcDtodHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvUDEwMTcuanBn.jpg" border=0 align=middle><BR>某人从图的左上角的A&nbsp;点出发，可以向下行走，也可以向右走，直到到达右下角的B点。在走过的路上，他可以取走方格中的数（取走后的方格中将变为数字0）。<BR>此人从A点到B&nbsp;点共走两次，试找出2条这样的路径，使得取得的数之和为最大。<BR><BR> 

 
 # 输入格式 
输入的第一行为一个整数N（表示N*N的方格图），接下来的每行有三个整数，前两个表示位置，第三个数为该位置上所放的数。一行单独的0表示输入结束。 

 
 # 输出格式 
只需输出一个整数，表示2条路径上取得的最大的和。 
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
2 3 13
2 6 6
3 5 7
4 4 14
5 2 21 
5 6 4
6 3 15
7 2 14
0 0 0
</td><td>67</td></tr></table>
