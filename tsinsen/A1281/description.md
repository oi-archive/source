<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　阿狸和桃子正在玩一个游戏，游戏是在一个带权图G=(V, E)上进行的，设节点权值为w(v)，边权为c(e)。游戏规则是这样的：<br/>
　　1.	阿狸和桃子轮流将图中的顶点染色，阿狸会将顶点染成红色，桃子会将顶点染成粉色。已经被染过色的点不能再染了，而且每一轮都必须给一个且仅一个顶点染色。<br/>
　　2.	为了保证公平性，节点的个数N为偶数。<br/>
　　3.	经过N/2轮游戏之后，两人都得到了一个顶点集合。对于顶点集合S，得分计算方式为<br/>
　　<img width="255" height="59" src="source/tsinsen/A1281/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NmhqWUJoTWg=.do"/>。<br/>
　　由于阿狸石头剪子布输给了桃子，所以桃子先染色。两人都想要使自己的分数比对方多，且多得越多越好。如果两人都是采用最优策略的，求最终桃子的分数减去阿狸的分数。</div>
# 输入格式

<div class="pdcont">　　输入第一行包含两个正整数N和M，分别表示图G的节点数和边数，保证N一定是偶数。<br/>
　　接下来N+M行。<br/>
　　前N行，每行一个整数w，其中第k行为节点k的权值。<br/>
　　后M行，每行三个用空格隔开的整数a b c，表示一条连接节点a和节点b的边，权值为c。</div>
# 输出格式

<div class="pdcont">　　输出仅包含一个整数，为桃子的得分减去阿狸的得分。</div>
# 样例输入

<div class="pddata">4 4<br/>
6<br/>
4<br/>
-1<br/>
-2<br/>
1 2 1<br/>
2 3 6<br/>
3 4 3<br/>
1 4 5</div>
# 样例输出

<div class="pddata">3</div>
# 数据规模和约定

<div class="pdcont">　　对于40%的数据，1 ≤ N ≤ 16。<br/>
　　对于100%的数据，1 ≤ N ≤ 10000，1 ≤ M ≤ 100000，-10000 ≤ w , c ≤ 10000。</div>

</div>