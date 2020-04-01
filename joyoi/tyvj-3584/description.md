# 

 
 # 题目描述 
<p>
火车沿途有N个车站，告诉你从每一站到每一站的人数，现在查票员只能查K次票，每次查票可以控制目前在车上的所有乘客的车票。求一个查票方案，使得控制的不同的乘客尽量多。<br><br>（显然对同一个乘客查票多次是没有意义的，只算一次）<br><br></p> 

 
 # 输入格式 
<p>
<br><br>第一行正整数 N K (1≤K＜N≤600， K≤50).<br>接下来N-1行，第i行第j个数描述第i站上，到第i+j站下的乘客个数。总乘客数≤2*109<br><br></p> 

 
 # 输出格式 
<p>
<br><br>单调增的K个整数，用空格隔开，表示经过哪些站以后查票。<br></p> 
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
<tr><td>7 2

2 1 8 2 1 0

3 5 1 0 1

3 1 2 2

3 5 6

3 2

1
</td><td>
2 5
</td></tr></table>
