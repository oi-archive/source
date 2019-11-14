
# Description

<div class="content">跟所有人一样，农夫约翰以着宁教我负天下牛，休叫天下牛负我的伟大精神，日日夜夜苦思生
财之道。为了发财，他设置了一系列的规章制度，使得任何一只奶牛在农场中的道路行走，都
要向农夫约翰上交过路费。

农场中由N（1 &lt;= N &lt;= 250）片草地（标号为1到N），并且有M（1 &lt;= M &lt;= 10000）条
双向道路连接草地A_j和B_j（1 &lt;= A_j &lt;= N; 1 &lt;= B_j &lt;= N）。奶牛们从任意一片草
地出发可以抵达任意一片的草地。FJ已经在连接A_j和B_j的双向道路上设置一个过路费L_j
（1 &lt;= L_j &lt;= 100,000）。

可能有多条道路连接相同的两片草地，但是不存在一条道路连接一片草地和这片草地本身。最
值得庆幸的是，奶牛从任意一篇草地出发，经过一系列的路径，总是可以抵达其它的任意一片
草地。

除了贪得无厌，叫兽都不知道该说什么好。FJ竟然在每片草地上面也设置了一个过路费C_i
（1 &lt;= C_i &lt;= 100000）。从一片草地到另外一片草地的费用，是经过的所有道路的过路
费之和，加上经过的所有的草地（包括起点和终点）的过路费的最大值。

任劳任怨的牛们希望去调查一下她们应该选择那一条路径。她们要你写一个程序，接受K（1 
&lt;= K &lt;= 10,000）个问题并且输出每个询问对应的最小花费。第i个问题包含两个数字s_i
和t_i（1 &lt;= s_i &lt;= N; 1 &lt;= t_i &lt;= N; s_i != t_i），表示起点和终点的草地。

考虑下面这个包含5片草地的样例图像:
<img border="0" src="/source/bzoj/1774/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE3NzQuanBn.jpg"/>

从草地1到草地3的道路的“边过路费”为3，草地2的“点过路费”为5。

要从草地1走到草地4，可以从草地1走到草地3再走到草地5最后抵达草地4。如果这么走的话，
需要的“边过路费”为2+1+1=4，需要的点过路费为4（草地5的点过路费最大），所以总的花
费为4+4=8。

而从草地2到草地3的最佳路径是从草地2出发，抵达草地5，最后到达草地3。这么走的话，边
过路费为3+1=4，点过路费为5，总花费为4+5=9。


</div>

# Input

<div class="content">* 第1行: 三个空格隔开的整数: N, M和K

* 第2到第N+1行: 第i+1行包含一个单独的整数: C_i

* 第N+2到第N+M+1行: 第j+N+1行包含3个由空格隔开的整数: A_j, B_j和L_j

* 第N+M+2倒第N+M+K+1行: 第i+N+M+1行表示第i个问题，包含两个由空格隔开的整数s_i
	和t_i

</div>

# Output

<div class="content">* 第1到第K行: 第i行包含一个单独的整数，表示从s_i到t_i的最小花费。
</div>

# Sample Input

<div class="content"><span class="sampledata">5 7 2<br/>
2<br/>
5<br/>
3<br/>
3<br/>
4<br/>
1 2 3<br/>
1 3 2<br/>
2 5 3<br/>
5 3 1<br/>
5 4 1<br/>
2 4 3<br/>
3 4 4<br/>
1 4<br/>
2 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
9<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

