# 

 
 # 题目背景 
SCOI2011&nbsp;Day2&nbsp;第二题 

 
 # 题目描述 
lxhgww非常喜欢数字游戏，他发现，很多数都可以表示成两个相互反转的数之和，他把这个现象称为数的“镜像拆分”。比如66共有五种镜像拆分方法：<BR>66&nbsp;=&nbsp;15&nbsp;+&nbsp;51<BR>66&nbsp;=&nbsp;24&nbsp;+&nbsp;42<BR>66&nbsp;=&nbsp;33&nbsp;+&nbsp;33<BR>66&nbsp;=&nbsp;42&nbsp;+&nbsp;24<BR>66&nbsp;=&nbsp;51&nbsp;+&nbsp;15<BR>注意，前导0是不允许的，所以66&nbsp;=&nbsp;60&nbsp;+&nbsp;06不算做合法的镜像拆分。<BR>现在lxhgww想知道，在K进制下，对于在[A,&nbsp;B]区间内的数，其镜像拆分的方案数之和是多少？<BR> 

 
 # 输入格式 
输入的第一行是一个数K。<BR>输入的第二行是一个数n，表示数字A的长度。<BR>接下来n行，表示A从低位开始的每一位数字。<BR>然后是一个数m，表示数字B的长度。<BR>接下来m行，表示B从低位开始的每一位数字。 

 
 # 输出格式 
输出一行，包含一个整数，表示镜像拆分的方案数之和。由于这个答案非常大，只需要输出这个答案除以20110521的余数。 

 
 # 提示 
对于20%的数据，保证：&nbsp;2&lt;=K&lt;=100，1&lt;=n,&nbsp;m&lt;=100<BR>对于50%的数据，保证：2&lt;=K&lt;=1000，1&lt;=n,&nbsp;m&lt;=1000<BR>对于100%的数据，保证：&nbsp;2&lt;=K&lt;=100000，1&lt;=n,&nbsp;m&lt;=100000<BR>对于所有的数据，保证：&nbsp;0&lt;A&lt;=B，A,&nbsp;B的每一位数字都在[0,&nbsp;K-1]的范围内，没有前导0<BR> 
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
<tr><td>【输入样例1】
10
2
6
6
2
6
6
【输入样例2】
10
1
1
4
0
0
0
1
</td><td>【输出样例1】
5

【输出样例2】
410
</td></tr></table>
