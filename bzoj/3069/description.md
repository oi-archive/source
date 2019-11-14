
# Description

<div class="content"><p><span style="font-size: medium">Byteasar是一个很纠结的人。每次他经过Bytetown的时候都知道有至少2条不同的路径可以选择，这导致他必须花很长时间来决定走哪条路。Byteasar最近听说了Bytetown的修路计划，他可能是唯一一个为此感到高兴的人——他有机会消除他的烦恼。</span></p>
<p><span style="font-size: medium">在Byteasar一共有n个岔口，连接着m条双向道路。两条路径<strong>完全不同</strong>当且仅当他们没有公共的道路（但是允许经过相同的岔口）。</span></p>
<p><span style="font-size: medium">Byteasar想知道：对于两个岔口<code>x y</code>，是否存在一对完全不同的路径。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行3个整数：<code>n, m, z (2&lt;=n&lt;=100000, 1&lt;=m,z&lt;=100000)</code>，分别代表：n个岔口，m条边，事件数z。岔口编号为1~n。</span></p>
<p><span style="font-size: medium">下面m行：<code>ai, bi (1&lt;=ai,bi&lt;= n, ai!=bi)</code>，描述一条边</span></p>
<p><span style="font-size: medium">然后下面z行描述事件：<code>ti, ci, di (t=&#39;Z&#39; or &#39;P&#39;, 1&lt;=ci,di&lt;=n, ci!=di)</code>。事件按照时间排序。</span></p>
<ul>
    <li><span style="font-size: medium">当<code>t=&#39;Z&#39;</code>，表示删除一条边<code>(ci, di)</code>，保证这条边之前没有被删除。注意，边可以被全部删除！ </span></li>
    <li><span style="font-size: medium">当<code>t=&#39;P&#39;</code>，询问是否存在从ci到di的一对完全不同的路径。 </span></li>
</ul></div>

# Output

<div class="content"><p><span style="font-size: medium">对于每组询问，如果存在，输出<code>TAK</code>，否则输出<code>NIE</code>。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 8 7<br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 3<br/>
3 4<br/>
3 7<br/>
7 4<br/>
5 6<br/>
Z 1 4<br/>
P 1 3<br/>
P 2 4<br/>
Z 1 3<br/>
P 1 3<br/>
Z 6 5<br/>
P 5 6<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
TAK<br/>
NIE<br/>
NIE<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

