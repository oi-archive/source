# 

 
 # 题目描述 
<p align="left">定义一个数&nbsp;x&nbsp;是&nbsp;Happy&nbsp;Number&nbsp;，当且仅当求该数字所有数位的平方和，得到的新数再次求所有数位的平方和，如此重复进行，最终结果为1。</p>

<p align="left">例如19就是个&nbsp;Happy&nbsp;Number&nbsp;：</p>

<p align="left">19&rarr;1^2+&nbsp;9^2=82&nbsp;&nbsp;82&rarr;8^2+&nbsp;2^2=68&nbsp;68&rarr;6^2+&nbsp;8^2=100&nbsp;100&rarr;1^2+&nbsp;0^2+&nbsp;0^2=1</p>

<p align="left">给定&nbsp;L,R&nbsp;，求&nbsp;[L,R]&nbsp;内&nbsp;Happy&nbsp;Number&nbsp;的个数。</p> 

 
 # 输入格式 
<p align="left">第一行一个正整数&nbsp;T&nbsp;，表示数据组数。</p>

<p align="left">接下来&nbsp;T&nbsp;行，每行两个正整数，表示&nbsp;L,R&nbsp;。</p> 

 
 # 输出格式 
<p align="left">对于每组测试数据，输出一个整数表示这个区间内&nbsp;Happy&nbsp;Number&nbsp;的个数。</p>

<p>接下来&nbsp;T&nbsp;行，每行两个正整数，表示&nbsp;L,R&nbsp;。</p>

<p>&nbsp;</p> 

 
 # 提示 
<p align="left"><span style="line-height: 1.6em;">对于&nbsp;30%&nbsp;的数据，满足&nbsp;R&nbsp;&le;&nbsp;10^5；</span></p>

<p align="left">对于&nbsp;100%&nbsp;的数据，满足&nbsp;1&nbsp;&le;&nbsp;L&nbsp;&le;&nbsp;R&nbsp;&le;&nbsp;10^18,1&nbsp;&le;&nbsp;T&nbsp;&le;&nbsp;200&nbsp;。</p>

<p>&nbsp;</p>

<p>&nbsp;</p> 
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
<tr><td>2
2 6
1 10</td><td>0
3</td></tr></table>
