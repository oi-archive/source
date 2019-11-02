# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;后勤部队运来一批武器（机枪和盔甲）。你要把这些武器分配给手下的marine们（每人一部机枪，一套盔甲）。可是问题来了。。。<br>&nbsp;&nbsp;&nbsp;&nbsp;这些武器的型号不相同（武器是由出价最低的承包商制造的），把一部m型的机枪和一套n型的盔甲分配给一个marine得到的不满意值为(m-n)^2（每个marine当然希望自己得到的武器是同一型号的）。<br>&nbsp;&nbsp;&nbsp;&nbsp;你的任务就是把a部机枪和b套盔甲分配给手下n个marine。使他们的不满意值之和最小。<br> 

 
 # 输入格式 
第一行：3&nbsp;个正整数&nbsp;n&nbsp;,&nbsp;a&nbsp;,&nbsp;b&nbsp;(1&lt;=n&lt;=a,b&lt;=80)<br>第二行：a&nbsp;个数表示每部机枪的型号<br>第三行：b&nbsp;个数表示每套盔甲的型号<br>0&lt;=型号值&lt;=10000<br> 

 
 # 输出格式 
输出一个数：最小不满意值。<br> 
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
<tr><td>Sample 1：
2 3 3
9 10 20
0 10 11
Sample 2：
3 4 4
3 9 7 4
4 2 5 5
</td><td>Sample 1：
2
Sample 2：
5
</td></tr></table>
