
# Description

<div class="content"><div>小C最近学习了拓扑排序的相关知识。对一个有向无环图G进行拓扑排序，是将G中所有顶点排成一个线性序列，使</div>
<div>得对图G中任意一条有向边(u,v)，u在线性序列中出现在v之前。例如，如果图G的点集为{1,2,3,4}，边集为{(1,2)</div>
<div>,(1,3),(2,4),(3,4)}，那么(1,2,3,4)和(1,3,2,4)都是图G的拓扑序列。现在小C对一个简单（无重边）有向无环</div>
<div>图进行了拓扑排序，但不小心把原图弄丢了。除了拓扑序列，小C只记得原图的边数为k，而且图中存在一个顶点u</div>
<div>可以到达其他所有顶点。他想知道有多少个满足上述要求的简单有向无环图。由于答案可能很大，你只需要输出答</div>
<div>案模m的余数。</div>
<p></p></div>

# Input

<div class="content"><div>输入第一行包含3个整数n、k、m。</div>
<div>第二行是空格隔开的n个正整数a1,a2,…,an，表示原图的一个拓扑序列，保证是1到n的一个排列。</div>
<div>0 ≤ k ≤ n ≤ 200000， 1 ≤ m ≤ 10^200000。</div>
<p></p></div>

# Output

<div class="content"><div>仅输出一个整数， 表示满足要求的简单有向无环图个数模 m 的余数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 4<br/>
1 2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
【样例说明】<br/>
共有 9 个满足要求的简单有向无环图，边集分别为：<br/>
{(1, 2), (1, 3), (1, 4), (2, 3)},<br/>
{(1, 2), (1, 3), (1, 4), (2, 4)},<br/>
{(1, 2), (1, 3), (1, 4), (3, 4)},<br/>
{(1, 2), (1, 3), (2, 3), (2, 4)},<br/>
{(1, 2), (1, 3), (2, 3), (3, 4)},<br/>
{(1, 2), (1, 3), (2, 4), (3, 4)},<br/>
{(1, 2), (1, 4), (2, 3), (2, 4)},<br/>
{(1, 2), (1, 4), (2, 3), (3, 4)},<br/>
{(1, 2), (2, 3), (2, 4), (3, 4)}。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 徐明宽">By 徐明宽</a></p></div>

