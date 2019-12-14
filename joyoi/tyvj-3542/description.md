# 

 
 # 题目描述 
<p>
 折叠的定义如下：<br>1.	一个字符串可以看成它自身的折叠。记作S &#61664; S<br>2.	X(S)是X(X>1)个S连接在一起的串的折叠。记作X(S) &#61664; SSSS…S(X个S)。<br>3.	如果A &#61664; A’, B&#61664;B’，则AB &#61664; A’B’<br>例如，因为3(A) = AAA, 2(B) = BB，所以3(A)C2(B) &#61664; AAACBB，而2(3(A)C)2(B)&#61664;AAACAAACBB<br>给一个字符串，求它的最短折叠。例如AAAAAAAAAABABABCCD的最短折叠为：9(A)3(AB)CCD。<br></p> 

 
 # 输入格式 
<p>
仅一行，即字符串S，长度保证不超过100。<br><br></p> 

 
 # 输出格式 
<p>
仅一行，即最短的折叠长度。<br><br></p> 

 
 # 提示 
<p>
一个最短的折叠为：2(NEERC3(YES))<br></p> 
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
<tr><td>NEERCYESYESYESNEERCYESYESYES

</td><td>14
</td></tr></table>
