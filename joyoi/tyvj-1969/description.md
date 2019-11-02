# 

 
 # 题目背景 
George很喜欢数学，尤其是算数数系列。<BR> 

 
 # 题目描述 
他最喜欢的是数字的无穷序列，结果是把所有的自然数按升序排列。这个序列开始是：&nbsp;1234567891011121314...&nbsp;我们叫序列&nbsp;S。然后&nbsp;S[1]&nbsp;=&nbsp;1,&nbsp;S[2]&nbsp;=&nbsp;2,&nbsp;...&nbsp;,&nbsp;S[10]&nbsp;=&nbsp;1,&nbsp;S[11]&nbsp;=&nbsp;0,&nbsp;...&nbsp;,&nbsp;以此类推。&nbsp;<BR>George&nbsp;现有一个数字系列&nbsp;A&nbsp;，他想知道在S中最早出现的位置。帮助他解决这个难题。<BR> 

 
 # 输入格式 
输入文件包含&nbsp;A&nbsp;-&nbsp;给出的数字系列。位数不超过&nbsp;200。没有空格。<BR> 

 
 # 输出格式 
输出一个整数。-&nbsp;最小的&nbsp;k&nbsp;，使&nbsp;A[1]&nbsp;=&nbsp;S[k],&nbsp;A[2]&nbsp;=&nbsp;S[k+1],&nbsp;...&nbsp;A[len(A)]&nbsp;=&nbsp;S[k&nbsp;+&nbsp;len(A)&nbsp;－1],&nbsp;len(A)&nbsp;表示&nbsp;A&nbsp;的长度。<BR> 

 
 # 提示 
Ural&nbsp;State&nbsp;University&nbsp;Problem&nbsp;Archive<BR> 
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
<tr><td>101
</td><td>10
</td></tr></table>
