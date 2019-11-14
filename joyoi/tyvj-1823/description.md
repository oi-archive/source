# 

 
 # 题目描述 
火星人是一种好奇心很大的生物。最近，火星人对字符串产生了浓厚的兴趣。他们研究了字符串的LCP：<BR>	<BR>	对于字符串str[1..n]，LCP(i,&nbsp;j)为str[i..n]与str[j..n]这两个字符串的公共前缀长。<BR>	<BR>	例如str="madamimadam"：<BR>	<BR><img src="/source/joyoi/tyvj-1823/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTgyMy9Qcm9ibGVtSW1nLzE4MjMuanBn.jpg" border=0 align=middle><BR>	<BR>	有LCP(1,&nbsp;7)&nbsp;=&nbsp;LCP("madamimadam",&nbsp;"madam")&nbsp;=&nbsp;5<BR>	LCP(4,&nbsp;8)&nbsp;=&nbsp;LCP("amimadam",&nbsp;"adam")&nbsp;=&nbsp;1<BR>	LCP(10,11)&nbsp;=&nbsp;LCP("am",&nbsp;"m")&nbsp;=&nbsp;0<BR>	<BR>	后来，火星人发现，如果进行了后缀排序，就能够很快地求LCP，同样，如果能很快地求出字符串的LCP，也可以高效地把所有后缀排序。不过事情总不是想象的那么简单，地球人JS总是喜欢测试火星人的智商：他会在火星人把字符串的后缀排序以后，修改原来的字符串，导致火星人的工作全盘浪费。<BR>	<BR>	于是火星人请到了聪明的你，设计一个程序，对给出的字符串能够支持以下三种操作：<BR>	<BR>	1、求LCP(i,&nbsp;j)<BR>	2、将第i个位置的字符修改<BR>	3、在第i个位置后插入一个字符<BR>	<BR>	火星人很害怕被地球人耻笑，所以希望你的算法能有很高的执行效率。 

 
 # 输入格式 
输入文件第一行为一个字符串（仅包含小写字母）。<BR>	接下来的一行的整数Q代表操作的个数（1&nbsp;≤Q&nbsp;&nbsp;≤150000）。<BR>	接下来Q行表示了待执行的操作。<BR>	Q&nbsp;i&nbsp;j表示求LCP(i,&nbsp;j)的数值<BR>	R&nbsp;i&nbsp;char表示将第i位置的字符替换成小写字母char<BR>	I&nbsp;i&nbsp;char表示在第i个字符后插入小写字母char 

 
 # 输出格式 
对于每一个Q&nbsp;i&nbsp;j，输出一行为LCP(i,&nbsp;j)的数值。 

 
 # 提示 
对于20%的数据，最终字符串的长度不超过1000。<BR>	对于另外30%的数据中不含有插入操作。<BR>	对于100%的数据，最终字符串的长度不超过100000。<BR>	对于100%的数据，替换字符的次数不超过100000。<BR>	对于100%的数据，询问LCP的次数不超过10000。 
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
<tr><td>madamimadam
7
Q 1 7
Q 4 8
Q 10 11
R 3 a
Q 1 7
I 10 a
Q 2 11</td><td>5
1
0
2
1</td></tr></table>
