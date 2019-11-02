# 

 
 # 题目背景 
“扫地”杯III&nbsp;NOIP2012模拟赛&nbsp;day2&nbsp;第一题<br><br><br> 

 
 # 题目描述 
做了HEOI2012的赵州桥(bridge)之后，liouzhou_101就感到极其的不爽，首先那题题目叙述巨渣，然后做法极坑。<br>不过那题是一道和染色有关的问题，于是在此同时也启发liouzhou_101想到了这样一个简单的问题：<br>在一串未打结的项链上(意思就是说项链的左端和右端不相连)，有N颗珠子，你有M种颜色，然后就问你有多少种方法将每一颗珠子都染上颜色，使得任意两颗相邻的珠子的颜色不同。<br>liouzhou_101这种傻×自然不会做了，于是来向你请教…<br>当然，由于liouzhou_101的脑子构造极其简单，你不要想太多，请不要考虑Polya之类的本质相同，否则的话仅凭liouzhou_101的理解能力是不能理解的…<br><br><br> 

 
 # 输入格式 
输入只有一行，三个正整数N、M和P，之间以一个空格隔开。<br><br> 

 
 # 输出格式 
输出只有一行，表示染色的方法总数模P。<br><br> 

 
 # 提示 
一共有324种染色方法，对13取模后是12。<br><br>对于10%的数据，N=1，M&lt;=10，P&lt;=10；<br>对于20%的数据，N&lt;=10，M&lt;=10，P&lt;=100；<br>对于50%的数据，N,M,P&lt;=1,000,000,000；<br>对于100%的数据，1&lt;=N,M,P&lt;=1,000,000,000,000,000,000，且M&gt;=2。<br><br><br>liouzhou_101<br><br><br> 
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
<tr><td>5 4 13

</td><td>12

</td></tr></table>
