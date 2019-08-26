
# Description

<div class="content"><div>给一棵n个结点的树，每个结点有一个正整数权值。要求选出一个结点的集合，满足：</div>
<div>1.这个集合包含1号结点</div>
<div>2.这个集合在树上是一个连通块。</div>
<div>即，设这个集合为S，则树上存在|S|-1条边，这些边连接的结点都属于S。</div>
<div>记一个集合的权值为该集合内所有结点的权值和。</div>
<div>求权值第k小的集合的权值。</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行两个整数n,k。</div>
<div>接下来n-1行，每行两个整数u,v，表示结点u和结点v之间有一条边。</div>
<div>接下来一行n个整数，表示每个结点的权值。</div>
<div>保证存在权值第k小的集合</div>
<div>对于60%的数据，n&lt;=300000,k&lt;=600000</div>
<div>对于另外40%数据，n&lt;=100000,10^6&lt;=k&lt;=10^18,保证答案不超过500</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一个整数，表示答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
1 2<br/>
2 3<br/>
2 4<br/>
4 5<br/>
1 2 3 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">15<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

