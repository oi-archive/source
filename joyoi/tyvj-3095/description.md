# 

 
 # 题目描述 
<p>
　　城市街道交费系统最近创立了。一辆汽车左转一次需付费$1，右转一次需付费$5。只有当前进、左转、右转都无路可走的时候，调头才是允许的，调头每次付费$10。<br>　　给出一张城市地图，要求你求出从起始点到达终止点的花费最少的路径。幸运的是，所有的道路都是正北、正南、正西或正东方向的。<br>【样例1】<br>　　如下图，符号‘#’代表街道，符号‘.’代表障碍区，符号‘E’表示起始站且汽车面朝东，符号‘F’表示汽车终止点。<br><br><center><img src="/source/joyoi/tyvj-3095/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA5NS9wcm9ibGVtc19pbWFnZXMvMTI1OC8xLmJtcA==.bmp"></img></center><br>　　最便宜的路径花费$8：直走，然后左转3次，最后右转到终止点F。如果先直走然后右转2次，花费将是$10。<br>【样例2】<br>　　如图10-2，符号‘S’表示起始站且汽车面朝南。最便宜的路径花费$7：立刻左转，直走，在第一个岔路口左转，随后右转。<br><br><center><img src="/source/joyoi/tyvj-3095/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA5NS9wcm9ibGVtc19pbWFnZXMvMTI1OC8yLmJtcA==.bmp"></img></center><br>　　城市地图高度最小为4，最大为30，城市地图宽度亦最小为4最大为30。只有一个起点、一个终点，他们之间总存在可通达的路径。同时由于地图周围一圈均是障碍区，所以汽车是没有可能开除城市的。<br><br></p> 

 
 # 输入格式 
<p>
　　输入文件erp.in如下：<br>　　（1）第一行有2个整数，地图高度h和宽度w。<br>　　（2）其后h行每行w个字母，将是以下字母中的一个：<br>　　　　　‘.’表示障碍区<br>　　　　　‘#’表示道路<br>　　　　　‘E’表示起始点且汽车面朝东<br>　　　　　‘W’ 表示起始点且汽车面朝西<br>　　　　　‘N’ 表示起始点且汽车面朝北<br>　　　　　‘S’ 表示起始点且汽车面朝南<br>　　　　　‘F’ 表示终点<br></p> 

 
 # 输出格式 
<p>
　　输出文件erp.out仅包含一个整数，即为最便宜路径的费用。</p> 

 
 # 提示 
<p>
【问题分析】<br>　　求最短路径。<br>　　首先是建图，将地图中的每个点拆成4个结点(每个方向一个)。然后根据题中的要求，前进时边长为0，左转为1，右转为5，调头为10(注意，调头是有条件限制的)。整个图共有4n2个结点。<br>　　对整个图用Dijkstra算法求一个最短路径，即得最小的费用，时间复杂度是O(N2)，其中N=4n2。<br>　　事实上，我们建的图是一个稀疏图，每个点扩展出去的边很少，整个图的边数和点数是同阶的。所以，如果用Dijkstra+Heap去求最短路径，时间复杂度就是O(Nlog2N)，N=4n2。<br><br><br>或：标号法（宽度搜索）</p> 
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
<tr><td>8 11								
...........
....#####..
....#...#..
....#...#..
.#E######..
....#......
.##F#......
...........
</td><td>8</td></tr></table>
