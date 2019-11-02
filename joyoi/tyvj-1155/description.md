# 

 
 # 题目描述 
考虑一下定义在非负整数n上的递推关系：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;f0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当n=0时<BR>F(n)=&nbsp;|&nbsp;f1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当n=1时<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;a*F(n-1)+b*F(n-2)&nbsp;&nbsp;其它<BR><BR>给定f0,f1,a,b,n,写一个程序计算F(n)，-10^9≤F(n)≤10^9（四舍五入），保证一定有解。 

 
 # 输入格式 
一行有五个数，f0,f1,a,b,n。-10^9≤n,f0,f1≤10^9，10^6≤a,b≤10^6。<BR>a,b是实数，n,f0,f1是整数。 

 
 # 输出格式 
一个数F(n)。 
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
<tr><td>样例1：0 1 1 1 20

样例2：0 1 -1 0 1000000000

样例3：-1 1 4 -3 18
</td><td>样例1：6765

样例2：-1

样例3：387420487
</td></tr></table>
