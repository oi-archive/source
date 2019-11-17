# 

 
 # 题目背景 
JSOI&nbsp;2009 

 
 # 题目描述 
JOSEPHUS问题应该是大家非常熟悉的了。<BR>这个问题是：已知圈上人数N，和出圈周期K，即每次报到数K的人出圈，求最后一个出圈的人是谁。<BR>现在我们把该问题反一下，即已知圈上人数N和出圈次序，要求最小的出圈周期k。下图为N=4，K=5时的情况：<BR><img src="/source/joyoi/tyvj-1827/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTgyNy9Qcm9ibGVtSW1nLzE4MjctMS5qcGc=.jpg" border=0 align=middle><BR> 

 
 # 输入格式 
输入文件共两行，第一行为一个整数N，表示圈上人数，其中2&lt;=N&lt;=20,第二行共有N个用空格隔开的整数，表示出圈次序，第i个数的值v代表第i个人是第v个出圈的。 

 
 # 输出格式 
输出文件仅一行表示最小的出圈周期，若无论用什么样的出圈周期都不可能得到给定的出圈序列，则输出"NO"。 
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
<tr><td>4
1 4 2 3</td><td>5</td></tr></table>
