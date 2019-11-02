# 

 
 # 题目描述 
TsyD学习了生物的生态环境那一张后，老师留了一项作业，就是给一张食物网，求所有食物链的总数。（从最低营养级生物（它不能吃任何其他的生物）开始到最高营养级（它不能被任何其他生物吃）&nbsp;叫做一条食物链）<BR>	输入保证所有的生物之间都有直接或间接的生存关系<BR> 

 
 # 输入格式 
第一行&nbsp;N,M&nbsp;分别表示有N（N&lt;=50000）个生物，M(M&lt;=100000)个吃的关系<BR>接下来M行&nbsp;每行有两个值a，b&nbsp;分别&nbsp;表示b吃a&nbsp;（编号从1开始）<BR> 

 
 # 输出格式 
食物链的总数&nbsp;MOD&nbsp;11129&nbsp;的值 

 
 # 提示 
样例解释：<BR>两条食物链分别为&nbsp;1-&gt;3<BR>		&nbsp;1-&gt;2-&gt;3 
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
<tr><td>3 3
1 2
2 3
1 3
</td><td>2</td></tr></table>
