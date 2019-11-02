# 

 
 # 题目描述 
在以后的若干天里戴维将学习美元与德国马克的汇率。编写程序帮助戴维何时应买或卖马克或美元，使他从100美元开始，最后能获得最高可能的价值。 

 
 # 输入格式 
输入文件的第一行是一个自然数N，1≤N≤100，表示戴维学习汇率的天数。<BR>接下来的N行中每行是一个自然数A，1≤A≤1000。第i+1行的A表示预先知道的第i+1天的平均汇率，在这一天中，戴维既能用100美元买A马克也能用A马克购买100美元。<BR> 

 
 # 输出格式 
输出文件的第一行也是唯一的一行应输出要求的钱数(单位为美元，保留两位小数)。 

 
 # 提示 
Day&nbsp;1&nbsp;...&nbsp;changing&nbsp;100.0000&nbsp;美元=&nbsp;400.0000&nbsp;马克<BR>Day&nbsp;2&nbsp;...&nbsp;changing&nbsp;400.0000&nbsp;马克=&nbsp;133.3333&nbsp;美元<BR>Day&nbsp;3&nbsp;...&nbsp;changing&nbsp;133.3333&nbsp;美元=&nbsp;666.6666&nbsp;马克<BR>Day&nbsp;5&nbsp;...&nbsp;changing&nbsp;666.6666&nbsp;马克=&nbsp;266.6666&nbsp;美元<BR> 
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
<tr><td>5
400
300
500
300
250
</td><td>266.67</td></tr></table>
