# 

 
 # 题目描述 
直接看输入输出格式吧~<br> 

 
 # 输入格式 
第一行一个数字N<br>	接下来N行,&nbsp;每行X，Y<br><br> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;每个X都可以看做是个二进制拆分,1表示有，0表示无，所以这个二进制可以表示成位置的集合，对于每个X，Y输出属于这个X但不属于在这之前刚输入的Y个X的子集个数(空集不计入）。<br><br> 

 
 # 提示 
&nbsp;1&lt;N&lt;60000,&nbsp;0&lt;X&lt;60000,&nbsp;Y&lt;=已输入的个数。数据保证每个X都不一样。<br><br>&nbsp;单个测试点包含多组数据！<br><br>zanoes原创<br><br> 
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
7 0
15 1
3 1
3
7 0
15 1
3 1

</td><td>7
8
0
7
8
0

</td></tr></table>
