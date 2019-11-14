# 

 
 # 题目背景 
一中为了校庆，举办了校庆典礼。<BR> 

 
 # 题目描述 
faith神牛是一中最刻苦的OIer，他受不了校庆典礼上校长的唠叨，于是毅然决定偷逃向机房。不料刚跑出0.00001米，就被火眼金睛的班主任发现了。<BR>faith神牛被班主任带到了办公室，然后……。<BR>由于班主任对校长的唠叨异常感兴趣，所以在教训完faith神牛后离开了办公室，奔向了典礼现场。<BR>可怜的faith神牛被班主任牢牢地绑在了椅子上，但可喜的是他还可以勉强原地转动身体。<BR>一中的办公楼结构很复杂，在faith神牛的周围，分布着n堵不透明的墙，但每堵墙上都镶嵌有0～1扇豪华的透明玻璃落地窗。<BR>faith神牛眼力超人，只要他和某扇玻璃窗上某一点的连线上没有不透明的墙遮挡，那么他就能够看见这扇窗。<BR>faith神牛为了解闷，开始逐个数他所能够看到的玻璃窗。那么他究竟能够看到几扇玻璃窗呢。<BR><BR>注意：<BR>1、当faith神牛恰好处于某堵墙的正侧面的时候（在faith神牛的视角看来，这堵墙就是竖直的一条细线），这堵墙上的玻璃窗就无法被faith神牛看到了。<BR>2、当faith神牛的视线恰好经过某堵墙或窗的边缘，faith神牛的视线不会被阻挡。<BR> 

 
 # 输入格式 
输入数据包含n+1行<BR>第一行包含三个整数n、x0与y0，分别代表墙的数目和faith神牛的坐标(x0,y0)。<BR>以后n行每行包含八个实数，用空格分开。<BR>设第i+1行的八个实数为x1,y1,x2,y2,x3,y3,x4,y4。<BR>代表第i堵墙的两个端点的坐标为(x1,y1)和(x2,y2)。<BR>第i堵墙上玻璃窗的端点坐标为(x3,y3)(x4,y4)。<BR>当x3=x4且y3=y4的时候，代表第i堵墙上没有玻璃窗。<BR><BR>保证墙的两个端点不重合且玻璃窗的端点都在相应的墙上。<BR>保证任意两堵墙没有公共点且faith神牛不在墙体内。<BR> 

 
 # 输出格式 
输出数据仅包含一个整数，表示faith神牛能够看到的玻璃窗数目。<BR> 

 
 # 提示 
样例解释：<BR>如图，黑色为墙壁，蓝色为窗户，红色为faith神牛。<BR>显然，两个窗户faith神牛都能看见。<BR><img src="/source/joyoi/tyvj-1683/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTY4My9odHRwOi8vd3d3LmZpbGVkZW4uY29tL2ZpbGVzLzIwMTEvNC8xNS8zMTE1OTI1L2Rvb3JzLnBuZw==.png" border=0 align=middle><BR><BR>数据范围：<BR>对于20%的数据，n&lt;=10<BR>对于40%的数据，n&lt;=50<BR>对于60%的数据，n&lt;=100<BR>对于80%的数据，n&lt;=500<BR>对于100%的数据，1&lt;=n&lt;=2000,各点坐标的绝对值&lt;=1000<BR> 
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
<tr><td>2 4 3
0 0 0 5 0 1 0 3
3.0 0.0 0 6.0 2 2 1 4
</td><td>2
</td></tr></table>
