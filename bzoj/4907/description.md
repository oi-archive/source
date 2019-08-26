
# Description

<div class="content"><div>你有n个点，你可以在这n个点之间连无向边，两个点之间至多只能连一条边，也不允许连自环，问至多能连多少条</div>
<div>边。但这个问题的答案显然是n(n-1)/2条。所以有一个额外的限制，要求这个图不存在非平凡的自同构。一个图G</div>
<div>有非平凡的自同构定义为存在一个1,2,...,n的置换p(1), p(2),...,p(n)满足对于所有点u, v，(u, v)之间有边当</div>
<div>且仅当(p(u), p(v))之间有边，并且这个置换非平凡也就是存在一个点u使得p(u) ≠ u。比如对于一个5个点的图(</div>
<div>1,2),(2,3),(3,4),(4,5),(5,1),(1,3)，那么p(1)=3, p(2)=2, p(3)=1, p(4)=5, p(5)=4为这个图的一个非平凡的</div>
<div>自同构。你要回答一个n个点的无向简单的不存在非平凡自同构的图最多有多少条边，如果答案不存在，即不存在n</div>
<div>个点满足条件的图，请输出 &#34;-1&#34; (不包含引号)，否则输出答案对10^9+7的余数。</div></div>

# Input

<div class="content"><div>第一行一个正整数T表示数据组数。接下来T行，每行一个正整数n表示你要回答的图的点的个数。</div>
<div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif;">本题只有一个点n=10^100</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">其余测试点n&lt;=10^18</span></div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>共T行，每行输出 &#34;-1&#34; 或者答案对10^9+7的余数。</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5<br/>
6</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
-1<br/>
-1<br/>
-1<br/>
-1<br/>
9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

