# 

 
 # 题目描述 
<p>
给你一个无向图，N(N<=500)个顶点, M(M<=5000)条边，每条边有一个权值Vi(Vi<30000)。给你两个顶点S和T，求一条路径，使得路径上最大边和最小边的比值最小。如果S和T之间没有路径，输出”IMPOSSIBLE”，否则输出这个比值，如果需要，表示成一个既约分数。 <br>备注： 两个顶点之间可能有多条路径。</p> 

 
 # 输入格式 
<p>
第一行包含两个正整数，N和M。<br>下来的M行每行包含三个正整数：x，y和v。表示景点x到景点y之间有一条双向公路，车辆必须以速度v在该公路上行驶。<br>最后一行包含两个正整数s，t，表示想知道从景点s到景点t最大最小速度比最小的路径。s和t不可能相同。<br><br></p> 

 
 # 输出格式 
<p>
如果景点s到景点t没有路径，输出“IMPOSSIBLE”。否则输出一个数，表示最小的速度比。如果需要，输出一个既约分数。<br></p> 
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
<tr><td>【样例输入1】
4 2
1 2 1
3 4 2
1 4

【样例输入2】
3 3
1 2 10
1 2 5
2 3 8
1 3


【样例输入3】
3 2
1 2 2
2 3 4
1 3

</td><td>【样例输出1】
IMPOSSIBLE

【样例输出2】
5/4
【样例输出3】
2

【数据范围】
1<  N < = 500
1 < = x, y < = N，0 < v < 30000，x ≠ y
0 < M < =5000
</td></tr></table>
