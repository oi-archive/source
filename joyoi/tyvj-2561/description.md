# 

 
 # 题目描述 
<p>
<br>农夫John发现他的奶牛产奶的质量一直在变动。经过细致的调查，他发现：虽然他不能预见明天<br>产奶的质量，但连续的若干天的质量有很多重叠。我们称之为一个“模式”。<br>John的牛奶按质量可以被赋予一个0到1000000之间的数。并且John记录了N(1<=N<=20000)天的<br>牛奶质量值。他想知道最长的出现了至少K(2<=K<=N)次的模式的长度。<br>比如1 2 3 2 3 2 3 1 中 2 3 2 3出现了两次。当K=2时，这个长度为4。<br></p> 

 
 # 输入格式 
<p>
* Line 1: 两个整数 N,K。<br><br>* Lines 2..N+1: 每行一个整数表示当天的质量值。<br></p> 

 
 # 输出格式 
<p>
* Line 1: 一个整数：N天中最长的出现了至少K次的模式的长度<br><br><br></p> 
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
<tr><td>
8 2
1
2
3
2
3
2
3
1
</td><td>4</td></tr></table>
