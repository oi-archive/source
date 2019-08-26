
# Description

<div class="content"><div>这里有 N 座城镇, 和城镇之间的 M 巴士单行线(没有中间停靠站)。 城镇从1到N 标号。 一个旅行者在 0时刻位于 1号城镇想要到达 P 号城镇。他将乘坐巴士在T 时刻到达P 号城镇。如果他早到了，他必须等待。</div>
<div></div>
<div>对于任意一个巴士路线i, 我们知道其中的起点城镇si 和目标城镇ti 。我们也同样知道路线的出发时间和到达时间,但仅仅是近似值：我们知道巴士离开起点城镇si 在时间范围[ai, bi]内，且到达目标城镇ti 在时间范围[ci, di]内(端点值包括在内)。</div>
<div></div>
<div>旅行者不喜欢等待, 因此他要寻找一个旅行计划使得最大等待时间尽量小，同时保证绝对不会错过计划中的任何一辆巴士(意思是, 每次他换乘巴士, 他需要下车的巴士的最晚到达时间不会迟于他需要搭乘的下一辆巴士的最早出发时间)。</div>
<div></div>
<div>当计算等待时间时，我们必须假设最早可能到达的时间和最晚可能出发的时间。</div>
<div></div>
<div>编写一个程序，寻找一个最为合理的搭车计划。</div></div>

# Input

<div class="content"><div style="font-size: 11.8181819915771px;">The input file name is TRIP.IN. The first line contains the integer numbers N (1&lt;=N&lt;=50,000), M (1&lt;=M&lt;=100,000), P ( 1&lt;=P&lt;=N), and T (0&lt;=T&lt;=1,000,000,000).</div>
<div style="font-size: 11.8181819915771px;"></div>
<div style="font-size: 11.8181819915771px;">The following M lines describe the bus routes. Each line contains the integer numbers si, ti, ai, bi, ci, di, where si and ti are the source and destination towns of the bus route i, and ai, bi, ci, di describe the departure and arrival times as explained above (1&lt;=si&lt;=N, 1&lt;=ti&lt;=N, 0&lt;=ai&lt;=bi &lt; ci&lt;=di&lt;=1,000,000,000).</div></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">只需要包含一个数——最合理搭车方案的最长可能等待时间。如果不可能保证在T 时刻到达城市P，那么输出-1。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 6 2 100<br/>
1 3 10 20 30 40<br/>
3 2 32 35 95 95<br/>
1 1 1 1 7 8<br/>
1 3 8 8 9 9<br/>
2 2 98 98 99 99<br/>
1 2 0 0 99 101<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">32</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

