
# Description

<div class="content"><div>比特铁路系统需要重新布置。通过对铁路网络深入的分析，有一些站点需要被移除，有一些道路也需要被移除。</div>
<div>整个铁路网络可以看做一张由n个点，m条道路组成的无向图。从每一个点出发都可以通过直接或间接的道路到达其它所有点。两个站点之间最多只有一条道路。每一条道路都有一个正整数费用。你的任务是决定哪些点和道路需要被保留。</div>
<div>要求：</div>
<div>1.从每一个没被移除的点出发都能通过直接或间接的没被移除的道路到达其他所有没被移除的点。</div>
<div>2.剩下的道路的费用总和要比较小，即不能超过最优解的两倍。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(2&lt;=n&lt;=5000,1&lt;=m&lt;=500000)，表示点数和边数。</div>
<div>接下来m行，每行包含三个正整数a,b,u(1&lt;=a,b&lt;=n,a!=b,1&lt;=u&lt;=100000)，表示a和b之间有一条费用为u的道路。</div>
<div>最后一行的开头为一个正整数p(2&lt;=p&lt;=n,p*m&lt;=15000000)，表示必须要保留的点数。</div>
<div>接下来包含p个正整数，按递增顺序依次给出必须保留的点的编号。</div>
<p></p></div>

# Output

<div class="content"><div>第一行包含两个正整数c,k，其中c表示剩余道路的费用总和，k表示剩余道路的条数。</div>
<div>接下来k行，每行包含两个正整数a,b，表示一条道路的两个端点。</div>
<div>如有多组解，输出任意一组。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 11<br/>
1 2 6<br/>
3 1 5<br/>
2 3 8<br/>
3 4 9<br/>
3 5 10<br/>
5 4 3<br/>
5 6 9<br/>
6 4 8<br/>
6 8 8<br/>
6 7 7<br/>
8 7 10<br/>
4 2 5 7 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">42 5<br/>
2 3<br/>
3 5<br/>
5 6<br/>
6 7<br/>
6 8</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/4158/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNy9waWMucG5n.png" width="365" height="213" alt=""/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

