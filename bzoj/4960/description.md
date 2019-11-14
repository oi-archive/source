
# Description

<div class="content"><div>cwbc最近在研究无向图，他想要在一个点数为n、边数为m的无向图中找到一个最大的边独立集，但他觉得这样不够</div>
<div>有趣，于是他给每条边一个边权wi，在保证边独立集边数最多的情况下，要求最大权值与最小权值的差最小，但是</div>
<div>cwbc太弱了，只好请大家来帮忙。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数n、m，n为点数，m为边数。</div>
<div>接下来m行，每行三个正整数xi、yi、wi，表示xi与yi之间有一条边权为wi的无向边。</div>
<div>1&lt;=n&lt;=120, 1&lt;=m&lt;=n*(n-1)/2, 1&lt;=wi&lt;=10^9, 保证不存在重边和自环</div>
<p></p></div>

# Output

<div class="content"><div>第一行一个整数，表示最大边独立集的边数。</div>
<div>第二行一个整数，表示题目要求的最小差值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2 1<br/>
3 4 7<br/>
2 3 2<br/>
1 4 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By cwbc
">By cwbc<br/>
</a></p></div>

