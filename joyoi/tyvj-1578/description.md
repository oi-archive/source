# 

 
 # 题目描述 
给出一个长度为n的数列Ai。现有如下两种操作：<BR>（1）把数列中第i个数改为x<BR>（2）给出一个i，问数列中有多少个j满足第i个数和第j个数之间所有的数都不超过max(Ai,Aj)。<BR>给出m个操作，请对每个询问操作做出回答。<BR> 

 
 # 输入格式 
第一行两个正整数n、m。<BR>随后n行，每行一个正整数Ai。<BR>随后m行，若是修改操作，则以一个大写C开头，随后两个正整数i和x；若是查询操作，则以一个大写Q开头，随后一个正整数i。<BR> 

 
 # 输出格式 
每行一个正整数，请对所有询问操作按顺序给出回答。 

 
 # 提示 
对于40%的数据，n、m&lt;=5000；<BR>对于100%的数据，n、m&lt;=50000，|Ai|、x&lt;=100000。时限2秒。<BR> 
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
<tr><td>5 3
1
3
2
3
2
Q 1
C 1 3
Q 1
</td><td>2
4
</td></tr></table>
