# 

 
 # 题目背景 
NOIP2011&nbsp;day1&nbsp;第二题<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;丽江河边有n&nbsp;家很有特色的客栈，客栈按照其位置顺序从&nbsp;1&nbsp;到n&nbsp;编号。每家客栈都按照某一种色调进行装饰（总共&nbsp;k&nbsp;种，用整数&nbsp;0&nbsp;~&nbsp;k-1&nbsp;表示），且每家客栈都设有一家咖啡店，每家咖啡店均有各自的最低消费。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;两位游客一起去丽江旅游，他们喜欢相同的色调，又想尝试两个不同的客栈，因此决定分别住在色调相同的两家客栈中。晚上，他们打算选择一家咖啡店喝咖啡，要求咖啡店位于两人住的两家客栈之间（包括他们住的客栈），且咖啡店的最低消费不超过&nbsp;p&nbsp;。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;他们想知道总共有多少种选择住宿的方案，保证晚上可以找到一家最低消费不超过&nbsp;p&nbsp;元的咖啡店小聚。&nbsp; 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第一行三个整数n&nbsp;，k&nbsp;，p，每两个整数之间用一个空格隔开，分别表示客栈的个数，色调的数目和能接受的最低消费的最高值；&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来的n&nbsp;行，第&nbsp;i+1&nbsp;行两个整数，之间用一个空格隔开，分别表示&nbsp;i&nbsp;号客栈的装饰色调和i&nbsp;号客栈的咖啡店的最低消费。&nbsp;<BR>&nbsp;<BR>&nbsp; 

 
 # 输出格式 
输出只有一行，一个整数，表示可选的住宿方案的总数。&nbsp; 

 
 # 提示 
对于30%&nbsp;的数据，有&nbsp;n&nbsp;≤100；&nbsp;<BR>对于50%&nbsp;的数据，有&nbsp;n&nbsp;≤1,000；&nbsp;<BR>对于100%的数据，有&nbsp;2&nbsp;≤n&nbsp;≤200,000，0&lt;k&nbsp;≤50，0≤p&nbsp;≤100&nbsp;，&nbsp;0&nbsp;≤最低消费≤100。&nbsp; 
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
<tr><td>5 2 3 
0 5 
1 3 
0 2 
1 4 
1 5 </td><td>3

【输入输出样例说明】 
 
客栈编号  ①  ②  ③  ④  ⑤ 
色调      0   1   0   1   1 
最低消费  5   3   2   4   5 
 
2 人要住同样色调的客栈，所有可选的住宿方案包括：住客栈①③，②④，②⑤，④⑤，但是若选择住4 、5 号客栈的话，4 、5 号客栈之间的咖啡店的最低消费是4 ，而两人能承受的最低消费是3 元，所以不满足要求。因此只有前 3 种方案可选。</td></tr></table>
