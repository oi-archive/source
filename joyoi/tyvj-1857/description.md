# 

 
 # 题目背景 
中山市选2011&nbsp;小W的问题<BR> 

 
 # 题目描述 
有一天，小W找了一个笛卡尔坐标系，并在上面选取了N个整点。他发现通过这些整点能够画出很多个“W”出来。具体来说，对于五个不同的点(x1,&nbsp;y1),&nbsp;(x2,&nbsp;y2),&nbsp;(x3,&nbsp;y3),&nbsp;(x4,&nbsp;y4),&nbsp;(x5,&nbsp;y5)，如果满足：<BR>·x1&nbsp;&lt;&nbsp;x2&nbsp;&lt;&nbsp;x3&nbsp;&lt;&nbsp;x4&nbsp;&lt;&nbsp;x5<BR>·y1&nbsp;&gt;&nbsp;y3&nbsp;&gt;&nbsp;y2<BR>·y5&nbsp;&gt;&nbsp;y3&nbsp;&gt;&nbsp;y4<BR>则称它们构成一个“W”形。<BR>现在，小W想统计“W”形的个数，也就是满足上面条件的五元点组个数。你能帮助他吗？<BR><BR> 

 
 # 输入格式 
第一行包含一个整数N，表示点的个数。<BR>下面N行每行两个整数，第i+1行为(xi,&nbsp;yi)，表示第i个点的坐标。 

 
 # 输出格式 
仅包含一行，为“W”形个数模1&nbsp;000&nbsp;000&nbsp;007的值。 

 
 # 提示 
对于100%的数据满足N&nbsp;≤&nbsp;100&nbsp;000，0&nbsp;≤&nbsp;xi&nbsp;≤&nbsp;10^9，0&nbsp;≤&nbsp;yi&nbsp;≤&nbsp;10^9 
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
<tr><td>6
1 10
2 1
3 5
4 6
5 1
6 10</td><td>3</td></tr></table>
