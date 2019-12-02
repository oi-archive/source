# 

 
 # 题目描述 
<p>
树的最长链<br>　　乌托邦有n个城市，某些城市之间有公路连接。任意两个城市都可以通过公路直接或者间接到达，并且任意两个城市之间有且仅有一条路径（What does this imply? A tree!）。<br>　　每条公路都有自己的长度，这些长度都是已经测量好的。<br>　　小修想从一个城市出发开车到另一个城市，并且她希望经过的公路总长度最长。请问她应该选择哪两个城市？这个最长的长度是多少？<br></p> 

 
 # 输入格式 
<p>
　　第一行n（n <= 1000）。<br>　　以下n-1行每行三个整数a, b, c。表示城市a和城市b之间有公路直接连接，并且公路的长度是c(c <= 10000)。<br></p> 

 
 # 输出格式 
<p>
　　仅一个数，即最长长度。<br>　　</p> 

 
 # 提示 
<p>
求任何无根树的最长链算法：<br>　　（1）以任意一个点a为根，进行树型dp，找到一个距离a点最远的点b。<br>　　（2）再以点b为根，再进行树型dp，找到一个距离b点最远的点c。<br>　　（3）则b与c之间的距离即为树的最长链。<br>　　<br>　　注：如果结点间距离为1，也可以用宽度搜索代替树型dp（参见：problem　1901）。<br><br><br>优秀代码参考：　东莞中学初中部 肖遥<br><br><center><img src="/source/joyoi/tyvj-3442/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzQ0Mi9wcm9ibGVtc19pbWFnZXMvMTA0NS8xLmJtcA==.bmp"></img></center></p> 
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
<tr><td>Longest.in
5
1 2 2
2 3 1
2 4 3
1 5 4

</td><td>Longest.out
9



说明：从城市4到城市5，经过的路径是4-2-1-5，总长度是9。</td></tr></table>
