
# Description

<div class="content"><div>Siruseri 城中的道路都是单向的。不同的道路由路口连接。按照法律的规定， 在每个路口都设立了一个 Siruser</div>
<div>i 银行的 ATM 取款机。令人奇怪的是，Siruseri 的酒吧也都设在路口，虽然并不是每个路口都设有酒吧。Bandit</div>
<div>ji 计划实施 Siruseri 有史以来最惊天动地的 ATM 抢劫。他将从市中心 出发，沿着单向道路行驶，抢劫所有他</div>
<div>途径的 ATM 机，最终他将在一个酒吧庆 祝他的胜利。使用高超的黑客技术，他获知了每个 ATM 机中可以掠取的</div>
<div>现金数额。他希 望你帮助他计算从市中心出发最后到达某个酒吧时最多能抢劫的现金总数。他可 以经过同一路口</div>
<div>或道路任意多次。但只要他抢劫过某个 ATM 机后，该 ATM 机 里面就不会再有钱了。 例如，假设该城中有 6 个</div>
<div>路口，道路的连接情况如下图所示：</div>
<div><img src="/source/bzoj/1179/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8xMS5wbmc=.png" width="332" height="135" alt=""/></div>
<div>市中心在路口 1，由一个入口符号→来标识，那些有酒吧的路口用双圈来表示。每个 ATM 机中可取的钱数标在了</div>
<div>路口的上方。在这个例子中，Banditji 能抢 劫的现金总数为 47，实施的抢劫路线是：1-2-4-1-2-3-5。</div></div>

# Input

<div class="content"><div>第一行包含两个整数N、M。N表示路口的个数，M表示道路条数。</div>
<div>接下来M行，每行两个整数，这两个整数都在1到N之间，</div>
<div>第i+1行的两个整数表示第i条道路的起点和终点的路口编号。</div>
<div>接下来N行，每行一个整数，按顺序表示每个路口处的ATM机中的钱数。</div>
<div>接下来一行包含两个整数S、P，S表示市中心的编号，也就是出发的路口。P表示酒吧数目。</div>
<div>接下来的一行中有P个整数，表示P个有酒吧的路口的编号</div>
<div>N, M&lt;=500000。每个ATM机中可取的钱数为一个非负整数且不超过4000。</div>
<div>输入数据保证你可以从市中心沿着Siruseri的单向的道路到达其中的至少一个酒吧。</div></div>

# Output

<div class="content"><p>输出一个整数，表示Banditji从市中心开始到某个酒吧结束所能抢劫的最多的现金总数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 7<br/>
1 2<br/>
2 3<br/>
3 5<br/>
2 4<br/>
4 1<br/>
2 6<br/>
6 5<br/>
10<br/>
12<br/>
8<br/>
16<br/>
1 5<br/>
1 4<br/>
4<br/>
3<br/>
5<br/>
6</span></div>

# Sample Output

<div class="content"><span class="sampledata">47</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

