# 

 
 # 题目描述 
<p>
Mirko 和 Slavko 正在玩动物玩具的游戏。 首先，他们要在下图给出的三种玩具模板中选择一种。三种模板分别由一维、二维和三维的网格点（在图中用圆圈表示）组成。<br><br><img border="0" src="/source/joyoi/tyvj-2630/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYzMC9wcm9ibGVtc19pbWFnZXMvMzA4MC8xODA3LmpwZw==.jpg"> <br> <br>接下来Mirko 把 N 个小动物玩具放到选中的模板的网格点上。<br>动物玩具可以走一步到达与它相邻的网格点上（在图中相邻的点之间有一条小短线相连）。两个网格点之间的距离定义为从一个网格点到另一个网格点所需要移动的最小步数。<br>如果两个动物之间的距离小于等于D，则它们之间可以互相听见。Slavko 的任务是计算在模板上有多少对动物可以互相听得见。<br>任务<br>给定模板的类型、所有动物的位置以及数字D，写一个程序计算有多少对动物可以互相听得见。<br></p> 

 
 # 输入格式 
<p>
输入的第一行按顺序给出四个整数：<br>&#8226; 模板类型 B (1 ≤ B ≤ 3);<br>&#8226; 玩具动物的数目 N (1 ≤ N ≤ 100 000);<br>&#8226; 动物之间可以互相听得见的最大距离D (1 ≤ D ≤ 100 000 000);<br>&#8226; 模板的大小 M ( 即在输入中允许的最大的坐标值):<br>&#61607; 当 B=1 时, M 最大是 75 000 000.<br>&#61607; 当 B=2时, M 最大是 75 000.<br>&#61607; 当 B=3时, M 最大是 75.<br>接下来的N 行每行包含B 个整数，整数之间用空格隔开，表示一个动物玩具的坐标。坐标的取值范围是1 到 M ( 包括M )。<br>每个网格点可以同时包含多个动物玩具。<br></p> 

 
 # 输出格式 
<p>
输出应该包括一个整数，表示可以互相听得见的玩具动物的对数。<br>注意：使用64 位整数类型计算和输出结果 (在 C/C++ 中用long long, 在Pascal 中用int64 ) 。<br><br>评分<br>在30分的测试数据中, 动物数目 N 最多是 1 000。<br>如果成功通过了某一种模板（一维、二维或者三维）的全部测试数据，将会得到至少30分。<br></p> 

 
 # 提示 
<p>
对于input 1的解释： 假设动物按给出的顺序编号为1到6。4对互相能够听得到的动物分别是:<br>&#8226; 1-5 ( 距离是5)<br>&#8226; 1-6 ( 距离是2)<br>&#8226; 2-3 ( 距离是0)<br>&#8226; 5-6 ( 距离是3)<br>对于input 2 的解释：8对动物分别是:<br>&#8226; 1-2 ( 距离是2)<br>&#8226; 1-4 ( 距离是4)<br>&#8226; 1-5 ( 距离是3)<br>&#8226; 2-3 ( 距离是3)<br>&#8226; 2-4 ( 距离是4)<br>&#8226; 3-4 ( 距离是3)<br>&#8226; 3-5 ( 距离是4)<br>&#8226; 4-5 ( 距离是3)<br></p> 
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
<tr><td>input 1
1 6 5 100 
25 
50 
50 
10 
20 
23 

input 2
2 5 4 10 
5 2 
7 2 
8 4 
6 5 
4 4 
</td><td>output 1
4 

output 2 
8 </td></tr></table>
