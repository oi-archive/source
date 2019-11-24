# 

 
 # 题目描述 
<p>
　　春天到了，百花齐放，西湖公园里新设置了许多花坛，设计师想用不同的花摆出不同的图案以吸引游人，于是设计了各种图案并且在花圃中选好了要摆放的花。不幸的是负责搬运和摆放的工人因为临时有事，只将花放到花架上就匆匆离开了，并没有按照设计师原来的设计方案摆放，结果花坛杂乱不堪,设计师只好自己来调整花的位置。由于设计师通常从事脑力劳动，较少从事搬运和摆放花盆的体力工作，所以请你帮忙找出一种移动方法使工作量最小。<br><br>　　不同种类的花有不同的类型编号，虽然地球上花的种类很多，但因为公园里的花不超过1,000,000种，所以花的类型编号不超过1,000,000。另一方面，出于美学考虑，一个花坛里摆放的不同种类的花不超过3种，且不同种类的花的数量不可太接近，对于任意两种花，数量多的花的盆数至少是数量少的花的2倍。<br>　　花坛是正六边形的，共摆放有19盆花，每盆花都放在一个转盘上，转动一盆花下面的转盘，会使周围的6盆花顺时针或逆时针移动一个位置（但不可把花转到花坛外），称为一次操作。你的任务：用最少的操作使花坛由初始状态转化为符合设计图纸的目标状态。<br>例如： <br><br><center><img src="/source/joyoi/tyvj-3151/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE1MS9wcm9ibGVtc19pbWFnZXMvMTQzOC8xLmJtcA==.bmp"></img></center>　　　 <br>　　　　　　　　　　　　　　　　　　初始状态　　　　　　　　　　　　　　目标状态<br><br>　　如图，只需将处于圆心位置的那盆花的转盘顺时针转动一个位置，红色的花就移动到了目标位置。<br></p> 

 
 # 输入格式 
<p>
　　输入文件共11行，１－5行描述花坛的初始状态，7－11行表示花盆应摆放的位置。中间以空行分隔。5行数字分别表示花坛的5个行，其中第1、5两行有3个整数，第2、4两行有4个整数，第3行有5个整数，表示每一行的花的类型，不同的数代表不同种类的花。</p> 

 
 # 输出格式 
<p>
　　输出文件第一行包含一个整数T即最少的操作数，数据保证20步之内有解。以下T行输出操作序列，每行代表一次操作，包括3个整数 , , ,（ , ）表示第i步转动第 行，第 盆花下的转盘，当 为0时表示向顺时针方向转动， 为1时表示向逆时针方向转动，如有多种方案，任意输出其中一种即可。</p> 
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
<tr><td><br><img src="/source/joyoi/tyvj-3151/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE1MS9wcm9ibGVtc19pbWFnZXMvMTQzOC8yLmJtcA==.bmp"></img>　
<br><img src="/source/joyoi/tyvj-3151/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE1MS9wcm9ibGVtc19pbWFnZXMvMTQzOC8zLmJtcA==.bmp"></img>　</td><td>1
3 2 0
 </td></tr></table>
