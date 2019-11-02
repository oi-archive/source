# 

 
 # 题目背景 
NOIP2009第三题<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;C&nbsp;国有n&nbsp;个大城市和m&nbsp;条道路，每条道路连接这n&nbsp;个城市中的某两个城市。任意两个<BR>城市之间最多只有一条道路直接相连。这m&nbsp;条道路中有一部分为单向通行的道路，一部分<BR>为双向通行的道路，双向通行的道路在统计条数时也计为1&nbsp;条。<BR>&nbsp;&nbsp;&nbsp;C&nbsp;国幅员辽阔，各地的资源分布情况各不相同，这就导致了同一种商品在不同城市的价<BR>格不一定相同。但是，同一种商品在同一个城市的买入价和卖出价始终是相同的。<BR>&nbsp;&nbsp;&nbsp;商人阿龙来到&nbsp;C&nbsp;国旅游。当他得知同一种商品在不同城市的价格可能会不同这一信息<BR>之后，便决定在旅游的同时，利用商品在不同城市中的差价赚回一点旅费。设C&nbsp;国n&nbsp;个城<BR>市的标号从1~&nbsp;n，阿龙决定从1&nbsp;号城市出发，并最终在n&nbsp;号城市结束自己的旅行。在旅游的过程中，任何城市可以重复经过多次，但不要求经过所有n&nbsp;个城市。阿龙通过这样的贸易方式赚取旅费：他会选择一个经过的城市买入他最喜欢的商品——水晶球，并在之后经过的另一个城市卖出这个水晶球，用赚取的差价当做旅费。由于阿龙主要是来C&nbsp;国旅游，他决定这个贸易只进行最多一次，当然，在赚不到差价的情况下他就无需进行贸易。<BR>&nbsp;&nbsp;&nbsp;假设&nbsp;C&nbsp;国有5&nbsp;个大城市，城市的编号和道路连接情况如下图，单向箭头表示这条道路<BR>为单向通行，双向箭头表示这条道路为双向通行。<BR><img src="/source/joyoi/tyvj-1122/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTEyMi9Qcm9ibGVtSW1nLzExMjIuanBn.jpg" border=0 align=middle><BR><BR>&nbsp;&nbsp;&nbsp;假设&nbsp;1~n&nbsp;号城市的水晶球价格分别为4，3，5，6，1。阿龙可以选择如下一条线路：1-&gt;2-&gt;3-&gt;5，并在2&nbsp;号城市以3&nbsp;的价格买入水晶球，在3号城市以5&nbsp;的价格卖出水晶球，赚取的旅费数为2。<BR>&nbsp;&nbsp;&nbsp;阿龙也可以选择如下一条线路&nbsp;1-&gt;4-&gt;5-&gt;4-&gt;5，并在第1&nbsp;次到达5&nbsp;号城市时以1&nbsp;的价格买入水晶球，在第2&nbsp;次到达4&nbsp;号城市时以6&nbsp;的价格卖出水晶球，赚取的旅费数为5。<BR>&nbsp;&nbsp;&nbsp;现在给出&nbsp;n&nbsp;个城市的水晶球价格，m&nbsp;条道路的信息（每条道路所连接的两个城市的编号以及该条道路的通行情况）。请你告诉阿龙，他最多能赚取多少旅费。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;第一行包含&nbsp;2&nbsp;个正整数n&nbsp;和m，中间用一个空格隔开，分别表示城市的数目和道路的<BR>数目。<BR>&nbsp;&nbsp;&nbsp;第二行&nbsp;n&nbsp;个正整数，每两个整数之间用一个空格隔开，按标号顺序分别表示这n&nbsp;个城<BR>市的商品价格。<BR>&nbsp;&nbsp;&nbsp;接下来&nbsp;m&nbsp;行，每行有3&nbsp;个正整数，x，y，z，每两个整数之间用一个空格隔开。如果z=1，表示这条道路是城市x&nbsp;到城市y&nbsp;之间的单向道路；如果z=2，表示这条道路为城市x&nbsp;和城市y&nbsp;之间的双向道路。<BR> 

 
 # 输出格式 
第一行包含&nbsp;2&nbsp;个正整数n&nbsp;和m，中间用一个空格隔开，分别表示城市的数目和道路的<BR>数目。<BR>第二行&nbsp;n&nbsp;个正整数，每两个整数之间用一个空格隔开，按标号顺序分别表示这n&nbsp;个城<BR>市的商品价格。<BR>接下来&nbsp;m&nbsp;行，每行有3&nbsp;个正整数，x，y，z，每两个整数之间用一个空格隔开。如果z=1，表示这条道路是城市x&nbsp;到城市y&nbsp;之间的单向道路；如果z=2，表示这条道路为城市x&nbsp;和城市y&nbsp;之间的双向道路。 

 
 # 提示 
【数据范围】<BR>输入数据保证&nbsp;1&nbsp;号城市可以到达n&nbsp;号城市。<BR>对于&nbsp;10%的数据，1≤n≤6。<BR>对于&nbsp;30%的数据，1≤n≤100。<BR>对于&nbsp;50%的数据，不存在一条旅游路线，可以从一个城市出发，再回到这个城市。<BR>对于&nbsp;100%的数据，1≤n≤100000，1≤m≤500000，1≤x，y≤n，1≤z≤2，1≤各城市<BR>水晶球价格≤100。 
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
<tr><td>5 5
4 3 5 6 1
1 2 1
1 4 1
2 3 2
3 5 1
4 5 2
</td><td>5
</td></tr></table>
