# 

 
 # 题目描述 
湖面上有n座岛屿，从1~n编号。现在要湖上建桥使得岛屿连接起来。桥双向通行。 

 
 # 输入格式 
输入第一行有两个整数n,m。<BR>接下来是m行，按照时间顺序每行是一次询问。每行第一个整数q代表询问的内容：如果q=1，则接下来是两个岛屿编号a,b(a≠b)；如果q=2，则接下来是一个岛屿编号c。<BR> 

 
 # 输出格式 
对于每个询问，按次序各输出一行作为回答：<BR>q=1时：如果a,b相互可达，则输出Yes；如果a,b相互不可达，则输出No，并在a,b之间建一座桥。<BR>q=2时：输出一个整数x，表示由c出发可以到达的岛屿有x个（不包括c自身）。<BR> 

 
 # 提示 
对于100%的数据，2≤n≤10,000,&nbsp;1≤m≤30,000。<BR>寒假模拟赛&nbsp;提高组&nbsp;day2-1 
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
<tr><td>5 9
1 2 3
1 3 2
2 1
2 2
1 4 5
1 2 4
1 2 5
2 4
2 5
</td><td>No
Yes
0
1
No
No
Yes
3
3
</td></tr></table>
