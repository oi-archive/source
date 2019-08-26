
# Description

<div class="content"><div>F说完了上面一题的题目觉得好累啊，他再也不想废话了。</div>
<div>给一张n个点m条边的无向图。求一个至少包含四个点的极小环。</div>
<div>极小环的定义为，一个简单环并且满足环上的不相邻节点没有边相连。</div></div>

# Input

<div class="content"><div>第一行一个整数t，表示数据组数。</div>
<div>每组数据格式如下：</div>
<div>第一行包含三个整数n,m含义如题。</div>
<div>接下来m行，每行两个整数ui,vi，表示图中的一条连接ui,vi的边。顶点从1开始标号。</div>
<div>t ≤ 4, n ≤ 1e3,m ≤ 1e5</div></div>

# Output

<div class="content"><div>每组数据输出一行，如果存在这样的环，那么输出满足题意的任意一个环。否则输出&#39;no&#39;。</div>
<div>环的输出：假设你的环有m个节点，那么你需要按顺序输出m个整数，</div>
<div>s1...sm，表示si与si-1之间有边相连，特别地，s1与sm之间有边相连。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
5 6<br/>
1 2<br/>
1 3<br/>
2 3<br/>
4 3<br/>
5 2<br/>
4 5<br/>
4 5<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 1<br/>
1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 3 4 5<br/>
No</span></div>

# Hint

<div class="content"><p></p><p> 请不要提交！</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=匿名原创，本站版权所有">匿名原创，本站版权所有</a></p></div>

