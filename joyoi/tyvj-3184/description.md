# 

 
 # 题目描述 
<p>
问题描述：<br>　　现在政府计划在某个区域内的的城市间架设高速公路，以使任意两个城市间能够直接或间接到达，怎样修路，费用最小。<br></p> 

 
 # 输入格式 
<p>
　　第一行两个整数 n，m，期中n(n <= 3000)表示城市数目，m表示城市间现有的道路条数，接下来共有m行，每行三个数xi,yi,ti(0 <= xi,yi <= 1500)表示修城市xi到城市yi的费用为ti。</p> 

 
 # 输出格式 
<p>
　　一行，一个结果值，表示总共的最小费用。<br></p> 

 
 # 提示 
<p>
分析：<br>　　本题是一个典型的最小生成树问题，可用kuruskal算法解题，算法思路如下：<br>　　每次选不属于同一连通分量(保证无圈)且边权值最小的2个顶点，将边加入最小生成树集合中，并将所在的2个连通分量合并，直到只剩一个连通分量。<br>算法实现：<br>　　1、将边按非降序排列；<br>　　while 合并次数　少于　顶点数-1　begin<br>　　　　取一条边(u,v)(因为已经排序，所以必为最小)<br>　　　　if 顶点u,v不属于同一连通分量 then<br>　　　　　　合并u,v所在的连通分量，（注：此处使用并查集实现，以提高效率！）<br>　　　　　　//如果需要输出选用的边，输出边(u,v)。<br>　　　　　　合并次数增1；tot=tot+w(u,v)<br>　　end;<br>　　算法结束：tot为最小生成树的总权值<br><br><br>特别提示：<br>　　本题的限时为0.5秒！同样的测试数据量，采用prim和kruskal算法，必然超过1秒，可以参见本在线题库中，p1041，p1042的测试结果。采用并查集降低运行时间！</p> 
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
<tr><td></td><td></td></tr></table>
