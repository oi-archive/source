# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;火车从始发站（称为第1站）开出，在始发站上车的人数为a，然后到达第2站，在第2站有人上、下车，但上、下车的人数相同，因此在第2站开出时（即在到达第3站之前）车上的人数保持为a人。从第3站起（包括第3站）上、下车的人数有一定规律：上车的人数都是前两站上车人数之和，而下车人数等于上一站上车人数，一直到终点站的前一站（第n-1站），都满足此规律。现给出的条件是：共有N个车站，始发站上车的人数为a，最后一站下车的人数是m（全部下车）。试问x站开出时车上的人数是多少？<BR>&nbsp;&nbsp;&nbsp;&nbsp;若无解则输出“No&nbsp;answer.” 

 
 # 输入格式 
输入a，n，m和x四个数<BR>0&lt;=a,m&lt;=10000<BR>0&lt;n,x&lt;=20<BR> 

 
 # 输出格式 
输出一个数x即站开出时车上的人数 
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
<tr><td>1 6 7 3</td><td>2</td></tr></table>
