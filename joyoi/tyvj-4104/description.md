# 

 
 # 题目背景 
<p><b>汕头五校联赛Day2第三题(by&nbsp;xcl)</b></p> 

 
 # 题目描述 
<p><strong>S城最近闪电风暴频繁出现，作为雷电防御总局的CJJ收到一个任务，要在S城建设避雷针，以减少因雷电而带来的灾害。首先他要知道地面哪些地点常常遭雷击，故他找到闪电爱好者XCL，并与他讨论。他们利用空气微观分子监测技术收集了空气中各个时刻的空气分子之间的电阻（Rxy(没有列举出的两点间电阻视为无穷大)）和闪电的爆发点（在空中一点（记为1）），每一时刻闪电都会从爆发点开始，选择一条总电阻和最小的路径到达地面某些点（当有多条路径的总电阻和相等时，闪电会在中间某一些点发生分岔，并同时击中地面多点）。现在，他们要你帮助，给你t个时刻，每个时刻的空气点数n（编号为1..n）、空气点x到空气点y间的电阻值Rxy（共m条路径）、并给你o个地面上的点Xi，要你算出该时刻闪电落地点（SPOTi）（可能会有多个）。</strong></p> 

 
 # 输入格式 
<p><strong>第一行：t</strong></p>

<p>&nbsp;&nbsp;&nbsp;<strong>以下t组数据每组第一行：n,m,o</strong></p>

<p>&nbsp;&nbsp;&nbsp;<strong>接下来m行：x,y,Rxy表示x点到y点的电阻值Rxy（注意，x到y的Rxy有且只有一个，不需考虑重复电阻值）</strong></p>

<p>&nbsp;&nbsp;&nbsp;<strong>再接下来一行：o个地面点（SPOTi）</strong></p> 

 
 # 输出格式 
<p><strong>对于每组数据，各两行：</strong></p>

<p>&nbsp;&nbsp;&nbsp;<strong>第一行：Q表示该时刻闪电共有多少个落地点（数据保证至少有一个落地点,</strong>&nbsp;<strong>且从爆发点到落地点的电阻之和不会是无穷大）</strong></p>

<p>&nbsp;&nbsp;&nbsp;<strong>第二行：Q个正整数表示各个落地点的编号（按从小到大的顺序输出）</strong></p> 

 
 # 提示 
<p><strong style="line-height: 1.6em;">数据范围：</strong></p>

<p><strong>对于40%数据，t&lt;=10,&nbsp;n&lt;=1000</strong></p>

<p><strong>对于60%数据，t&lt;=10,&nbsp;n&lt;=5000</strong></p>

<p><strong>对于90%数据，t&lt;=100,&nbsp;n&lt;=10000</strong></p>

<p><strong>对于100%数据，t&lt;=100,&nbsp;n&lt;=100000,&nbsp;m&lt;=10000，o&lt;=n,&nbsp;Rxy&lt;=100，&nbsp;SPOTi&lt;=n</strong></p> 
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
10 6 3
1 2 10
2 3 5
1 3 20
2 4 30
2 5 20
3 6 1
4 5 6
10 4 2
1 2 10
1 3 1
2 4 2
2 5 5
4 5
</td><td>1
6
1
4
</td></tr></table>
