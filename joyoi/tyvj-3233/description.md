# 

 
 # 题目描述 
<p>
(reliable.pas/c/cpp)<br><br>【问题描述】<br><br>一次战争中，有N个防御站在一条直线上。<br>你得到一则信息，现在要判断这则信息是否可信。<br>信息包含M条提示，每条提示要么是精确的，要么是含糊的。<br>精确提示的格式是P A B X，表示防御站A在防御站B北面X光年处。<br>含糊提示的格式是V A B，表示防御站A在防御站B北面至少1光年处，但具体距离不知道。<br></p> 

 
 # 输入格式 
<p>
输入有多种数据。每组数据以两个整数N (0 < N ≤ 1000)和M (1 ≤ M ≤ 100000)开始。接下来M行，输入M条提示。<br><br></p> 

 
 # 输出格式 
<p>
每组数据输出一行。如果能布置这N个防御站的位置来满足这M条提示，则输出“Reliable”，否则输出“Unreliable”。</p> 

 
 # 提示 
<p>
本题数据不完整，请在本系统测试通过后到 http://poj.org/problem?id=2983 提交完整测试！<br><br></p> 
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
<tr><td>3 4
P 1 2 1
P 2 3 1
V 1 3
P 1 3 1
5 5
V 1 2
V 2 3
V 3 4
V 4 5
V 3 5
</td><td>Unreliable
Reliable</td></tr></table>
