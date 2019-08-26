
# Description

<div class="content"><p><span style="font-size: medium">John在他的农场中闲逛时发现了许多虫洞。虫洞可以看作一条十分奇特的有向边，并可以使你返回到过去的一个时刻（相对你进入虫洞之前）。John的每个农场有M条小路（无向边)连接着N （从1..N标号）块地，并有W个虫洞。其中1&lt;=N&lt;=500,1&lt;=M&lt;=2500,1&lt;=W&lt;=200。 现在John想借助这些虫洞来回到过去（出发时刻之前），请你告诉他能办到吗。 John将向你提供F(1&lt;=F&lt;=5)个农场的地图。没有小路会耗费你超过10000秒的时间，当然也没有虫洞回帮你回到超过10000秒以前。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: 一个整数 F, 表示农场个数。 </span></p>
<p><span style="font-size: medium">* Line 1 of each farm: 三个整数 N, M, W。</span></p>
<p><span style="font-size: medium"> * Lines 2..M+1 of each farm: 三个数（S, E, T）。表示在标号为S的地与标号为E的地中间有一条用时T秒的小路。</span></p>
<p><span style="font-size: medium"> * Lines M+2..M+W+1 of each farm: 三个数（S, E, T）。表示在标号为S的地与标号为E的地中间有一条可以使John到达T秒前的虫洞。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Lines 1..F: 如果John能在这个农场实现他的目标，输出&#34;YES&#34;,否则输出&#34;NO&#34;。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 3 1<br/>
1 2 2<br/>
1 3 4<br/>
2 3 1<br/>
3 1 3<br/>
3 2 1<br/>
1 2 3<br/>
2 3 4<br/>
3 1 8<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">NO<br/>
YES<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

