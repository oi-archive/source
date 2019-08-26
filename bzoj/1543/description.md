
# Description

<div class="content">给定一个连通的带边权的图（允许自环和重边），求不同的最小生成树个数。两个生成树不同当它们所用的边的序号不同，换句话说，重边算多次。

</div>

# Input

<div class="content">第一行n,m，表示点数和边数(1&lt;=n&lt;=50000,1&lt;=m&lt;=100000)
下接m行，每行3个数k1,k2,w，表示k1和k2之间有一条权值为w 的边。

</div>

# Output

<div class="content">仅一行一个数：生成树个数 mod 1000003（质数）

</div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
1 2 6<br/>
1 2 6<br/>
2 3 6<br/>
3 1 6<br/>
3 3 8<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
注：不会存在5条及5条以上的边，他们的边权是相同的。<br/>
<br/>
样例解释：<br/>
5棵生成树分别如下（边按输入顺序标号）：<br/>
(1,3)   (2,3)  (1,4)  (2,4)  (3,4) <br/>
5号边是自环。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=HNOI2009集训Day3">HNOI2009集训Day3</a></p></div>

