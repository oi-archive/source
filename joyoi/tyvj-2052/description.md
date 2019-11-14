# 

 
 # 题目背景 
（话说GJQ要给CS&nbsp;#2提供一道题，好激动）<br><br> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;GJQ成为了一个景区的负责人！他的领导admin大人交给他一个任务，让他负责设计景区的接待方案。<br>&nbsp;&nbsp;&nbsp;&nbsp;从车站到景区的区域有N个路口，由M条双向道路连接，车站在1号路口，景区在N号路口，每条道路有一个长度len，在每一条道路上的每个单位长度都有一盏彩灯，即一条len长度的道路有len盏彩灯。<br>&nbsp;&nbsp;&nbsp;&nbsp;现在GJQ要负责T天的接待，具体来说是设计接待车从车站到景区的路线，一旦某天的路线确定，这条路线经过的所有道路上的彩灯就必须开一整天，每盏灯开一天需要的费用为1。<br>&nbsp;&nbsp;&nbsp;&nbsp;由于一些不为人知的原因，在某些时间段内某一个路口可能不能经过，与此同时与这个路口相连的边也不能通过，这就意味着每天的路线不一定会相同，定义某一天和上一天的路线不同（定义路线不同为路线经过的边集不同或经过边的顺序不同）为一次路线修改，由于线路配置等原因，每一次路线修改需要额外花费K的费用。（你可以认为存在第0天，第0天的路线始终与第1天相同）<br>&nbsp;&nbsp;&nbsp;&nbsp;现在GJQ想知道，完成这T天的接待所需要的最小总费用是多少？<br><br> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行包含一个数TEST，表示数据组数<br>&nbsp;&nbsp;&nbsp;&nbsp;接下来TEST组数据，对于每一组数据：<br>&nbsp;&nbsp;&nbsp;&nbsp;第一行三个数T，N，K，M含义见题目描述<br>&nbsp;&nbsp;&nbsp;&nbsp;接下来M行，每行三个数u，v，len，表示从u路口到v路口有一条长度为len的无向道路<br>&nbsp;&nbsp;&nbsp;&nbsp;接下来一行一个数P，表示有P个限制条件<br>&nbsp;&nbsp;&nbsp;&nbsp;接下来P行，每行三个数x,l,r，表示由于不为人知的原因，在第l天到第r天不能通过x路口<br><br> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;一行一个数，表示最小总费用。<br><br> 

 
 # 提示 
N&lt;=10,M&lt;=N*(N-1)/2,T&lt;=10000,K&lt;=5000,P&lt;=100,TEST仅为常数大小，不必计算在时间复杂度内<br>答案保证在int范围内<br>限制条件可能会出现相交的情况<br><br>GJQ<br><br> 
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
<tr><td>1
5 5 10 8
1 2 1
1 3 3
1 4 2
2 3 2
2 4 4
3 4 1
3 5 2
4 5 2
4
2 2 3
3 1 1 
3 3 3
4 4 5

</td><td>32

</td></tr></table>
