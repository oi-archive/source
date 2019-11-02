# 

 
 # 题目描述 
<p>
暑假到了，Philia想回家乡度过一个愉快的旅程。假设有N个地方是Philia很感兴趣的。对于任意两个地方，有且只有两条公路，一条从A到B，一条从B到A。公路有两种类型，R1和R2。公共汽车在R1上行走，人们在R2上行走。如果从A到B，走R2会花费T2分钟，而走R1只需要花费T1分钟（当然，T1 < T2）。<br>你不能坐公共汽车从A到B，再到C,…，最后回到A。也就是说，不存在所有边都是R1边的回路C1->C2->…->Ck->C1。<br>现在Philia想从一个地方出发，然后访问所有的地方，最后回到原来出发的地方。Philia会在每个地方逗留T分钟。请编程计算Bob所需的最小的时间。<br>比如说，如图3.1。(A)有4个地方，(B)是其中一条最优路线 (A->B->C->D->A). 实线表示R1路，虚线表示R2路。<br>可以看出，在(B)，Philia需要花费 T+T1+T+T2+T+T1+T+T2=4*T+2*T1+2*T2分钟。<br><br><center><img src="/source/joyoi/tyvj-2997/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk5Ny9wcm9ibGVtc19pbWFnZXMvMzYxMC90LmJtcA==.bmp"></img></center><br> <br>			(A)											(B)<br>图3.1	乡村公路<br></p> 

 
 # 输入格式 
<p>
输入包含多组测试数据。第一行包含一个正整数T，表示测试数据数目。每组测试数据包含两部分，第一部分包含四个整数N (1<N<100), T, T1, T2 (0<T, T1, T2<100)。第二部分包含N*N的矩阵M。Philia需要花费M[i][j]分钟从i地到达j地。数据保证当i=j，则M[i][j]=0，否则M[i][j]必定等于T1或T2 (T1<T2)。</p> 

 
 # 输出格式 
<p>
对每一组测试数据。输出一行包含一个整数S，表示Philia需要花费的最少时间。</p> 
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
4 10 10 20
0 10 10 10
20 0 20 20
20 20 0 10
20 20 20 0
</td><td>100</td></tr></table>
