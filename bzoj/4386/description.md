
# Description

<div class="content"><p>给定一张n个点m条边的带权有向图，每条边的边权只可能是1，2，3中的一种。<br/>
将所有可能的路径按路径长度排序，请输出第k小的路径的长度，注意路径不一定是简单路径，即可以重复走同一个点。</p></div>

# Input

<div class="content"><p>第一行包含三个整数n,m,k(1&lt;=n&lt;=40，1&lt;=m&lt;=1000，1&lt;=k&lt;=10^18)。<br/>
接下来m行，每行三个整数u,v,c(1&lt;=u,v&lt;=n，u不等于v，1&lt;=c&lt;=3)，表示从u出发有一条到v的单向边，边长为c。<br/>
可能有重边。</p></div>

# Output

<div class="content"><p>包含一行一个正整数，即第k短的路径的长度，如果不存在，输出-1。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6 11<br/>
1 2 1<br/>
2 3 2<br/>
3 4 2<br/>
4 5 1<br/>
5 3 1<br/>
4 6 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p>长度为1的路径有1-&gt;2，5-&gt;3，4-&gt;5。<br/><br/>
长度为2的路径有2-&gt;3，3-&gt;4，4-&gt;5-&gt;3。<br/><br/>
长度为3的路径有4-&gt;6，1-&gt;2-&gt;3，3-&gt;4-&gt;5，5-&gt;3-&gt;4。<br/><br/>
长度为4的路径有5-&gt;3-&gt;4-&gt;5。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

