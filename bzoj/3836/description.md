
# Description

<div class="content"><div>King Byteasar believes that Byteotia, a land full of beautiful sights, should attract lots of tourists, who should spend lots of money, which should eventually find their way to the royal treasury. But reality does not live up to his dream. So the king instructed his councilor to look into this issue. The councilor found out that foreigners keep away from Byteotia due to its sparse road network.</div>
<div>Let us remark that there are   towns in Byteotia, connected by   two way roads, each road linking two different towns. The roads may lead through picturesque overflies and somewhat less picturesque tunnels. There is no guarantee that every town can be reached from every other town.</div>
<div>The councilor observed that the current road network does not allow for a long journey. Namely, wherever one starts the journey, it is impossible to visit more than 10 towns without passing through some town twice.</div>
<div>Due to limited funds in the treasury, no new roads will be constructed at the time. Instead, Byteasar has decided to build a network of tourist information points (TIPs), staffed by officers who are to advertise the short trips that are available. For each town, there should be a TIP either in this town or one of the towns directly linked by a road. Moreover, the cost of building the TIP is known for each town. Help the king by finding the cheapest way of building TIPs that will satisfy aforementioned condition.</div>
<div><span style="white-space: pre-wrap;">给定一个n个点，m条边的无向图，其中你在第i个点建立旅游站点的费用为C[i]。在这张图中，任意两点间不存在节点数超过10的简单路径。</span></div>
<div>
<pre style="white-space: pre-wrap;">请找到一种费用最小的建立旅游站点的方案，使得每个点要么建立了旅游站点，要么与它有边直接相连的点里至少有一个点建立了旅游站点。<br/></pre>
</div>
<p></p></div>

# Input

<div class="content"><div>The first line of the standard input contains two integers N,M(2&lt;=N&lt;=20 000,0&lt;=m&lt;=25000), separated by a single space, that specify the number of towns and roads in Byteotia respectively. The towns are numbered from   to n. The second line of input contains n integers C1,C2…Cn(0&lt;=Ci&lt;=10000), separated by single spaces; the number Ci specifies the cost of building a TIP in the town no. i.</div>
<div>Then, a description of the Byteotian road network follows. The i-th of the following m lines contains two integers Ai，Bi(1&lt;=Ai&lt;Bi&lt;=N), separated by a single space, that indicate that the towns no. Ai and Bi are linked by a road. There is at most one (direct) road between any pair of towns.</div>
<div><span style="white-space: pre-wrap;">第一行包含两个正整数n,m(1&lt;=n&lt;=20000,0&lt;=m&lt;=25000)，分别表示点数和边数。</span></div>
<div><span style="white-space: pre-wrap;">第二行包含n个整数，其中第i个数为C[i](0&lt;=C[i]&lt;=10000)，表示在第i个点建立旅游站点的费用。</span></div>
<div><span style="white-space: pre-wrap;">接下来m行，每行两个正整数u,v(1&lt;=u,v&lt;=n)，表示u与v之间连了一条边，保证没有重边</span></div>
<p></p></div>

# Output

<div class="content"><div>Your program should print out one integer to the standard output: the total cost of building all the TIPs.</div>
<div>
<pre style="white-space: pre-wrap;">输出一行一个整数，即最小的总费用。		</pre>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6<br/>
3 8 5 6 2 2<br/>
1 2<br/>
2 3<br/>
1 3<br/>
3 4<br/>
4 5<br/>
4 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
</span></div>

# Hint

<div class="content"><p></p><p>Explanation: To attain the minimum, the TIPs should be built in towns no. 1, 5, and 6. (the cost will be  ).</p><br/>
<pre style="white-space: pre-wrap;"><br/>
分别在1，5，6号站点建立旅游站点。<br/>
</pre><br/>
<div></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

