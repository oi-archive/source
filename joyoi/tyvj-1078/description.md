# 

 
 # 题目描述 
有N个不同的正整数数x1,&nbsp;x2,&nbsp;...&nbsp;xN&nbsp;排成一排，我们可以从左边或右边去掉连续的i个数（只能从两边删除数），1&lt;=i&lt;=n，剩下N-i个数，再把剩下的数按以上操作处理，直到所有的数都被删除为止。<BR>每次操作都有一个操作价值，比如现在要删除从i位置到k位置上的所有的数。操作价值为|xi&nbsp;–&nbsp;xk|*(k-i+1)，如果只去掉一个数，操作价值为这个数的值。<BR>任务<BR>如何操作可以得到最大值，求操作的最大价值。&nbsp; 

 
 # 输入格式 
输入文件remove.in&nbsp;的第一行为一个正整数N，第二行有N个用空格隔开的N个不同的正整数。<BR>3&lt;=N&lt;=100,N个操作数为1..1000&nbsp;之间的整数。 

 
 # 输出格式 
输出文件remove.out&nbsp;包含一个正整数，为操作的最大值 
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
<tr><td>6
54 29 196 21 133 118</td><td>768</td></tr></table>
