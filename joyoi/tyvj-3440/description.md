# 

 
 # 题目描述 
<p>
数字识别（digital.pas\c\cpp）

 
 # 输入格式 
<p>
　　输入文件digital.in共有三行，表示一个9位数(各个数码用7段短线表示），每行有27个字符，这些字符可以是‘_’（ASCII码为5FH）、‘|’（ASCII码为7CH）或‘’（空格ASCII码为20H），其中数字后带H表示16进制数。</p> 

 
 # 输出格式 
<p>
　　输出文件digital.out只有一行，如果数据能被识别出是合法的支票，且只有一种方案，则输出这种方案；如果有多种方案，则输出“ambiguous”；如果不能识别出是合法的支票，则输出“ failure”。</p> 
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
<tr><td>    _  _     _  _ _  _  _ 
  | _| _||_||_ |_  ||_||_|
  ||_  _|  | _||_| ||_| _|
</td><td>123456789</td></tr></table>