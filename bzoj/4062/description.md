
# Description

<div class="content"><p>擅长偷盗的卢平想要偷走邪恶的欧文收藏的珠宝。欧文在他的商店里放置了n个珠宝。每个珍贵的石头一定有着k种颜色之一的颜色。展览馆非常的大，我们可以将珠宝视为欧几里得平面上的一些互异的点。这场展览由一些非常珍贵的报警设备来保护。</p>
<div>卢平发明了一种装置：一个巨大的机械臂，可以用来抢欧文的珠宝而不被任何报警设备发现。这只机械臂可以做一次抢的操作（也仅有一次）可以将在某条水平线段及其下方的所有珠宝拿走（如图）。卢平很容易偷走所有的珠宝，但是他知道，他拿得越多就越难不被发现。他决定选择一种安全的方案，他拿走的珠宝的颜色数不会超过k。</div>
<div> <img src="/source/bzoj/4062/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS9HLmpwZw==.jpg" width="344" height="288" alt=""/></div>
<div>请你计算他在不拿走所有颜色的情况下最多拿多少个珠宝。</div></div>

# Input

<div class="content"><p> 第一行一个正整数T，表示有T组数据。</p>
<div>每组数据第一行两个正整数n和k，表示珠宝数量和颜色数量，2 &lt;= n &lt;= 200000, 2 &lt;= k &lt;= n。</div>
<div>接下来n行，每行三个整数x_j, y_j, c_j，表示第j个珠宝在(x_j, y_j)的位置，颜色为c_j，1 &lt;= x_j, y_j &lt;= 10^9, 1 &lt;= c_j &lt;= k。</div>
<div>你可以认为每种颜色至少有一个珠宝。</div></div>

# Output

<div class="content"><p>对于每组数据输出一行，即最大的可能偷走的珠宝数量。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
10 3<br/>
1 2 3<br/>
2 1 1<br/>
2 4 2<br/>
3 5 3<br/>
4 4 2<br/>
5 1 2<br/>
6 3 1<br/>
6 7 1<br/>
7 2 3<br/>
9 4 2 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tjz">鸣谢Tjz</a></p></div>

