
# Description

<div class="content"><div>IOI铁路是由N+2个站点构成的直线线路。这条线路的车站从某一端的车站开始顺次标号为0...N+1。</div>
<div>这条路线上行驶的电车分为上行电车和下行电车两种，上行电车沿编号增大方向行驶，下行电车沿编号减小方向行驶。乘坐这两种电车的话，移动1站的距离需要T秒。换句话说，乘坐上行电车从车站i走到车站i+1需要T秒，称作下行电车从车站i走到车站i-1也需要T秒。你不能在0号车站乘坐下行电车，或在N+1号车站乘坐上行电车。由于电车发车的频率非常高，你可以无视等待电车消耗的时间。</div>
<div>每个车站设有上行电车的站台和下行电车的站台，连接两个站台的道路上设有邮戳台。</div>
<div>现在，IOI铁路召开了邮戳拉力赛。在拉力赛中，选手需要从0号车站的上行电车站台出发，在1...N号车站各盖一枚邮戳，最终到达N+1号车站的上行电车站台即可完成。</div>
<div>为了在每个车站盖上邮戳，必须从电车上下来，步行走到车站通路上的邮戳台。在i号车站的上行电车站台、邮戳台、下行电车站台之间移动所消耗的时间如下所示：</div>
<div>从车站i的上行电车站台到邮戳台的时间为Ui秒</div>
<div>从车站i的邮戳台到上行电车站台的时间为Vi秒</div>
<div>从车站i的下行电车站台到邮戳台的时间为Di秒</div>
<div>从车站i的邮戳台到下行电车站台的时间为Ei秒</div>
<div>邮戳拉力赛的选手只能访问0号车站与N+1号车站各一次。1...N号车站都可以访问任意多次。</div>
<div> </div>
<div>现在给出有邮戳台的车站个数、乘坐电车移动一站的时间、在每个车站的上行电车站台、邮戳台、下行电车站台之间移动所消耗的时间，请你求出完成邮戳拉力赛的最短时间。</div>
<div>这个时间包括从0号车站出发，按下N个邮戳后到达N+1号车站的时间。无视等车的时间和按邮戳的时间。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个空格分隔的整数N和T，表示有N+2个车站，电车行驶一站的距离需要T秒</div>
<div>接下来N行，第i行有四个空格分隔的整数Ui,Vi,Di,Ei，分别表示：</div>
<div>从车站i的上行电车站台到邮戳台的时间为Ui秒</div>
<div>从车站i的邮戳台到上行电车站台的时间为Vi秒</div>
<div>从车站i的下行电车站台到邮戳台的时间为Di秒</div>
<div>从车站i的邮戳台到下行电车站台的时间为Ei秒</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，表示完成邮戳拉力赛的最短时间。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1<br/>
1 1 1 1<br/>
1 9 9 1<br/>
9 9 1 1<br/>
1 9 9 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">23</span></div>

# Hint

<div class="content"><p></p><div>从车站0出发，按照2-1-4-3-1-5的顺序访问车站可以达到最短时间。</div><br/>
<div>1&lt;=N&lt;=3000</div><br/>
<div>1&lt;=T&lt;=10^5</div><br/>
<div>1&lt;=Ui&lt;=10^5(1&lt;=i&lt;=N)</div><br/>
<div>1&lt;=Vi&lt;=10^5(1&lt;=i&lt;=N)</div><br/>
<div>1&lt;=Di&lt;=10^5(1&lt;=i&lt;=N)</div><br/>
<div>1&lt;=Ei&lt;=10^5(1&lt;=i&lt;=N)</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI 2013~2014 春季training合宿 竞技2 By PoPoQQQ">JOI 2013~2014 春季training合宿 竞技2 By PoPoQQQ</a></p></div>

