# 

 
 # 题目描述 
<p>
奶牛Bessie最近在学习字符串操作，它用如下的规则逐一的构造出新的字符串：<br>S(0) = “moo”<br>S(1) = S(0) + “m”+ “ooo” + S(0) = “moo” + “m” + “ooo” + “moo” = “moomooomoo”<br>S(2) = S(1) + “m” + “oooo” + S(1) = “moomooomoo” + “m” + “oooo” +  “moomooomoo” = “moomooomoomoooomoomooomoo”<br>………<br>Bessie就这样产生字符串，直到最后产生的那个字符串长度不小于读入的整数Ｎ才停止。<br>通过上面观察，可以发现第k个字符串是由：第k-1个字符串 + “m” +  (k+2个o) + 第k-1个字符串连接起来的。<br>现在的问题是：给出一个整数N (1 <= N <= 10^9)，问第N个字符是字母“m”还是“o”?<br></p> 

 
 # 输入格式 
<p>
一个整数N。</p> 

 
 # 输出格式 
<p>
一个字符，m或者o。</p> 

 
 # 提示 
<p>
样例解释：<br>由题目所知：字符串S(0)是moo, 现在要求第11个字符，显然字符串S(0)不够长；<br>同样S(1)的长度是10，也不够长；S(2)的长度是25，够长了，S(2)的第11个字符是m，所以答案就输出m。<br></p> 
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
<tr><td>11</td><td>m</td></tr></table>
