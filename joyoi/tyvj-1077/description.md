# 

 
 # 题目描述 
对于一个素数P，我们可以用一系列有理分数(分子、分母都是不大于N的自然数)来逼近sqrt(p)，例如P=2，N=5的时候：1/1&lt;5/4&lt;4/3&lt;sqrt(2)&lt;3/2&lt;5/3&lt;2/1。<BR>任　务　：<BR>给定P、N（N&gt;sqrt(p)），求X、Y、U、V，使x/y&lt;sqrt(p)&lt;u/v且x/y与sqrt(p)之间、sqrt(p)与u/v之间都不能再插入满足题意的有理分数。 

 
 # 输入格式 
输入文件的第一行为P、N，其中&nbsp;P、N&lt;30000。 

 
 # 输出格式 
输出文件只有一行，格式为“X/Y&nbsp;U/V”。注意，答案必须是既约的，也就是说分子、分母的最大公约数必须等于1。 
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
<tr><td>样例1：
2 5
样例2：
5 100</td><td>样例1：
4/3 3/2

样例2：
38/17 85/38
</td></tr></table>
