# 

 
 # 题目背景 
清北学堂杯NOIP模拟赛第一道<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;某城镇城市由n个村落{S1,&nbsp;S2,&nbsp;…,&nbsp;Sn&nbsp;}组成，且已建造n-1条道路证所有村落之间均有通路。市政府最近正在规划建立一座大型超市，其选址应尽可能缩短村民到该超市的距离。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这里，联接于村落S_i与村落S_j之间通路所经过道路的数目，即它们之间的距离，记作&lt;Si,Sj&gt;。<BR><img src="/source/joyoi/tyvj-1536/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTUzNi9Qcm9ibGVtSW1nLzE1MzYuanBn.jpg" border=0 align=middle><BR><BR>&nbsp;&nbsp;&nbsp;图1.&nbsp;城镇实例：dist(A,&nbsp;C)&nbsp;=&nbsp;2,&nbsp;dist(A,&nbsp;D)&nbsp;=&nbsp;3,&nbsp;dist(D,&nbsp;E)&nbsp;=&nbsp;2<BR>&nbsp;&nbsp;&nbsp;另外，鉴于各村落中居住人口的规模差异很大，因此在评估距离时还应顾及这一因素。于是，若用将村落Si&nbsp;的人口规模记作|Si|，则选址于村落Sj的代价可表示为：&nbsp;cost(Sj)=&nbsp;∑dist(Si,Sj)*|Si|&nbsp;&nbsp;&nbsp;(1&lt;=i&lt;=n) 

 
 # 输入格式 
共2n&nbsp;行：第一行为一个正整数n，表示村落的数目；第2&nbsp;至n+1&nbsp;行：依次为各村落的人口规模|Si|,&nbsp;1&lt;=&nbsp;i&nbsp;&lt;=&nbsp;n；第n+2&nbsp;至2n&nbsp;行：每行为以空格分隔的两个正整数i&nbsp;和j，表示村落Si与村落Sj之间建有一座道路。 

 
 # 输出格式 
只有一行：为正整数m，表示选址于村落Sm&nbsp;代价最小。若这样的村落有多个，输出其中编号最小者。 

 
 # 提示 
60%&nbsp;数据&nbsp;n&lt;=100000<BR>100%&nbsp;数据&nbsp;n&lt;=1000000;0&lt;=|Si|&lt;=10000;1&lt;=i&lt;=n 
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
<tr><td>9
70
94
78
19
91
11
43
25
13
1 6
1 7
6 3
6 9
3 8
6 2
7 4
2 5</td><td>6
</td></tr></table>
