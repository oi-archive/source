# 

 
 # 题目背景 
LHX教主最近总困扰于前来膜拜他的人太多了，所以他给他的花园加上了一道屏障。&nbsp;<BR><BR><BR> 

 
 # 题目描述 
可以把教主的花园附近区域抽像成一个正方形网格组成的网络，每个网格都对应了一个坐标（均为整数，有可能为负），若两个网格(x1,&nbsp;y1)，(x2,&nbsp;y2)有|x1&nbsp;-&nbsp;x2|&nbsp;+&nbsp;|y1&nbsp;-&nbsp;y2|&nbsp;=&nbsp;1，则说这两个网格是相邻的，否则不是相邻的。<BR>教主在y&nbsp;=&nbsp;0处整条直线上的网格设置了一道屏障，即所有坐标为(x,&nbsp;0)的网格。当然，他还要解决他自己与内部人员的进出问题，这样教主设置了N个入口a1,&nbsp;a2,&nbsp;…,&nbsp;aN可供进出，即对于y&nbsp;=&nbsp;0上的所有网格，只有&nbsp;(a1,&nbsp;0)，(a2,&nbsp;0)，&nbsp;……，&nbsp;(aN,&nbsp;0)&nbsp;可以通过，之外的所有纵坐标为0的网格均不能通过，而对于(x,&nbsp;y)有y不为0的网格可以认为是随意通过的。<BR>现在教主想知道，给定M个点对(x1,&nbsp;y1)，(x2,&nbsp;y2)，并且这些点均不在屏障上，询问从一个点走到另一个点最短距离是多少，每次只能从一个格子走到相邻的格子。<BR><BR><BR> 

 
 # 输入格式 
输入的第1行为一个正整数N，为屏障上入口的个数。<BR>第2行有N个整数，a1,&nbsp;a2,&nbsp;…,&nbsp;aN，之间用空格隔开，为这N个入口的横坐标。<BR>第3行为一个正整数M，表示了M个询问。<BR>接下来M行，每行4个整数x1,&nbsp;y1,&nbsp;x2,&nbsp;y2，有y1与y2不等于0，表示了一个询问从(x1,&nbsp;y1)到(x2,&nbsp;y2)的最短路。<BR><BR><BR><BR> 

 
 # 输出格式 
输出共包含m行，第i行对于第i个询问输出从(x1,&nbsp;y1)到(x2,&nbsp;y2)的最短路距离是多少。 

 
 # 提示 
对于20%的数据，有n，m≤10，ai，xi，yi绝对值不超过100；<BR>对于40%的数据，有n，m≤100，ai，xi，yi绝对值不超过1000；<BR>对于60%的数据，有n，m≤1000，ai，xi，yi绝对值不超过100000；<BR>对于100%的数据，有n，m≤100000，ai，xi，yi绝对值不超过100000000。<BR><BR> 
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
<tr><td>2
2 -1
2
0 1 0 -1
1 1 2 2


</td><td>4
2



</td></tr></table>
