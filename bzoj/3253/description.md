
# Description

<div class="content"><div>A:“大图书馆是一张n点m边的无向图，Marisa和Patchouli初始分别位于点X和点Y。每分钟，两人都有一次行动机</div>
<div>会：当某人位于点i时，有pi的概率停留在点i，有1-pi的概率等概率随机选择点i的相邻节点之一并前往。若两人</div>
<div>在某个点相遇，则行动停止。值得注意的是，两人在边上是不会相遇的，所以两人在某条边上迎面经过，只会错过</div>
<div>而不会相遇。两人同时行动，求两人在每个点相遇的概率。”</div>
<div>B：“这不是CodeForces 113 D吗，还原度真高啊喂。”</div>
<div>A：“那改一改……不求在每个点相遇的概率，改成求两人在相遇前走过的路径长度期望和。”</div>
<div>B：“大同小异。”</div>
<div>A：“大图书馆的m条边的长度是可以修改的，两人的初始位置也是。”</div>
<div>B：“你不要让Patchouli太累了……”</div></div>

# Input

<div class="content"><div>第一行三个正整数n、m、t，表示点数、边数和数据组数</div>
<div>以下m行，每行2个整数a,b，表示点a和点b之间有一条无向边</div>
<div>接下来一行n个实数表示pi，保证0.01&lt;=pi&lt;=0.99</div>
<div>以下t行，每行前m个整数表示每条边的长度，最后2个整数表示初始位置点X和点Y</div>
<div>1&lt;=n&lt;=22,t&lt;=500，1&lt;=边权&lt;=1000000<br/>
保证图是无重边和自环的连通图</div>
<p></p></div>

# Output

<div class="content"><div>
<div>共t行，每行一个实数表示两人在相遇前走过的路径长度期望和（保留2位小数）</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 2<br/>
1 2<br/>
2 3<br/>
3 4<br/>
1 4<br/>
0.5 0.5 0.5 0.5<br/>
1 1 1 1 1 2<br/>
2 2 2 2 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.67<br/>
10.67</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

