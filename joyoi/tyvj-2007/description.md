# 

 
 # 题目描述 
设F[i]为斐波那契数列的第i项，F[1]=1,F[2]=1,F[i]=F[i-1]+F[i-2](i&gt;=3)。<br> 

 
 # 输入格式 
输入包含若干行（不多于10行），以EOF结尾。每行包含两个整数a,b。<br> 

 
 # 输出格式 
对于每一行输入，如果F[a]能整除F[b]，输出1，否则输出0.<br> 

 
 # 提示 
对于20%的数据，1&lt;=a,b&lt;=91。<br>对于50%的数据，1&lt;=a&lt;=91,1&lt;=b&lt;=1000。<br>对于100%的数据，1&lt;=a,b&lt;=1000000。<br> 
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
<tr><td>3 7
4 8
5 5
</td><td>0
1
1
</td></tr></table>
