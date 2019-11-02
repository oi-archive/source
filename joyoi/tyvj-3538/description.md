# 

 
 # 题目描述 
<p>
　　一个农夫要把n只马分配到k个马房里，放置的规则是：第1 到 第pi只马放入第一个马房，第pi+1 到第pk只放入第二个马房，......，以此类推。此外对于每一个马房都有一个叫做“不高兴系数”，即白色马的数量*黑色马的数量。你的任务是合理地分配这n只马，使得它所有马房的“不高兴系数”和最小。 <br></p> 

 
 # 输入格式 
<p>
　　从文件horses.in中读入数据，文件中第一行有 2 个整数：  n ( 1 <= n <= 500 ) 和  k ( 1 <= k <= n)。接下来的n行有n个数。第 i 行为第 i 只马的颜色： 1 是黑色， 0 是白色。 <br></p> 

 
 # 输出格式 
<p>
　　将结果输出到文件horses.out中，其结果为最小的“不高兴系数”的总和。<br></p> 
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
<tr><td>6 3
1
1
0
1
0
1
</td><td>2</td></tr></table>
