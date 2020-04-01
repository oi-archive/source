# 

 
 # 题目背景 
NOIP2007年提高组第一题 

 
 # 题目描述 
某次科研调查时得到了n个自然数，每个数均不超过1500000000（1.5*109）。已知不相同的数不超过10000个，现在需要统计这些自然数各自出现的次数，并按照自然数从小到大的顺序输出统计结果。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入包含n+1行：<BR>&nbsp;&nbsp;&nbsp;&nbsp;第1行是整数n，表示自然数的个数。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第2~n+1行每行一个自然数。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出包含m行（m为n个自然数中不相同数的个数），按照自然数从小到大的顺序输出。每行输出两个整数，分别是自然数和该数出现的次数，其间用一个空格隔开。 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;40%的数据满足：1&lt;=n&lt;=1000<BR>&nbsp;&nbsp;&nbsp;&nbsp;80%的数据满足：1&lt;=n&lt;=50000<BR>&nbsp;&nbsp;&nbsp;&nbsp;100%的数据满足：1&lt;=n&lt;=200000，每个数均不超过1&nbsp;500&nbsp;000&nbsp;000（1.5*10^9）<BR> 
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
2
4
2
4
5
100
2
100
</td><td>2 3
4 2
5 1
100 2
</td></tr></table>
