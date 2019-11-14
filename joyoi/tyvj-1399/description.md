# 

 
 # 题目背景 
话说有这么一个神牛Big&nbsp;Hui... 

 
 # 题目描述 
　　Big&nbsp;Hui闲得没事，于是学了一门新的语言big，big的语法是这样的：对于每一个正确的big语言的表达式，包含算术表达式，注释,符号部分。<BR>　　其中，注释优先级最高。其次是括号内的算术表达式。<BR>　　注释可以出现在任何地方，注释内可以是任何字符。注释的开头用"(*"表示，结束用&nbsp;"*)"表示。每一个注释必须有结束标志。<BR>　　一个算术表达式是用"(",")"括起，可以包含以下字符："=+-*/0123456789)("&nbsp;,当然可以有注释在其中。&nbsp;算术表达式中不允许有空格，可以有回车符。算术表达式中可以嵌套括号，但括号必须匹配。即诸如：&nbsp;"((1)))"&nbsp;，"(23))((+)"&nbsp;等不是合法的。当且仅当括号匹配正确，表达式才是正确的。<BR>　　其他（也就是不是以上二种）字符文字可以是除"("&nbsp;和")"外的字符。&nbsp;<BR>　　另外特别指出，除了不能在算术表达式中出现外，空格在程序的任一地方出现是可能的。<BR>　　Big&nbsp;Hui身为一个OIer自然可以偷懒了，所以Big&nbsp;Hui会随手写个代码，来判断一个big语言是否正确。 

 
 # 输入格式 
第一行一个整数n;<BR>接下来有n个段落，每个段落（若干行）的结尾为一行000。 

 
 # 输出格式 
N行;<BR>每行输出‘YES’（表示该段表达式正确）或输出‘NO’（表示错误）<BR> 
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
<tr><td>1
Hello, here is a sample big xxxx. It contains some arithmetical expressions like
(2+2=4), (2+-/*) and ((3+3)*3=20(*this is not true, but you don't have to verify it :-) *)+8)
(* the closing bracket in the previous comment is also in order, since this bracket
does not belong to any arithmetical expression*)
000
</td><td>YES
</td></tr></table>
