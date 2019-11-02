# 

 
 # 题目描述 
Henryy&nbsp;国正致力于首都的一个旅游电车建设工程。首都有&nbsp;N&nbsp;个旅游景区。<BR>Henryy&nbsp;国的电车永远只沿道路规定的方向行驶，为了不使投入使用的电车有可<BR>能无法回到它的起始站，&nbsp;Henryy希望知道他的首都的可以在哪些景区设置站点。<BR>一个景区可以被设置成车站，当且仅当对于任意一个从该景区出发所能到达的景<BR>区，均至少有一条路可回到该景区。你的同事已完成了一份景区之间的道路连通<BR>情况的报告。报告中将给出首都的景区数目&nbsp;N、道路总数&nbsp;M&nbsp;以及一些形如“景<BR>区&nbsp;A&nbsp;和景区&nbsp;B&nbsp;之间有一条从&nbsp;A&nbsp;到&nbsp;B&nbsp;的单向道路”的信息。现在明确你的任务：<BR>根据报告中的信息，列出所有可以被设置成车站的景区。&nbsp;<BR> 

 
 # 输入格式 
【输入文件】&nbsp;<BR>输入文件由多份报告组成（这些报告相互无任何联系），每份报告包括：N，<BR>M，接下来&nbsp;M&nbsp;对整数&nbsp;Ai、Bi&nbsp;(1&lt;=I&lt;=M)表示&nbsp;Ai&nbsp;和&nbsp;Bi&nbsp;之间有一条单向道路<BR>Ai?Bi。仅一个包含整数&nbsp;N=0&nbsp;的报告表示你的工作结束，你的程序不应该对此<BR>有任何反应。各整数间用空格或空行分隔。对于任意景区，分别以该景区为起点<BR>或终点的道路总数均不超过&nbsp;50。&nbsp;<BR> 

 
 # 输出格式 
【输出文件】&nbsp;<BR>&nbsp;&nbsp;对于每份报告，输出一行列表包括：所有能被设置成电车站点的景区编号，<BR>各编号之间用一个空格隔开。&nbsp; 

 
 # 提示 
【数据约定】&nbsp;<BR>&nbsp;&nbsp;对于&nbsp;40%的数据，有N&lt;=200。&nbsp;<BR>对于&nbsp;100%的数据，有&nbsp;N&lt;=5000。&nbsp; 
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
<tr><td>【样例输入】 
5 6 
1 2 
2 3 
3 4 
4 1 
2 5 
5 2 
 
1 0 
 
0 
</td><td>【样例输出】 
1 2 3 4 5 
1 
</td></tr></table>
