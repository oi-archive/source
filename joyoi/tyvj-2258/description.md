# 

 
 # 题目描述 
<p>
战犯们企图逃离监狱，他们详细地计划了如何逃出监狱本身，逃出监狱之后他们希望在附近的一个村子里找到掩护。村子（下图中的B）和监狱（图中的A）中间有一个峡谷，这个峡谷也是有士兵守卫的。守卫峡谷的士兵们坐在岗哨上很少走动，每个士兵的观察范围是100米。士兵所处位置决定了战犯们能否安全通过峡谷，安全通过的条件就是在任何时刻战犯们距离最近的士兵大于100米。<br>给定峡谷的长、宽和每个士兵在峡谷中的坐标，假定士兵的位置一直保持不变，请你写一个程序计算战犯们能否不被士兵发现，顺利通过峡谷。如果不能，那么战犯们最少需要消灭几个士兵才能安全通过峡谷（无论士兵是否被另一个士兵看到，他都可以被消灭）。<br><br><img border="0" src="/source/joyoi/tyvj-2258/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjI1OC9wcm9ibGVtc19pbWFnZXMvMjYyOC8xMzQwLmpwZw==.jpg"><br></p> 

 
 # 输入格式 
<p>
第一行有三个整数L、W和N，分别表示峡谷的长度、宽度和士兵的人数。接下来的N行，每行两个整数Xi和Yi，表示第i个士兵在峡谷的坐标（0 <= Xi <= L, 0 <= Yi <= W)，坐标以米为单位，峡谷的西南角坐标为(0, 0)，东北角坐标为(L, W)，见上图。注意：通过峡谷可以从(0, ys)（0 <= ys  <= W）到（L, ye）（0 <= ye <= W），其中ys， ye不一定是整数。<br></p> 

 
 # 输出格式 
<p>
只有一行，为一个整数，即安全通过峡谷需要消灭的士兵的人数，如果不需要消灭任何士兵，则输出0。<br></p> 

 
 # 提示 
<p>
1 <= W <= 50,000 1 <= L <= 50,000 1 <= N <= 250</p> 
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
<tr><td>130 340 5
10 50
130 130
70 170
0 180
60 260
</td><td>1</td></tr></table>
