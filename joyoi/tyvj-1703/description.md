# 

 
 # 题目背景 
石家庄二中&nbsp;真理检验杯NOIP模拟赛&nbsp;第二题&nbsp;2011.8<BR> 

 
 # 题目描述 
定义容抗Xi大小满足如下条件的一组电容为“电容序列”：<BR>·X1&nbsp;=&nbsp;1&nbsp;<BR>·Xm&nbsp;=&nbsp;n&nbsp;<BR>·X1&nbsp;&lt;&nbsp;X2&nbsp;&lt;&nbsp;...&nbsp;&lt;&nbsp;Xm-1&nbsp;&lt;&nbsp;Xm&nbsp;<BR>·对于每个k&nbsp;(2&lt;=k&lt;=m)&nbsp;都存在两个(不一定不相同)&nbsp;整数i和j&nbsp;(1&lt;=i,&nbsp;j&lt;=k-1)&nbsp;使得Xk=Xi+Xj&nbsp;<BR>你的任务是：给定一个整数n，找出符合上述定义，并使m最小的电容序列。<BR> 

 
 # 输入格式 
输入包含若干组数据。每组数据只包含一行：一个整数n&nbsp;(1&lt;=n&lt;=100).&nbsp;N=0代表着输入的结束。 

 
 # 输出格式 
对于每组数据，输出最小的m。 

 
 # 提示 
原题还要求输出一组可行解。<BR>但是由于TYVJ没有Special&nbsp;Judge功能，去掉了该问。<BR><BR>附样例具体答案：<BR>4&nbsp;&nbsp;&nbsp;1&nbsp;2&nbsp;3&nbsp;5<BR>5&nbsp;&nbsp;&nbsp;1&nbsp;2&nbsp;4&nbsp;6&nbsp;7<BR>5&nbsp;&nbsp;&nbsp;1&nbsp;2&nbsp;4&nbsp;8&nbsp;12<BR>6&nbsp;&nbsp;&nbsp;1&nbsp;2&nbsp;3&nbsp;5&nbsp;10&nbsp;15<BR>9&nbsp;&nbsp;&nbsp;1&nbsp;2&nbsp;4&nbsp;8&nbsp;9&nbsp;17&nbsp;34&nbsp;68&nbsp;77Poj2248 
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
7
12
15
77
0
</td><td>4
5
5
6
9
</td></tr></table>
