# 

 
 # 题目描述 
<p>
　　剔除四则运算表达式中的多余括号<br>　　输入一个含有括号的四则运算表达式，可能含有多余的括号，编程整理该表达式，去掉所有多余的括号，原表达式中所有变量和运算符号相对位置保持不变，并保持与原表达式等价。<br><br>输入表达式　　　　　　　　输出表达式<br>a+(b+c)　　　　　　  　　　a+b+c<br>(a*b)+c/(d*e)　　　　　　　a*b+c/(d*e)<br>a+b/(c-d)	　　　　　　　　　a+b/(c-d)<br>a-(b+c)　　　　　　　　　  a-(b+c)<br><br>　　注意：输入为a+b时，输出不能是b+a，即相对位置不能变。表达式以字符串输入，长度不超过255，不需要对输入表达式判断是否格式正确（即，程序应该默认输入表达式是格式正确的），所有变量均为单个小写字母，只要去掉所有多余括号，不要求对表达式简化。<br></p> 

 
 # 输入格式 
<p>
</p> 

 
 # 输出格式 
<p>
</p> 
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
<tr><td>a+(b+c)</td><td>a+b+c</td></tr></table>
