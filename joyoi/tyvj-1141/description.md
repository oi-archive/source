# 

 
 # 题目背景 
Tiny&nbsp;Basm语言 

 
 # 题目描述 
Tiny&nbsp;Basm语言(简称为TB语言)的巴科斯-瑙尔范式(BNF)为：&nbsp;<BR>&lt;程序&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;&lt;语句&gt;&nbsp;@{&nbsp;&lt;语句&gt;&nbsp;@&nbsp;}&nbsp;<BR><BR>&lt;语句&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;&lt;行号&gt;&nbsp;#&nbsp;&lt;语句体&gt;&nbsp;<BR><BR>&lt;语句体&gt;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;&lt;累加语句&gt;&nbsp;|&nbsp;&lt;输出语句&gt;&nbsp;|&nbsp;&lt;转移语句&gt;&nbsp;|&nbsp;&lt;条件语句&gt;&nbsp;|&nbsp;&lt;结束语句&gt;&nbsp;<BR><BR>&lt;累加语句&gt;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;&lt;变量&gt;&nbsp;+&nbsp;&lt;整数&gt;&nbsp;<BR><BR>&lt;输出语句&gt;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;&lt;变量&gt;&nbsp;?<BR><BR>&lt;转移语句&gt;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;GO&nbsp;#&nbsp;&lt;行号&gt;&nbsp;<BR><BR>&lt;条件语句&gt;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;IF&nbsp;#&nbsp;&lt;变量&gt;&nbsp;=&nbsp;&lt;整数&gt;&nbsp;#&nbsp;&lt;转移语句&gt;&nbsp;<BR><BR>&lt;结束语句&gt;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;END&nbsp;<BR><BR>&lt;变量&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;&lt;字母&gt;&nbsp;<BR><BR>&lt;行号&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;&lt;整数&gt;&nbsp;<BR><BR>&lt;整数&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;&lt;数字&gt;&nbsp;{&nbsp;&lt;数字&gt;&nbsp;}&nbsp;<BR><BR>&lt;字母&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z&nbsp;<BR><BR>&lt;数字&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;::=&nbsp;0|1|2|3|4|5|6|7|8|9&nbsp;<BR><BR>注：其中“::=”表示定义为，“|”表示或，{}内的项可以重复任意多次或不出现，“#”表示空格(一个字符，ASCII码为32)，“@”表示回车/换行(两个字符，ASCII码分别为13和10)。&nbsp;<BR><BR>&nbsp;&nbsp;<BR><BR>错误语句示例(在输入文件中不会出现任何错误语句)：&nbsp;<BR><BR>10#A+1.5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（不符合累加语句的定义，所加的不是整数）&nbsp;<BR><BR>20#A#?&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（不符合输出语句的定义，多加了一个空格）&nbsp;<BR><BR>30#IF#A=B#GO#10&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（不符合条件语句的定义，不应变量=变量）&nbsp;<BR><BR>&nbsp;&nbsp;<BR><BR>TB程序的执行：&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;程序从行号最小的一条语句开始执行，在未遇到条件语句时按行号由小至大顺序执行。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;所有变量在程序执行前被自动初始化为0。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;累加语句将语句中变量的值加上语句中的整数送回该变量。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输出语句将语句中变量的值在监视器上显示出来。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;执行条件语句时，当且仅当该语句中的变量与紧跟在等号后面的整数值相等，后面的转移语句才被执行。该语句中的所有整数值至多为4位。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;转移语句被执行后，程序将转去执行GO后面指定的行号的语句。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当程序执行结束语句后，结束整个程序的执行。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;假设该系统能处理任意大小的整数，而不会发生溢出。&nbsp;<BR><BR>&nbsp;&nbsp;<BR><BR>请编程，对于给定的TB语言程序P，求该程序所执行的语句数(执行条件语句不论是否成功转移，仅记为执行一条语句)。&nbsp;<BR><BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输入为一个TB语言程序P，语句数不超过100行。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;P中每条语句的长度不超过20个字符。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;P中转移语句里GO后面的行号一定有对应的语句。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;P中可能有多个不同行号的结束语句。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;P中行号最大的语句一定是结束语句。&nbsp;<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;P中的行号都不大于3000。&nbsp;<BR><BR>输入文件不一定是按行号递增顺序给出P的。&nbsp;<BR>当一行只有一个数-1时，表示一组数据输入结束<BR> 

 
 # 输出格式 
输出文件有且仅有一行：<BR><BR>如果程序能够正常结束，输出该程序所执行的语句数；<BR><BR>如果程序不能正常结束，输出-1<BR><BR> 

 
 # 提示 
NOI2000 
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
<tr><td>10 A+1
20 IF A=5 GO 60
60 END
30 A+2
40 A?
50 GO 20
-1
</td><td>11
</td></tr></table>
