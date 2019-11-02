# 

 
 # 题目描述 
<p>
给定一个连通无向图，判断其最小生成树是否唯一。<br>定义1（生成树）：在连通无向图G = (V, E) 中，生成树是图G的子图T = (V', E')，图T具有如下特征：<br>1. V' = V；<br>2. T 是连通无回路的。<br>定义2（最小生成树）：在带权的连通无向图G = (V, E) 中，最小生成树T = (V, E') 是G 的生成树中各边权值之和最小的。 <br></p> 

 
 # 输入格式 
<p>
第一行包含一个整数t (1 <= t <= 20)，表示测试数据组数。每一组数据代表一个图。每组数据以整数n和m开头，分别代表点数和边数，其中1 <= n <= 100。接下来m行每一行包含一个三元组 (xi, yi, wi)，表示从点 xi 到 yi 有一条权重为 wi 的表连接。任意两个点之间最多只有一条边。</p> 

 
 # 输出格式 
<p>
对于每组数据，如果最小生成树唯一，则输出其各边权值之和，否则输出字符串“Not Unique!”。</p> 
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
<tr><td>2
3 3
1 2 1
2 3 2
3 1 3
4 4
1 2 2
2 3 2
3 4 2
4 1 2
</td><td>3
Not Unique!</td></tr></table>
