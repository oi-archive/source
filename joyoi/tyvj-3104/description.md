# 

 
 # 题目描述 
<p>
代数表达式的定义如下：<br><br><center><img src="/source/joyoi/tyvj-3104/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEwNC9wcm9ibGVtc19pbWFnZXMvMTMwMi8xLmJtcA==.bmp"></img></center><br>　　例如，下面的式子是合法的代数表达式：<br>　　a；<br>　　a+b*(a+c);<br>　　a*a/(b+c)<br>　　下面的式子是不合法的代数表达式：<br>ab；<br>a+a*/(b+c)；<br>　　程序要求：<br>　　　　输入：输入一个字符串，以“；”结束，“；”本身不是代数表达式中字符，仅作为结束）；   <br>　　　　输出：若表达式正确，则输出“OK”；若表达式不正确，则输出“ERROR”，及错误类型。<br>错误类型约定：<br>　　　1、式了中出现不允许的字符；<br>　　　2、括号不配对；<br>　　　3、其它错误。<br>　　例如：输入：a+(b)；　　　　　　输出：OK<br>　　例如：输入：a+(b+c*a；　　　　输出：ERROR 2<br></p> 

 
 # 输入格式 
<p>
(((b+c))) 　　　　{样例1输入}</p> 

 
 # 输出格式 
<p>
OK 　　　　　　{样例1输出}</p> 
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
<tr><td>a+x 　　　　　{样例2输入}</td><td>ERROR 1　　　{样例2输出；之间有一个空格}</td></tr></table>
