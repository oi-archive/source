# 

 
 # 题目描述 
<p>
汽车加油行驶问题(trav.cpp/c/pas)<br><br>【问题描述】<br><br>　　给定一个N*N 的方形网格，设其左上角为起点◎，坐标为（1，1），X 轴向右为正，Y轴向下为正，每个方格边长为1，如图所示。一辆汽车从起点◎出发驶向右下角终点▲，其坐标为（N，N）。在若干个网格交叉点处，设置了油库，可供汽车在行驶途中加油。汽车在行驶过程中应遵守如下规则：<br>　　(1)汽车只能沿网格边行驶，装满油后能行驶K 条网格边。出发时汽车已装满油，在起点与终点处不设油库。<br>　　(2)汽车经过一条网格边时，若其X 坐标或Y 坐标减小，则应付费用B，否则免付费用。<br>　　(3)汽车在行驶过程中遇油库则应加满油并付加油费用A。<br>　　(4)在需要时可在网格点处增设油库，并付增设油库费用C（不含加油费用A）。<br>　　(5)(1)～(4)中的各数N、K、A、B、C均为正整数，且满足约束：2≤N ≤ 100，2 ≤ K ≤ 10。<br>　　设计一个算法，求出汽车从起点出发到达终点的一条所付费用最少的行驶路线。<br><br><center><img src="/source/joyoi/tyvj-3211/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxMS9wcm9ibGVtc19pbWFnZXMvMTYxOC9wMS5naWY=.gif"></img></center><br><br>【编程任务】<br><br>　　对于给定的交通网格，计算汽车从起点出发到达终点的一条所付费用最少的行驶路线。</p> 

 
 # 输入格式 
<p>
由文件trav.in提供输入数据。<br>　　文件的第一行是N，K，A，B，C的值。第二行起是一个N*N 的0-1 方阵，每行N 个值，至N+1 行结束。方阵的第i 行第j 列处的值为1 表示在网格交叉点（i，j）处设置了一个油库，为0 时表示未设油库。各行相邻两个数以空格分隔。</p> 

 
 # 输出格式 
<p>
程序运行结束时，将最小费用输出到文件trav.out中。</p> 
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
<tr><td>9 3 2 3 6
0 0 0 0 1 0 0 0 0
0 0 0 1 0 1 1 0 0
1 0 1 0 0 0 0 1 0
0 0 0 0 0 1 0 0 1
1 0 0 1 0 0 1 0 0
0 1 0 0 0 0 0 1 0
0 0 0 0 1 0 0 0 1
1 0 0 1 0 0 0 1 0
0 1 0 0 0 0 0 0 0</td><td>12</td></tr></table>
