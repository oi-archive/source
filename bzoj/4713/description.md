
# Description

<div class="content"><div>有一棵n个节点的大树，上面每条边有一个小写字符。</div>
<div>对于任意两个不同的点u,v，我们可以在树上找到u出发到v终止的唯一的一条最短路径，并将沿途经过的边上的字符依次写下来，得到一个字符串。</div>
<div>对于一个字符串，如果存在这样一个点对(u,v)，使得它们路径上的字符串与其完全匹配，那么我们就称这个字符串属于这棵树。</div>
<div>现在有m个迷失的字符串，请你写一个程序帮助判断每一条字符串是否属于这棵树。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数n(2&lt;=n&lt;=30000)，表示树的点数。</div>
<div>接下来n-1行每行包含两个正整数a,b和一个小写字符c(1&lt;=a,b&lt;=n,a!=b)，表示a点到b点之间有一条无向的树边，上面写着字符c。</div>
<div>接下来一行包含一个正整数m(1&lt;=m&lt;=30000)，表示迷失的字符串的个数。</div>
<div>接下来m行，每行一个由小写字符组成的字符串，分别表示每个迷失的字符串。</div>
<div>输入数据保证所有迷之的字符串的长度之和不超过30000。</div>
<p></p></div>

# Output

<div class="content"><div>包含m行，对于第i行，如果在树上可以找到第i个字符串，输出YES，否则输出NO。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2 b<br/>
1 4 a<br/>
2 3 c<br/>
9<br/>
bc<br/>
cb<br/>
b<br/>
c<br/>
d<br/>
aa<br/>
ab<br/>
abc<br/>
cba</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
YES<br/>
YES<br/>
YES<br/>
NO<br/>
NO<br/>
YES<br/>
YES<br/>
YES</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Claris">By Claris</a></p></div>

