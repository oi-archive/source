
# Description

<div class="content"><p> 不用惊慌，今天的题都不是小强出的。——融入了无数心血的作品，现在却不得不亲手毁掉，难以体会他的心情啊</p>
<div>。——那也是没有办法的事情，能量共振不消除的话……望着已经被装上炸药的水晶，02放下了望远镜，看向了手</div>
<div>中的共振分析报告。还是会有一些水晶，幸存下来的……也许吧。地图由密铺的六边形单元组成，每个单元与其他</div>
<div>六个单元相邻。为了方便起见，我们用坐标(x,y,z)描述一个单元的位置，表示从原点开始按如图所示的x,y,z方向</div>
<div>各走若干步之后到达的地方。有可能有两个坐标描述同一个单元，比如(1,1,1)和(0,0,0)描述的都是原点</div>
<div><img src="/source/bzoj/4625/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNi8xLnBuZw==.png" width="407" height="273" alt=""/></div>
<div>显然(x,y,z)单元和(x+1, y,z)，(x-1,y,z)，(x,y+1,z)，(x,y-1,z)，(x, y, z+1)，(x,y, z-1)相邻。有N块水晶</div>
<div>位于地图的单元内，第i块水晶位于坐标(xi, yi, zi)所表示的单元中，并拥有ci的价值。每个单元内部可能会有</div>
<div>多块水晶。地图中，有一些单元安装有能量源。如下图，任何满足x+y+z是3的整数倍的坐标所描述的单元内都安装</div>
<div>有能量源。</div>
<div><img src="/source/bzoj/4625/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNi8yLnBuZw==.png" width="407" height="298" alt=""/></div>
<div></div>
<div>有能量源的单元中的水晶价值将会额外增加10%.如果三块水晶所在的单元满足特定排列，那么它们将会引发共振。</div>
<div>共振分两种，a共振和b共振。a共振：如果三块水晶所在的单元两两相邻地排成一个三角形，那么会引起a共振。</div>
<div><img src="/source/bzoj/4625/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNi8zLnBuZw==.png" width="356" height="219" alt=""/></div>
<div>图中每一个三角形表示这三个单元各有一块水晶将会发生一个a共振。b共振：如果三块水晶所在的单元依次相邻地</div>
<div>排成一条长度为2的直线段，且正中间的单元恰好有能量源，那么会引起b共振。</div>
<div><img src="/source/bzoj/4625/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNi80LnBuZw==.png" width="409" height="294" alt=""/></div>
<div></div>
<div>图中粉红色线段表示这三个单元各有一块水晶将会发生一个b共振，黑色线段表示即使这三个单元有水晶也不会发</div>
<div>生b共振。现在你要炸掉一部分水晶，使得任何共振都不会发生的前提下，剩余水晶的价值总和最大。</div>
<div></div></div>

# Input

<div class="content"><div>
<div>第一行是一个正整数N，表示水晶数量。</div>
<div>接下来N行，每行四个整数xi，yi，zi，ci，空格分隔，表示一个水晶的位置和价值。</div>
<div>有可能有水晶的位置重合。</div>
<div>N≤50000，1≤ci≤1000，|xi|, |yi|, |zi|≤1000.</div>
</div>
<div></div></div>

# Output

<div class="content"><div>仅一行，一个实数，表示剩余水晶的价值总和。四舍五入保留1位小数。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
0 0 0 11<br/>
1 0 0 5<br/>
0 1 0 7<br/>
0 0 -1 13</span></div>

# Sample Output

<div class="content"><span class="sampledata">25.1<br/>
【样例说明1】<br/>
四块水晶排成一个菱形，没有b共振，有2处a共振，分别是1, 2, 4号水晶和1, 3, 4号水晶形成的三角形。<br/>
因此，为了消除两处a共振，有如下3种方案：<br/>
因此，为了消除两处a共振，有如下3种方案<br/>
1. 炸掉1号水晶，留下2, 3, 4号水晶，总剩余价值5+7+13=25.<br/>
2. 炸掉4号水晶，留下1, 2, 3号水晶，总剩余价值11×(1+10%)+5+7=24.1.<br/>
3. 炸掉2, 3号水晶，留下1, 4号水晶，总剩余价值11×(1+10%)+13=25.1.<br/>
因此我们采用第三种方案，最大总剩余价值为25.1.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

