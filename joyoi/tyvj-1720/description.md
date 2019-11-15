# 

 
 # 题目描述 
给定一个有向图&nbsp;G=(V,E)。给每个结点v&nbsp;赋上权值w[v]（w[v]须为正整数），使得对于任意一个结点v∈V，都有w[v]=sum{w[&nbsp;u&nbsp;]}((u,v)&nbsp;∈E)。则得到的加权图就是一个“和图”。如图（结点中的数字表示该结点权值）：<BR><img src="/source/joyoi/tyvj-1720/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTcyMC9odHRwOi8vd3d3LmNvZGVyc3BhY2UubmV0L2Jicy9hdHRhY2htZW50cy9tb250aF8xMjAxLzEyMDEyNTE4Mzk2ZDAyMzA1NWYyMDY1MTVkLmpwZw==.jpg" border=0 align=middle><BR>图G&nbsp;共有n&nbsp;个结点，从1~n&nbsp;标号。图中可能有自环、重边。其中某个结点x的权值w[x]已经固定，求可得到的满足“和图”条件的加权图的个数。 

 
 # 输入格式 
输入第一行为两个正整数n,m，分别表示图G中的结点数和有向边数。<BR>接下来的m行，每行有两个正整数u,v，表示图G中的一条有向边(u,v)。<BR>最后一行是两个正整数x,w[x]。<BR> 

 
 # 输出格式 
输出包括一行：如果可得到的“和图”有无穷多个，输出inf；否则输出其个数（须对10008取模）。 

 
 # 提示 
对于100%的数据1≤n≤15,1≤m≤100,w[x]≤100,000。寒假模拟赛&nbsp;提高组&nbsp;day1-3 
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
<tr><td>3 2
1 2
3 2
2 5
</td><td>4
</td></tr></table>
