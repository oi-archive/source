
# Description

<div class="content"><div>J国有N个大城市，城市之间建立了发达的高速路网。在J国，两个城市之间的高速公路都是直线连接的，且没有两条高速公路在端点城市以外的地方相交。另外，J国已经做好了战争规划，使得在任意一个城市或任意一个道路被摧毁的情况下，整个国家的路网依然能够畅通。</div>
<div>K国打算闪电突击J国，他们储备了大量的ICBM（Intercontinental Ballistic Missile，洲际弹道导弹），一枚导弹能够摧毁J国的一个城市。为了让闪击更有战略意义，K国的战争领导层提出了L个方案，每个方案是一个序列(a1,a2,...,an)，保证a1-a2,a2-a3,...,an-1-an,an-a1之间都有高速公路连接，且没有一个城市在序列上重复出现。这个方案的实施方法就是部署ICBM摧毁序列表示的环内所有的城市（包括落在环上的）。</div>
<div>现在战争领导层打算统计每个方案的导弹消耗。这个任务就交给你了。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数N,M，表示J国的城市数量以及高速路数量。</div>
<div>接下来M行，每行两个数x,y，表示x和y之间有一条高速路连接。保证没有重边和自环。</div>
<div>接下来N行，每行两个整数Xi,Yi，表示第I个城市的平面坐标。（坐标绝对值&lt;=10^9）</div>
<div>接下来一行L，表示方案个数。</div>
<div>接下来L行，每行以一个数k（k&gt;=3）开头，接下来k个数a1,a2,a3,...,ak，表示一个方案。</div>
<p></p></div>

# Output

<div class="content"><div>L行，每行一个数，表示对应方案需要的导弹数量。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 8<br/>
5 1<br/>
5 2<br/>
5 3<br/>
5 4<br/>
4 1<br/>
1 2<br/>
3 2<br/>
3 4<br/>
0 0<br/>
2 0<br/>
2 2<br/>
0 2<br/>
1 1<br/>
1<br/>
4 4 3 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=33333，L&lt;=30000，S&lt;=100000</p><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

