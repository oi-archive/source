# 

 
 # 题目描述 
喜欢钻研问题的JS&nbsp;同学，最近又迷上了对加密方法的思考。一天，他突然想出了一种他认为是终极的加密办法：把需要加密的信息排成一圈，显然，它们有很多种不同的读法。例如右图，可以读作：<BR>JSOI07<BR>SOI07J<BR>OI07JS<BR>I07JSO<BR>07JSOI<BR>7JSOI0<BR>把它们按照字符串的大小排序：<BR>07JSOI<BR>7JSOI0<BR>I07JSO<BR>JSOI07<BR>OI07JS<BR>SOI07J<BR>读出最后一列字符：I0O7SJ，就是加密后的字符串（其实这个加密手段实在很容易破解，鉴于这是突然想出来的，那就^^）。<BR>但是，如果想加密的字符串实在太长，你能写一个程序完成这个任务吗？<BR> 

 
 # 输入格式 
输入文件包含一行，欲加密的字符串。注意字符串的内容不一定是字母、数字，也可以是符号等。 

 
 # 输出格式 
输出一行，为加密后的字符串。 

 
 # 提示 
对于40%的数据字符串的长度不超过10000。<BR>对于100%的数据字符串的长度不超过100000。<BR> 
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
<tr><td>JSOI07</td><td>I0O7SJ</td></tr></table>
