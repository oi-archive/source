# 

 
 # 题目背景 
[noip1998T3]进位制<BR> 

 
 # 题目描述 
著名科学家卢斯为了检查学生对进位制的理解，他给出了如下的一张加法表，表中的字母代表数字。&nbsp;例如：&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<BR><img src="/source/joyoi/tyvj-1874/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTg3NC9odHRwOi8veXVhbnRpLnR5dmouY246ODA4MC9Qcm9ibGVtSW1nL1AxMDA2LmpwZw==.jpg" border=0 align=middle>				&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;其含义为：<BR>											L+L=L，L+K=K，L+V=V，L+E=E<BR>											K+L=K，K+K=V，K+V=E，K+E=KL											&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;……						&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;E+E=KV	<BR>根据这些规则可推导出：L=0，K=1，V=2，E=3&nbsp;同时可以确定该表表示的是4进制加法 

 
 # 输入格式 
&nbsp;n（n≤9）表示行数。<BR>以下n行，每行包括n个字符串，每个字串间用空格隔开。（字串仅有一个为‘+’号，其它都由大写字母组成）<BR> 

 
 # 输出格式 
输出各个字母表示什么数，格式如：L=0，K=1，……(这个的顺序同输入数据的第一行)，并在同一行输出加法运算是几进制的。<BR><BR><BR> 

 
 # 提示 
这里的加法表保证了0到n-1都会出现在字母中。数据保证能构成加法表。 
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
<tr><td>5
+ L K V E
L L K V E
K K V E KL
V V E KL KK
E E KL KK KV
</td><td>L=0 K=1 V=2 E=3 4</td></tr></table>
