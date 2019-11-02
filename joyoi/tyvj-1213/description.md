# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;有n个矩形，每个矩形可以用a,b来描述，表示长和宽。矩形X(a,b)可以嵌套在矩形Y(c,d)中当且仅当a&lt;c,b&lt;d或者b&lt;c,a&lt;d（相当于旋转X90度）。例如（1,5）可以嵌套在（6,2）内，但不能嵌套在（3,4）中。你的任务是选出尽可能多的矩形排成一行，使得除最后一个外，每一个矩形都可以嵌套在下一个矩形内。 

 
 # 输入格式 
第1行n&nbsp;(n&lt;=2000)<BR>第2到n+1行每行两个数a,b，表示这个矩形的长和宽 

 
 # 输出格式 
一个数，最多符合条件的矩形数目 
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
1 5
6 2
3 4</td><td>2</td></tr></table>
