# 

 
 # 题目描述 
<p>
喜欢钻研问题的JS 同学，最近又迷上了对加密方法的思考。一天，他突然想出了一种他认为是终极的加密办法：把需要加密的信息排成一圈，显然，它们有很多种不同的读法。例如下图，可以读作：<br><img border="0" src="/source/joyoi/tyvj-3500/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzUwMC9wcm9ibGVtc19pbWFnZXMvMjMzMC8xLmpwZw==.jpg"><br>JSOI07<br>SOI07J<br>OI07JS<br>I07JSO<br>07JSOI<br>7JSOI0<br>把它们按照字符串的大小排序：<br>07JSOI<br>7JSOI0<br>I07JSO<br>JSOI07<br>OI07JS<br>SOI07J<br>读出最后一列字符：I0O7SJ，就是加密后的字符串（其实这个加密手段实在很容易破解，鉴于这是突然想出来的，那就^^）。<br>但是，如果想加密的字符串实在太长，你能写一个程序完成这个任务吗？<br></p> 

 
 # 输入格式 
<p>
输入文件包含一行，欲加密的字符串。注意字符串的内容不一定是字母、数字，也可以是符号等。<br><br></p> 

 
 # 输出格式 
<p>
输出一行，为加密后的字符串。<br><br></p> 
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
<tr><td>JSOI07

</td><td>
I0O7SJ

数据规模
对于40%的数据字符串的长度不超过10000。
对于100%的数据字符串的长度不超过100000。
</td></tr></table>
