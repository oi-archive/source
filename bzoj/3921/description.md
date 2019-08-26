
# Description

<div class="content"><div>Mimori知道了，只有毁灭掉神树，才能保护Yuuna和大家。但是，想要到神树那里需要穿越树海，树海非常危险，需要携带一定量的精灵才能通过。</div>
<div>她把树海抽象为一张有n个点和m条边的无向连通图，无重边和自环，结点编号为1~n，结点之间有双向道路连接。</div>
<div>每个结点有一个精灵需求数，u结点的精灵需求数记作w[u]。</div>
<div>通过这些边要支付一定数量的精灵！费用规定如下：</div>
<div>①若是普通道路(记作类别0)，她需要支付1只精灵。</div>
<div>②若是特殊道路(记作类别1)，她需要支付自己当前携带的精灵数的1/20，若不满20只则按20只计算。(例如、若她身上此时有10只精灵，则需要支付1只；若有69只精灵，则需要支付4只。)</div>
<div>她定义了一个整数S，令S等于每对结点之间的最优路径长度之和。我们用d(u,v)表示u,v之间的最优路径长度，d(u,v)被定义为从u沿路径到达v，且身上至少还有w[v]只精灵的前提下，初始携带的的最少精灵数(注意!仅仅在边上要支付精灵,在结点处不支付,但是你需要满足终点的精灵需求数)。(例如、结点数等于3时，S=d(1,1)+d(1,2)+d(1,3)+d(2,1)+d(2,2)+d(2,3)+d(3,1)+d(3,2)+d(3,3))</div>
<div>那么问题来了，她想删除一条边后使得新的S值S’最大。当然，你必须保证删除后图仍然连通才行。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包括2个整数n，m，分别表示图的顶点数和边数。</div>
<div>第二行包括n个整数w1...wn，表示n个结点的精灵需求数。</div>
<div>接下来m行，每行包括三个整数u，v，op，代表一条连接u、v的无向边，其类别为op(参见题目描述)。</div>
<div>保证图连通，且无重边和自环。</div>
<p></p></div>

# Output

<div class="content"><div>仅包含一行，包括2个整数，为S和最大的S’。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 6<br/>
15 14 10 14 12<br/>
1 2 0<br/>
2 3 0<br/>
3 4 1<br/>
2 5 1<br/>
3 5 1<br/>
3 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">353 357</span></div>

# Hint

<div class="content"><p></p><div>1&lt;=n&lt;=110，</div><br/>
<div>1&lt;=m&lt;=1100，</div><br/>
<div>1&lt;=u&lt;=n，</div><br/>
<div>1&lt;=v&lt;=n，u≠v，</div><br/>
<div>0&lt;=op&lt;=1，</div><br/>
<div>1&lt;=wi&lt;=100(1&lt;=i&lt;=n)，</div><br/>
<div>保证图连通，且无重边和自环。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

