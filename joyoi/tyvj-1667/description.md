# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;递增总是一个优美的词，而一个串是字符串被定义为递增数列需要满足下列条件：<BR>&nbsp;&nbsp;&nbsp;&nbsp;字符串由逗号’,’和正整数组成。用逗号隔开的数字，依次严格上升，且第一位和最后一位不能有逗号，数字不能有前导零。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在给你一个包含问号’?’的串，问号可以用数字或者逗号代替，要求你把它变成一个递增数列，且字典序最小。如果无解则输出”impossible”。 

 
 # 输入格式 
一个未完成的串，包含若干个’?’。 

 
 # 输出格式 
一个串，合法的最小字典序的串。或者是”impossible”。 

 
 # 提示 
数据规模：串长度≤50。<BR>注意事项：数字不能为空，也就是逗号不能并在一起。<BR>空间限制：64MB清北学堂杯2011NovTyvj月赛(提高组难度)第二题 
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
<tr><td>?????????,9</td><td>1,2,3,4,5,9</td></tr></table>
