# 

 
 # 题目描述 
给出一个树形图（“tree-shaped”&nbsp;network）,有N（1≤N≤10，000）个顶点。如果删除树上某一个顶点，整棵树就会分割成若干个部分。显然，每个部分内部仍保持连通性。<BR>现在问：删除哪个点，使得分割开的每个连通子图中点的数量不超过N/2？如果有很多这样的点，就按升序输出。<BR>例如,如下图所示的树形图，砍掉顶点3或者顶点8，分割开的各部分满足条件。<BR><img src="/source/joyoi/tyvj-1951/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTk1MS9wcm9ibGVtaW1nL3AxOTUxLmpwZw==.jpg" border=0 align=middle><BR> 

 
 # 输入格式 
第1行：1个整数N，表示顶点数。顶点编号1-N。<BR>接下来n-1行每行两个整数x,y，表示x到y有一条边。 

 
 # 输出格式 
若干行，每行1个整数，表示一个符合条件的顶点的编号。如果没有顶点符合条件，则仅在第1行输出“NONE”。 
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
<tr><td>10
1 2
2 3
3 4
4 5
6 7
7 8
8 9
9 10
3 8
</td><td>3
8</td></tr></table>
