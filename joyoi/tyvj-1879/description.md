# 

 
 # 题目描述 
给定一个信封，最多只允许粘贴N张邮票，计算在给定K（N+K≤40）种邮票的情况下（假定所有的邮票数量都足够），如何设计邮票的面值，能得到最大值MAX，使在1～MAX之间的每一个邮资值都能得到。<BR>&nbsp;&nbsp;&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;例如，N=3，K=2，如果面值分别为1分、4分，则在1分～6分之间的每一个邮资值都能得到（当然还有8分、9分和12分）；如果面值分别为1分、3分，则在1分～7分之间的每一个邮资值都能得到。可以验证当N=3，K=2时，7分就是可以得到的连续的邮资最大值，所以MAX=7，面值分别为1分、3分。<BR>&nbsp;&nbsp;&nbsp;&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 

 
 # 输入格式 
第一行两个数n,k 

 
 # 输出格式 
第一行&nbsp;你选择的面值<BR>第二行&nbsp;你能取得的最大值MAX= 
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
<tr><td>3 2</td><td>1  3
MAX=7
</td></tr></table>
