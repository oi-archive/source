# 

 
 # 题目背景 
广州市2011年市选第一试 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;相信大家都用过计算器，一般来说，计算机都可以计算简单的&nbsp;加、减、乘、除这几种运算。简易计算器的功能和一般的计算器一样，只是它更加简单，只能处理整数运算，也就是说，它没有小数点按钮，并且它的除法运算是整除运算。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在，我们给出简易计算器上的按钮序列，请你编程序，模拟简易计算器的功能，输出最终的结果。<BR>	<BR>【计算器组成】<BR>&nbsp;&nbsp;&nbsp;&nbsp;简易计算器由以下按钮组成：<BR>&nbsp;&nbsp;&nbsp;&nbsp;数字按钮：&nbsp;0&nbsp;1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6&nbsp;7&nbsp;8&nbsp;9<BR>&nbsp;&nbsp;&nbsp;&nbsp;运算按钮：&nbsp;+&nbsp;-&nbsp;*&nbsp;/&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;等于号按钮：=<BR>&nbsp;&nbsp;&nbsp;&nbsp;正负转换按钮：+/-&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;为了表述方便，+/-&nbsp;按钮用&nbsp;F&nbsp;表示&nbsp;，<BR><BR>【计算器逻辑处理】<BR>&nbsp;&nbsp;&nbsp;&nbsp;计算器内存有3个值，M1，M2，OP，ST<BR>&nbsp;&nbsp;&nbsp;&nbsp;M1为计算器的左运算值，初始值为0<BR>&nbsp;&nbsp;&nbsp;&nbsp;M2为计算器的右运算值，初始值0<BR>&nbsp;&nbsp;&nbsp;&nbsp;OP为计算器的当前运算符，初始值为空<BR>&nbsp;&nbsp;&nbsp;&nbsp;ST为状态标记，初始值为0<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;状态装换逻辑如下：<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;ST=0&nbsp;&nbsp;&nbsp;(M1/OP输入态)：<BR>&nbsp;&nbsp;&nbsp;&nbsp;显示值：M1<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入数字N&nbsp;：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M1=N&nbsp;，转&nbsp;ST=1状态<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入F&nbsp;：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M1=-M1，转&nbsp;ST=0状态<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入运算符：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OP=运算符，转ST=2状态<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入“=”：&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;转&nbsp;ST=0状态<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;ST=1&nbsp;&nbsp;&nbsp;(M1+/OP输入态)：<BR>&nbsp;&nbsp;&nbsp;&nbsp;显示值：M1<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入数字N&nbsp;：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果M1&gt;=0则&nbsp;M1=M1*10+N&nbsp;否则M1=M1*10-N;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;转&nbsp;ST=1状态；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入F&nbsp;：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M1=-M1，转&nbsp;ST=1状态；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入运算符：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OP=运算符，转ST=2状态<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入“=”：&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;转&nbsp;ST=0状态<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;ST=2&nbsp;&nbsp;&nbsp;(OP/M2输入态)：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;显示值：M1<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入数字N：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M2=N，转ST=3状态;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入F：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M2=0，转&nbsp;ST=3状态；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入运算符：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OP=运算符，转ST=2状态<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入“=”：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;转&nbsp;ST=0状态<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;ST=3&nbsp;&nbsp;&nbsp;(M2+/OP输入态)：<BR>&nbsp;&nbsp;&nbsp;&nbsp;显示值：M2<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入数字N：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果M2&gt;=0则&nbsp;M2=M2*10+N&nbsp;否则M2=M2*10-N；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;转ST=3状态；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入F：&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M2=-M2，转&nbsp;ST=3状态；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入运算符：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M1=[M1][OP][M2]&nbsp;的值<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OP=运算符；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;转ST=2状态&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入“=”：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M1=[M1][OP][M2]&nbsp;的值<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;转ST=0状态&nbsp;<BR><BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入只有一行，表示在计算器输入的按钮，长度&lt;=100，里面只包含如下字符&nbsp;:<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0123456789+-*/=F<BR>&nbsp;&nbsp;&nbsp;&nbsp;输入数据保证不会出现除以0的&nbsp;情况，运算过程中各个内存的值的范围在[-10000000,&nbsp;10000000]&nbsp;以内 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出包含一行整数，表示最后在计算器显示的结果<BR>&nbsp;&nbsp; 
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
<tr><td>123=*2F-+/3+-=
	 </td><td>-82
</td></tr></table>
