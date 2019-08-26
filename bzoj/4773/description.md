
# Description

<div class="content"><div>
<div>在忘记考虑负环之后，黎瑟的算法又出错了。对于边带权的有向图 G = (V, E)，请找出一个点数最小的环，使得</div>
<div>环上的边权和为负数。保证图中不包含重边和自环。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第1两个整数n, m,表示图的点数和边数。</div>
<div>接下来的m行，每&lt;=三个整数ui, vi, wi，表&lt;=有一条从ui到vi，权值为wi的有向边。</div>
<div>2 &lt;= n &lt;= 300</div>
<div>0 &lt;= m &lt;= n(n &lt;= 1)</div>
<div>1 &lt;= ui, vi &lt;= n</div>
<div>|wi| &lt;= 10^4</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>仅一行一个整数，表示点数最小的环上的点数，若图中不存在负环输出0。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 6<br/>
1 2 -2<br/>
2 1 1<br/>
2 3 -10<br/>
3 2 10<br/>
3 1 -10<br/>
1 3 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

