# 

 
 # 题目描述 
<p>
　　一个探险家，在一个山洞里发现了一大笔宝藏，但他不慎碰到了自毁开关，来时的道路损坏并且在一定时间内整个山洞将塌毁，因此他不得不通过一个住满吸血蝙蝠的迷宫，故事从这里开始了。<br>　　在这个m列n行的迷宫中，有p个石柱，另有b只吸血蝙蝠。<br>　　蝙蝠分三种类型：<br>　　　　① 当蝙蝠前方遇到石柱或墙，向左转。<br>　　　　② 当蝙蝠前方遇到石柱或墙，向后转。<br>　　　　③ 当蝙蝠前方遇到石柱或墙，向右转。<br>　　人可以向上、下、左、右四个方向移动或在原位置等待，人运动一格或等待，都花费一个单位时间。在一个单位时间内，蝙蝠和人可以同时移动。蝙蝠也可以向上、下、左、右四个方向移动或旋转，注意旋转不花时间，也就是说蝙蝠和人都可以先旋转再移动。同一时刻，人和蝙蝠在同一地点时，人死亡。人和蝙蝠可以互相穿过，且蝙蝠可以重叠。<br><br><center><img src="/source/joyoi/tyvj-3142/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE0Mi9wcm9ibGVtc19pbWFnZXMvMTQyOS8xLmJtcA==.bmp"></img></center>　　　　 <br>　　上图的情况是人和蝙蝠互相穿过的情况，是合法的。<br>　　现在有一个人从（1,1）逃到（m,n），仅有（m+n-1）单位的时间，问在（m+n-1）单位的时间内共有几种逃脱路线。<br>　　注：在第１个时刻，人进入（1,1），蝙蝠赋初始状态，在第（m+n-1）时刻，人要到达（m,n）。<br>　　若初始状态中蝙蝠与石柱重合，则认为蝙蝠在石柱上休息，不会动。<br><br><center><img src="/source/joyoi/tyvj-3142/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE0Mi9wcm9ibGVtc19pbWFnZXMvMTQyOS8yLmJtcA==.bmp"></img></center>　<br></p> 

 
 # 输入格式 
<p>
　　输入文件第1行为m，n;第2行为石柱个数p；以下p行，每行两个整数，分别为石柱的横、纵坐标；第p+3行，为蝙蝠数b；以下b行，每行四个整数，分别为蝙蝠的横、纵坐标，蝙蝠方向d（上为１，左为２，下为３，右为４），以及蝙蝠类型t用１,２,３表示。<br>　　2 <= M <= 100 ; 2 <= N <= 100 ; 0 <= p <= 100 ; 0 <= b <= 100<br></p> 

 
 # 输出格式 
<p>
　　仅一行，为逃脱的方法数，若无解则输出０。</p> 
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
<tr><td>3 3
1
1 2
1
2 3 1 1

</td><td>3</td></tr></table>
