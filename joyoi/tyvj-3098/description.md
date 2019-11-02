# 

 
 # 题目描述 
<p>
【问题描述】<br><br>    LISP语言使用一种S表达式来表示程序和数据，一个S表达式可以简单地定义为：<br>    ＊	单个字母（大写或小写）是一个S表达式；<br>    ＊	如果U和V是S表达式，则（U，V）也是S表达式；<br>    例如，根据上述定义的第一条，单个字母a、c和m分别是一个合法的S表达式。而根据第二条，（a,c）和((a,c),m)也是合法的S表达式。<br>    你的任务是，根据定义，判断输入的表达式是否为合法的S表达式。<br><br><br></p> 

 
 # 输入格式 
<p>
  数据存放在当前目录下的文本文件“sexp.in”中。<br>文件的第一行是一个整数n,表示待判别的表达式的个数。以下n行，每行是一个字符串，表示待判别的表达式，字符串的前或后可能会有多余的空格，每行不超过72个字符。</p> 

 
 # 输出格式 
<p>
  答案输出到当前目录下的文本文件“sexp.out”中。<br>第一行输出表达式的个数。以下共有n行，每一行对应一个判别信息。如果对应的表达式是合法的S表达式，则输出“Yes”,否则输出“No”.<br></p> 

 
 # 提示 
<p>
【递归加强】</p> 
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
<tr><td>6
a
      b
         (a,b)
((a,b),(c,D))
(ab,c)
[a,b]
</td><td>6
Yes
Yes
Yes
Yes
No
No</td></tr></table>
