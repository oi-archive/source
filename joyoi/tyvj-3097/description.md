# 

 
 # 题目描述 
<p>
　　Bb喜欢玩电脑游戏，特别是战略游戏。但是他经常无法找到快速玩过游戏的办法。现在他有个问题。他要建立一个古城堡，城堡中的路形成一棵树。他要在这棵树的结点上放置最少数目的士兵，使得这些士兵能了望到所有的路。注意，某个士兵在一个结点上时，与该结点相连的所有边将都可以被了望到。请你编一程序，给定一树，帮Bob计算出他需要放置最少的士兵。<br>输入格式：<br>　　输入文件Strategi.in中数据表示一棵树，描述如下：<br>　　第一行 N，表示树中结点的数目。<br>　　第二行至第N+1行，每行描述每个结点信息，依次为：该结点标号i，k(后面有k条边与结点I相连)，接下来k个数，分别是每条边的另一个结点标号r1，r2，...，rk。对于一个n( 0 < n  <= 1500)个结点的树，结点标号在0到n-1之间，在输入文件中每条边只出现一次。<br>输出格式：<br>　　输出文件Strategi.out仅包含一个数，为所求的最少的士兵数目。<br>　　例如，对于如图1所示的树：答案为1（只要一个士兵在结点1上）。<br><br><img src="/source/joyoi/tyvj-3097/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA5Ny9wcm9ibGVtc19pbWFnZXMvMTI2MC8xYS5ibXA=.bmp"></img></p> 

 
 # 输入格式 
<p>
4<br>0 1 1<br>1 2 2 3<br>2 0<br>3 0<br></p> 

 
 # 输出格式 
<p>
1<br><br><br>样例1：配图<br><br><img src="/source/joyoi/tyvj-3097/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA5Ny9wcm9ibGVtc19pbWFnZXMvMTI2MC8xYS5ibXA=.bmp"></img></p> 

 
 # 提示 
<p>
分析：<br>　　本题的数学模型实质是：对于给定的图（这里的图是一棵树），求这个图的最小顶点覆盖（如图2），　图的最小顶点覆盖是NP问题，至今还没有有效算法。而本题N的规模可达1500，显然用搜索是无法完成的。但本题的图十分特殊是一棵树。很明显，叶节点不可能属于覆盖集，但叶节点的父节点一定属于覆盖集，以此为基础再判断上一层次节点是否属于覆盖集。这也就是贪心算法的一个应用。图的节点编号从大到小正好是我们判断的顺序，该顺序恰好是树的前序遍历顺序，具体算法如下：<br>　　（1）按前序遍历顺序重新编排整棵树的节点编号。<br>　　（2）对每个结点作没有被覆盖标记；<br>　　（3）从结点N到结点2判断：如果本结点及其父结点都没有被覆盖，则被其父结点作覆盖标记。<br>　　（4）已作覆盖标记的结点个数就是所求的要安排的最少士兵数。<br><br>[配图2]<br><br><img src="/source/joyoi/tyvj-3097/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA5Ny9wcm9ibGVtc19pbWFnZXMvMTI2MC8xYi5ibXA=.bmp"></img><br></p> 
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
<tr><td>5
3 3 1 4 2
1 1 0
2 0
0 0
4 0
</td><td>2

</td></tr></table>
