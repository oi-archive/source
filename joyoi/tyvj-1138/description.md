# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;cannot神牛NOIP2009比挂了，但是由于cannot神牛RP极高，最终获得了一等！于是cannot神牛知道了RP的重要性，开始积累更多的RP(这么高的RP，也不怕爆掉~)。cannot神牛一天梦中来到一片神秘的RP果地。<BR>&nbsp;&nbsp;&nbsp;RP果地地图是一个N*M(即为[1..N][1..M])的矩形，地图上每个点上有一个值Aij，如果Aij是正数或者是负数，那么该点长了一种RP值为Aij的RP果，如果Aij为0，那么该点是一个陷阱，cannot神牛当然不能走进陷阱了。<BR>&nbsp;&nbsp;&nbsp;cannot神牛必须从(sx,sy)点移动到(ex,ey)点，这期间一共有K个单位时间，每个单位时间能够从一个点到达上下左右临近的一个点，然后取下一个果子，获得这种果子的RP值(当然不能走出这张地图)，或者可以站在原地不动，但是不能累加到该点的RP果子的RP值。<BR>&nbsp;&nbsp;&nbsp;如果cannot神牛能从起始点(sx,sy)移动到终止点(ex,ey),那么输出cannot神牛最多能采摘到多少RP(起始点的RP值不算在内)，否则输出"Cannot&nbsp;can't!",双引号不输出(暴汗!是"不能,不能!"还是"cannot不能!"？)。<BR> 

 
 # 输入格式 
第一行三个正整数：N，M，K；<BR>第二行四个正整数：sx,sy,ex,ey分别代表起始点、终止点的横纵坐标；<BR>以后N行，每行M个数Aij。<BR> 

 
 # 输出格式 
一行；<BR>输出经过K个单位时间从起始点(sx,sy)移动到终止点(ex,ey)，最多能够积累的RP值，或者是"Cannot&nbsp;can't!"<BR> 

 
 # 提示 
从(1,1)移动到(2,1)获得3点RP，然后从(2,1)移动到(2,2)获得5点RP，总共积累了8点RP。<BR>1&lt;=N,M,K&lt;=200;<BR>对于任意Aij保证在integer范围内；<BR>对于输出保证在longint范围内。<BR>谨以此题献给cannot神牛！对于输出保证在longint范围内。<BR>yuan0818谨以此题献给cannot神牛！<BR> 
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
<tr><td>2 2 2
1 1 2 2
1 2
3 5
</td><td>8</td></tr></table>
