
# Description

<div class="content"><div style="background: white" align="left"><span style="font-size: 12pt; color: #200000">　　阿狸和桃子正在玩一个游戏，游戏是在一个带权图</span><span style="font-size: 12pt; color: #200000">G=(V, E)</span><span style="font-size: 12pt; color: #200000">上进行的，设节点权值为</span><span style="font-size: 12pt; color: #200000">w(v)</span><span style="font-size: 12pt; color: #200000">，边权为</span><span style="font-size: 12pt; color: #200000">c(e)</span><span style="font-size: 12pt; color: #200000">。游戏规则是这样的：</span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">　　</span><span style="font-size: 12pt; color: #200000">1. </span><span style="font-size: 12pt; color: #200000">阿狸和桃子轮流将图中的顶点染色，阿狸会将顶点染成红色，桃子会将顶点染成粉色。已经被染过色的点不能再染了，而且每一轮都必须给一个且仅一个顶点染色。</span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">　　</span><span style="font-size: 12pt; color: #200000">2. </span><span style="font-size: 12pt; color: #200000">为了保证公平性，节点的个数</span><span style="font-size: 12pt; color: #200000">N</span><span style="font-size: 12pt; color: #200000">为偶数。</span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">　　</span><span style="font-size: 12pt; color: #200000">3. </span><span style="font-size: 12pt; color: #200000">经过</span><span style="font-size: 12pt; color: #200000">N/2</span><span style="font-size: 12pt; color: #200000">轮游戏之后，两人都得到了一个顶点集合。对于顶点集合</span><span style="font-size: 12pt; color: #200000">S</span><span style="font-size: 12pt; color: #200000">，得分计算方式为<img height="71" width="266" alt="" src="/source/bzoj/2563/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMy8xMTEuanBn.jpg"/></span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">　　</span><span style="font-size: 12pt; color: #200000">。</span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">　　由于阿狸石头剪子布输给了桃子，所以桃子先染色。两人都想要使自己的分数比对方多，且多得越多越好。如果两人都是采用最优策略的，求最终桃子的分数减去阿狸的分数。</span></div>
<div style="background: white" align="left"><span style="font-size: 12pt; color: #200000">　</span></div></div>

# Input

<div class="content"><p><font size="3"><font color="#200000">　输入第一行包含两个正整数<span style="font-size: 12pt; color: #200000">N</span></font></font><span style="font-size: 12pt; color: #200000">和</span><span style="font-size: 12pt; color: #200000">M</span><span style="font-size: 12pt; color: #200000">，分别表示图</span><span style="font-size: 12pt; color: #200000">G</span><span style="font-size: 12pt; color: #200000">的节点数和边数，保证</span><span style="font-size: 12pt; color: #200000">N</span><span style="font-size: 12pt; color: #200000">一定是偶数。</span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">　　接下来</span><span style="font-size: 12pt; color: #200000">N+M</span><span style="font-size: 12pt; color: #200000">行。</span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">　　前</span><span style="font-size: 12pt; color: #200000">N</span><span style="font-size: 12pt; color: #200000">行，每行一个整数</span><span style="font-size: 12pt; color: #200000">w</span><span style="font-size: 12pt; color: #200000">，其中第</span><span style="font-size: 12pt; color: #200000">k</span><span style="font-size: 12pt; color: #200000">行为节点</span><span style="font-size: 12pt; color: #200000">k</span><span style="font-size: 12pt; color: #200000">的权值。</span><span style="font-size: 12pt; color: #200000"><br/>
</span><span style="font-size: 12pt; color: #200000">　　后</span><span style="font-size: 12pt; color: #200000">M</span><span style="font-size: 12pt; color: #200000">行，每行三个用空格隔开的整数</span><span style="font-size: 12pt; color: #200000">a b c</span><span style="font-size: 12pt; color: #200000">，表示一条连接节点</span><span style="font-size: 12pt; color: #200000">a</span><span style="font-size: 12pt; color: #200000">和节点</span><span style="font-size: 12pt; color: #200000">b</span><span style="font-size: 12pt; color: #200000">的边，权值为</span><span style="font-size: 12pt; color: #200000">c</span><span style="font-size: 12pt; color: #200000">。</span></p>
<div style="background: white" align="left"><span style="font-size: 12pt; color: #200000">　</span></div></div>

# Output

<div class="content"><p><font color="#200000" size="3">　输出仅包含一个整数，为桃子的得分减去阿狸的得分。</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
6<br/>
4<br/>
-1<br/>
-2<br/>
1 2 1<br/>
2 3 6<br/>
3 4 3<br/>
1 4 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
数据规模和约定<br/>
　　对于40%的数据，1 ≤ N ≤ 16。<br/>
　　对于100%的数据，1 ≤ N ≤ 10000，1 ≤ M ≤ 100000，-10000 ≤ w , c ≤ 10000。<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day2">2012国家集训队Round 1 day2</a></p></div>

