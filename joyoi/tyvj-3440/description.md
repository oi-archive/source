# 

 
 # 题目描述 
<p>
数字识别（digital.pas\c\cpp）<br><br>【题目描述】<br>　　银行里经常采用光学字符识别技术（OCR）来识别支票上的数字。当支票经过扫描仪扫描后，经过初步的处理，可以得到用7段短线表示的数字，如下图所示：<br><br><center><img src="/source/joyoi/tyvj-3440/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzQ0MC9wcm9ibGVtc19pbWFnZXMvMjI0Ni8xLmpwZw==.jpg"></img></center><br>　　该银行的支票共 9位数，可以表示为：d9d8d7d6d5d4d3d2d1。对一张合法的支票必须满足检验条件：(d9*9＋d8*8+ d7*7＋…＋d2*2+ d1） mod 11=0。<br>　　但是扫描仪有时会产生误差，漏掉一些短线。现在要求编一程序，识别出一张合法的支票。（现假设一张支票至多漏掉一条短线）<br></p> 

 
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
