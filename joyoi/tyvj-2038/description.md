# 

 
 # 题目背景 
“扫地”杯III&nbsp;NOIP2012模拟赛&nbsp;day1&nbsp;第一题<br><br><br><br> 

 
 # 题目描述 
liouzhou_101从NOI归来后文化课像坨屎，于是决定去补做一些作业，结果翻开作业的第一题就傻眼了：<br>设a、b、c为实数，且满足a+b+c=15,a^2+b^2+c^2=100，则a的最大值和最小值的积为____。<br>话说这题他都没有想出来怎么做，就开始自己YY，把这题牛逼成了：<br>设a1、a2、…、an为实数，且a1+a2+…+an=x，a1^2+a2^2+…+an^2=y，则a1的最大值和最小值的积为____。<br>liouzhou_101这种傻×自然不会做了，于是来向你请教…<br><br><br><br> 

 
 # 输入格式 
输入的第一行是一个正整数T，表示测资组数。<br>接着对每组测资，输入只有一行，三个正整数N、x和y，之间以一个空格隔开。<br><br><br><br> 

 
 # 输出格式 
对于每组测资，输出只有一行，假若不存在满足题目要求的，就输出“WA&nbsp;RE&nbsp;CE&nbsp;TLE&nbsp;MLE&nbsp;OLE”(不含引号)；否则输出一个精确到小数点后6位的浮点数，即a1的最大值和最小值的积。<br><br><br><br> 

 
 # 提示 
对于第一组测资，a1最大是9.082483，最小是0.917517，乘起来就是8.333333。<br>对于第二组测资，明显不可能存在a1满足题意。<br><br>对于10%的数据，N=1；<br>对于20%的数据，N&lt;=2；<br>对于40%的数据，N&lt;=3；<br>对于70%的数据，N&lt;=100；<br>对于100%的数据，1&lt;=T&lt;=10，1&lt;=N&lt;=10,000，-10,000&lt;=x&lt;=10,000，0&lt;=y&lt;=10,000。<br><br><br><br>liouzhou_101<br><br><br><br> 
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
3 15 100
1 4 15



</td><td>8.333333
WA RE CE TLE MLE OLE



</td></tr></table>
