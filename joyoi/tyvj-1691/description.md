# 

 
 # 题目背景 
全国信息学奥林匹克联赛（NOIP2011）复赛普及组第四题 

 
 # 题目描述 
对于&nbsp;1&nbsp;位二进制变量定义两种运算：<BR>运算符&nbsp;运算规则<BR>⊕&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⊕0=0<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⊕1=1<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⊕0=1<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⊕1=1<BR>×&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0×0=0<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0×1=0<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1×0=0<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1×1=1<BR>运算的优先级是：<BR>1.&nbsp;先计算括号内的，再计算括号外的。<BR>2.&nbsp;“×”运算优先于“⊕”运算，即计算表达式时，先计算×运算，再计算⊕运算。<BR>例如：计算表达式A⊕B&nbsp;×&nbsp;C&nbsp;时，先计算B&nbsp;×&nbsp;C，其结果再与A&nbsp;做⊕运算。<BR>现给定一个未完成的表达式，例如_+(_*_)，请你在横线处填入数字0&nbsp;或者1，请问有多少种填法可以使得表达式的值为0。<BR> 

 
 # 输入格式 
输入文件名为&nbsp;exp.in，共2&nbsp;行。<BR>第&nbsp;1&nbsp;行为一个整数L，表示给定的表达式中除去横线外的运算符和括号的个数。<BR>第&nbsp;2&nbsp;行为一个字符串包含L&nbsp;个字符，其中只包含’（’、’）’、’+’、’*’这4&nbsp;种字符，其中’（’、’）’是左右括号，’+’、’*’分别表示前面定义的运算符“⊕”和“×”。这行字符按顺序给出了给定表达式中除去变量外的运算符和括号。<BR> 

 
 # 输出格式 
输出文件&nbsp;exp.out&nbsp;共1&nbsp;行。包含一个整数，即所有的方案数。注意：这个数可能会很大，<BR>请输出方案数对10007&nbsp;取模后的结果。<BR> 

 
 # 提示 
【输入输出样例说明】<BR>给定的表达式包括横线字符之后为：_+(_*_)<BR>在横线位置填入(0、0、0)、(0、1、0)、(0、0、1)时，表达式的值均为0，所以共有3种填法。<BR>【数据范围】<BR>对于&nbsp;20%的数据有0&nbsp;≤L≤&nbsp;10。<BR>对于&nbsp;50%的数据有0&nbsp;≤L≤&nbsp;1,000。<BR>对于&nbsp;70%的数据有0&nbsp;≤L≤&nbsp;10,000。<BR>对于&nbsp;100%的数据有0&nbsp;≤L≤&nbsp;100,000。<BR>对于&nbsp;50%的数据输入表达式中不含括号。<BR>By&nbsp;wjy 
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
<tr><td>4
+(*)
</td><td>3
</td></tr></table>
