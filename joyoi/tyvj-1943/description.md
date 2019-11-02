# 

 
 # 题目描述 
<p>小R有这样一个容器，他只支持一种操作：<br />
每次取出容器中最小的数x（如果有多个，任取一个），放入(x*k1+1)&nbsp;%&nbsp;m以及(x*k2+1)&nbsp;%&nbsp;m。<br />
（每次取出的x不放回去,%相当于pascal里的mod）。<br />
一开始容器中只有一个数a。<br />
已知，a、k1、k2、m，求第N次取出的数是多少。</p> 

 
 # 输入格式 
<p>包含多组数据。(小于等于10组）<br />
<br />
每组数据包含五个整数a、k1、k2、m、N<br />
(0&lt;a、k1、k2、m、N&lt;40000)</p> 

 
 # 输出格式 
<p>对于每组数据，输出第N次取出的数</p> 
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
<tr><td>1 1 1 10 1</td><td>1</td></tr></table>
