# 

 
 # 题目描述 
<p><span style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px;">给一个整数n，这个整数用b(2&lt;=b&lt;=36)进制表示，请编写一个程序，将其转换为c</span><span style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px; line-height: 20.8px;">(2</span><span style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px; line-height: 20.8px;">&lt;=c&lt;=36)</span><span style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px;">进制并输出。若输入的整数为负数，那么输出的最前面也要有一个&ldquo;-&rdquo;。对于大于十进制的数，用大写的英文字母表示每位中大于9的数，例如A对应10，B对应11，C对应12，以此类推。</span></p> 

 
 # 输入格式 
<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px;">第一行为一个字符串，表示整数n。最前面可能有个负号。</p>

<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px;">第二行为两个正整数，分别为b<span style="line-height: 20.8px;">(2</span><span style="line-height: 20.8px;">&lt;=b&lt;=36)</span>和c<span style="line-height: 20.8px;">(2</span><span style="line-height: 20.8px;">&lt;=c&lt;=36)</span>，用一个空格隔开，分别表示转换前后的进制。</p> 

 
 # 输出格式 
<p><span style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px;">输出一个字符串，表示转换后的c进制表示。</span></p> 

 
 # 提示 
<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px;">对于40%的测试数据，保证c=10。</p>

<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px;">对于100%的测试数据，保证2&lt;=b&lt;=36,&nbsp;2&lt;=c&lt;=36。</p>

<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px;">保证&nbsp;-2147483648&lt;=(n)<sub>10</sub>&lt;=2147483647。</p>

<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px;">保证输入的转换前数字的字符串长度小于30。</p> 
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
<tr><td>1010
2 10</td><td>10</td></tr><tr><td>-01010101
2 16</td><td>-55</td></tr></table>
