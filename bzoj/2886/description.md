
# Description

<div class="content"><div><span style="font-size: medium">       小Y最近学得了最短路算法，一直想找个机会好好练习一下。话虽这么说，OJ上最短路的题目都被他刷光了。正巧他的好朋友小A正在研究一类奇怪的图，他也想凑上去求下它的最短路。</span></div>
<div><span style="font-size: medium">       小A研究的图可以这么看：在一个二维平面上有任意点(x,y)（0&lt;=x&lt;=N,0&lt;=y&lt;=M,且x,y均为整数），且(x,y)向(x-1,y)（必须满足1&lt;=x）和(x,y-1)（必须满足1&lt;=y）连一条边权为0的双向边。</span></div>
<div><span style="font-size: medium">       每个点都有一个非负点权，不妨设(x,y)的权值为F[x][y]，则有：</span></div>
<div><span style="font-size: medium">       1.x=0或y=0：F[x][y]=1；2.其他情况：F[x][y]=F[x-1][y]+F[x][y-1]。</span></div>
<div><span style="font-size: medium">       现在，小Y想知道(0,0)到(N,M)的最短路，即使得经过的点的权值之和最小。为了炫耀自己学过最短路算法，他决定和你进行一场比赛，看谁的程序跑得快。然则小Y没有学过高精度算法，所以他希望输出答案时只输出答案模1000000007后的值。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">       一行两个正整数N,M，表示图的大小。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">       一行一个整数Ans，表示答案模1000000007后的值。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: 15pt">【数据范围】</span></div><br/>
<div>10%的数据满足N,M&lt;=20；</div><br/>
<div>30%的数据满足N,M&lt;=100；</div><br/>
<div>60%的数据满足min(N,M)&lt;=100；</div><br/>
<div>100%的数据满足N*M&lt;=10^12。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

