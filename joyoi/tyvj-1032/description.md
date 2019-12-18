# 

 
 # 题目背景 
<p>USACO&nbsp;OCT09&nbsp;7TH</p> 

 
 # 题目描述 
<p>作為创造產奶纪录的回报，Farmer&nbsp;John决定开始每个星期给Bessie一点零花钱。<br />
<br />
FJ有一些硬币，一共有N&nbsp;(1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;20)种不同的面额。每一个面额都能整除所有比它大的面额。<br />
<br />
他想用给定的硬币的集合，每个星期至少给Bessie某个零花钱的数目C&nbsp;(1&nbsp;&lt;=&nbsp;C&nbsp;&lt;=&nbsp;<br />
100000000)。请帮他计算他最多能支付多少个星期的零花钱。</p> 

 
 # 输入格式 
<p>*&nbsp;第一行:&nbsp;两个由空格隔开的整数:&nbsp;N&nbsp;和&nbsp;C<br />
<br />
*&nbsp;第2到第N+1行:&nbsp;每一行有两个整数表示一个面额的硬币：硬币面额V&nbsp;(1&nbsp;&lt;=&nbsp;V&nbsp;&lt;=&nbsp;<br />
100,000,000)和Farmer&nbsp;John拥有的该面额的硬币数B&nbsp;(1&nbsp;&lt;=&nbsp;B&nbsp;&lt;=<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1,000,000).</p> 

 
 # 输出格式 
<p>*&nbsp;第一行:&nbsp;一个单独的整数，表示Farmer&nbsp;John最多能给Bessie支付多少个星期至少為C的零用钱。</p> 

 
 # 提示 
<p>FJ想要每个星期给Bessie六美分。他有100个1美分硬币，120个5美分硬币，和一个10美分硬币。<br />
<br />
FJ可以在一个星期超额付给Bessie一个10美分硬币。然后接下来的10个星期每星期付给<br />
Bessie两个5美分硬币。最后100个星期每星期付给Bessie一个1美分硬币跟一个5美分硬<br />
币。<br />
&nbsp;</p> 
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
<tr><td>3 6
10 1
1 100
5 120</td><td>111</td></tr></table>
