# 

 
 # 题目描述 
<p>
　　公元5000年，x市考古队发现了一份三千年前的文献，上面记录了公元2000年的一场足球盛事：曼联、罗马、拜仁、皇马、里昂这五支当时世界的五大联赛的冠军球队之间将进行地球总冠军争夺战。由于足球是当时的第一大运动，因此，这份文献对了解当时世界各地的体育发展水平乃至社会生活状况都有着重要意义。遗憾的是，由于年代久远，文献的比分部分被污损了。于是，x市的专家们想方设法地要恢复它。<br>　　据考证得知，那次比赛为单循环赛制，每支球队都与其他四支球队各赛一场，一共10场比赛（注意：这与当时流行的主客场制不同，因此这份文献更有特殊意义）。每场比赛的结果：赢球的一方积3分，输球的一方不得分；平局则双方各积一分。文献残余的部分显示了每支球队的总积分，总进球数与总失球数。专家们希望可以找出一种可能的每场比分方案，使之与统计结果相符。<br>　　例如，发现的一份文献如下：<br><br><center><img src="/source/joyoi/tyvj-3138/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEzOC9wcm9ibGVtc19pbWFnZXMvMTQyMy8xLmJtcA==.bmp"></img></center> 　　　　　　 <br>　　则一种可能的比分方案为：<br><br><center><img src="/source/joyoi/tyvj-3138/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEzOC9wcm9ibGVtc19pbWFnZXMvMTQyMy8yLmJtcA==.bmp"></img></center> 　　　　　　 <br></p> 

 
 # 输入格式 
<p>
　　每个输入数据有五行，从上到下依次代表曼联、罗马、拜仁、皇马、里昂这五支球队的统计数据。每行三个数据，分别为该支球队的总积分，总进球数，总失球数。<br><br></p> 

 
 # 输出格式 
<p>
　　每个输出数据为一个5*5的矩阵，矩阵中的每个元素用x：y的形式表示。第i行第j列（i<>j）的元素代表在i，j两支球队的比赛中"第i支球队的进球数：第j支球队的进球数"，相邻两元素间用一个空格隔开（球队按输入顺序从1到5编号），第i行第i列用"－：－"表示。矩阵应当是对称的。<br>　　注意，由于各支球队实力都很强，可以认为 每支球队的每场失球数不超过5个。<br></p> 

 
 # 提示 
<p>
缺测试数据！！</p> 
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
<tr><td>9 14 10
9 6 5
7 11 9
3 7 9
1 6 11
</td><td>--- 0-1 4-1 5-4 5-4 
1-0 --- 1-5 1-0 3-0 
1-4 5-1 --- 3-2 2-2 
4-5 0-1 2-3 --- 1-0 
4-5 0-3 2-2 0-1 ---</td></tr></table>
