# 

 
 # 题目描述 
<p align="left">小&nbsp;C&nbsp;数学成绩优异，于是老师给小&nbsp;C&nbsp;留了一道非常难的数学作业题：</p>

<p align="left">给定正整数&nbsp;N和&nbsp;M，要求计算&nbsp;Concatenate&nbsp;(1&nbsp;..&nbsp;N)&nbsp;Mod&nbsp;M的值，其中&nbsp;Concatenate&nbsp;(1&nbsp;..<span style="line-height: 1.6em;">N)是将所有正整数&nbsp;1,&nbsp;2,&nbsp;&hellip;,&nbsp;N顺序连接起来得到的数。例如，N&nbsp;=&nbsp;13,&nbsp;Concatenate&nbsp;(1&nbsp;..&nbsp;N)</span><span style="line-height: 1.6em;">=&nbsp;12345678910111213.</span></p>

<p align="left">小&nbsp;C&nbsp;想了大半天终于意识到这是一道不可能手算出来的题目，于是他只好向你求助，希望<span style="line-height: 1.6em;">你能编写一个程序帮他解决这个问题。</span></p> 

 
 # 输入格式 
<p>输入文件只有一行且为用空格隔开的两个正整数N和M</p> 

 
 # 输出格式 
<p align="left">输出文件仅包含一个非负整数，表示&nbsp;Concatenate&nbsp;(1&nbsp;..&nbsp;N)&nbsp;Mod&nbsp;M的值。</p>

<p>&nbsp;</p> 

 
 # 提示 
<p align="left"><span style="line-height: 1.6em;">30%的数据满足1&le;N&le;1000000；</span></p>

<p align="left"><span style="line-height: 1.6em;">100%的数据满足1&le;N&le;10^18且1&le;M&le;10^9.</span></p> 
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
<tr><td>12345678910 1000000000</td><td>345678910</td></tr><tr><td>13 13</td><td>4</td></tr></table>
