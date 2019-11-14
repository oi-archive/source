# 

 
 # 题目描述 
windy有&nbsp;N&nbsp;条木板需要被粉刷。<BR>每条木板被分为&nbsp;M&nbsp;个格子。<BR>每个格子要被刷成红色或蓝色。<BR>windy每次粉刷，只能选择一条木板上一段连续的格子，然后涂上一种颜色。<BR>每个格子最多只能被粉刷一次。<BR>如果windy只能粉刷&nbsp;T&nbsp;次，他最多能正确粉刷多少格子？<BR>一个格子如果未被粉刷或者被粉刷错颜色，就算错误粉刷。<BR> 

 
 # 输入格式 
第一行包含三个整数，N&nbsp;M&nbsp;T。<BR>接下来有N行，每行一个长度为M的字符串，'0'表示红色，'1'表示蓝色。<BR> 

 
 # 输出格式 
一个整数，最多能正确粉刷的格子数。<BR> 

 
 # 提示 
30%的数据，满足&nbsp;1&nbsp;&lt;=&nbsp;N,M&nbsp;&lt;=&nbsp;10&nbsp;；&nbsp;0&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;100&nbsp;。<BR>100%的数据，满足&nbsp;1&nbsp;&lt;=&nbsp;N,M&nbsp;&lt;=&nbsp;50&nbsp;；&nbsp;0&nbsp;&lt;=&nbsp;T&nbsp;&lt;=&nbsp;2500&nbsp;。四川SCOI2009一试&nbsp;Day2&nbsp;第二题 
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
<tr><td>3 6 3
111111
000000
001100
</td><td>16
</td></tr></table>
