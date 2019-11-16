# 

 
 # 题目描述 
<p>
农夫约翰的奶牛住在N (2 <= N <= 200,000)片不同的草地上，标号为1到N。恰好有N-1条单位长度的双向道路，用各种各样的方法连接这些草地。而且从每片草地出发都可以抵达其他所有草地。也就是说，这些草地和道路构成了一种叫做树的图。输入包含一个详细的草地的集合，详细说明了每个草地的父节点P_i (0 <= P_i <= N)。根节点的P_i == 0, 表示它没有父节点。因为奶牛建立了1到K一共K (1 <= K <= N/2)个政党。每只奶牛都要加入某一个政党，其中，<br>第i只奶牛属于第A_i (1 <= A_i <= K)个政党。而且每个政党至少有两只奶牛。<br>这些政党互相吵闹争。每个政党都想知道自己的“范围”有多大。其中，定义一个政党的范围是这个政党离得最远的两只奶牛（沿着双向道路行走）的距离。<br>比如说，记为政党1包含奶牛1，3和6，政党2包含奶牛2，4和5。这些草地的连接方式如下图所<br>示（政党1由-n-表示）：<br><img border="0" src="/source/joyoi/tyvj-2607/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYwNy9wcm9ibGVtc19pbWFnZXMvMzA0OS8xNzc2LmpwZw==.jpg"> <br><br>政党1最大的两只奶牛的距离是3（也就是奶牛3和奶牛6的距离）。政党2最大的两只奶牛的距离是2（也就是奶牛2和4，4和5，还有5和2之间的距离）。<br>帮助奶牛们求出每个政党的范围。<br></p> 

 
 # 输入格式 
<p>
* 第一行: 两个由空格隔开的整数: N 和 K<br><br>* 第2到第N+1行: 第i+1行包含两个由空格隔开的整数: A_i和P_i<br><br></p> 

 
 # 输出格式 
<p>
* 第1到第K行: 第i行包含一个单独的整数，表示第i个政党的范围。<br></p> 
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
<tr><td>6 2
1 3
2 1
1 0
2 1
2 1
1 5

</td><td>3
2</td></tr></table>
