# 

 
 # 题目背景 
USACO&nbsp;OCT09&nbsp;8TH&nbsp; 

 
 # 题目描述 
Bessie像她的诸多姊妹一样，因為从Farmer&nbsp;John的草地吃了太多美味的草而长出了太多的赘肉。所以FJ将她置於一个及其严格的节食计划之中。她每天不能吃多过H&nbsp;(5&nbsp;&lt;=&nbsp;H&nbsp;&lt;=&nbsp;45,000)公斤的乾草。<BR><BR>Bessie只能吃一整綑乾草；当她开始吃一綑乾草的之后就再也停不下来了。她有一个完整的N&nbsp;(1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;500)綑可以给她当作晚餐的乾草的清单。她自然想要尽量吃到更多的乾草。很自然地，每綑乾草只能被吃一次（即使在列表中相同的重量可能出现2次，但是这表示的是两綑乾草，其中每綑乾草最多只能被吃掉一次）。<BR><BR>给定一个列表表示每綑乾草的重量S_i&nbsp;(1&nbsp;&lt;=&nbsp;S_i&nbsp;&lt;=&nbsp;H),&nbsp;求Bessie不超过节食的限制的前提下可以吃掉多少乾草（注意一旦她开始吃一綑乾草就会把那一綑乾草全部吃完）。 

 
 # 输入格式 
*&nbsp;第一行:&nbsp;两个由空格隔开的整数:&nbsp;H&nbsp;和&nbsp;N<BR><BR>*&nbsp;第2到第N+1行:&nbsp;第i+1行是一个单独的整数，表示第i綑乾草的重量S_i。<BR> 

 
 # 输出格式 
*&nbsp;第一行:&nbsp;一个单独的整数表示Bessie在限制范围内最多可以吃多少公斤的乾草。<BR><BR><BR><BR> 
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
<tr><td>56 4
15
19
20
21

</td><td>56
</td></tr></table>
