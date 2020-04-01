
# Description

<div class="content"><div>给定一个无向图，某些点之间连有一条可以双向通过的边，假设结点a,b之间有边，则从a到b会得到c[a][b]个糖果，从b到a会得到c[b][a]个糖果。</div>
<div>问在图中是否存在一个环，可以无限获得糖果（即边权和为正）；如果存在，在这些正环中，点数最少的环有多少个点？</div>
<div>对于环的定义：环是一些点的序列，a1,a2,...,ak，a1和a2相连，a2和a3相连,...,ak和a1相连。其中ai和aj可以重合。对于这个环，它的点数视为K。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个整数N，M，分别表示点数和边数。</div>
<div>接下来M行，每行i,j,c[i][j],c[j][i]，表示i号点和j号点有一条边，从i到j获得c[i][j]个糖果，从j到i获得c[j][i]个糖果。</div>
<p></p></div>

# Output

<div class="content"><div>输出只包含一个整数，表示能够无限获得糖果的环中，最少的点数。</div>
<div>如果不存在那样的环，输出0。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2 -10 3<br/>
1 3 1 -10<br/>
2 4 -10 -1<br/>
3 4 0 -3</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据，1&lt;=N&lt;=300,0&lt;=M&lt;=N*(N-1)/2,-10000&lt;=c[i][j]&lt;=10000。<span class="Apple-tab-span" style="white-space:pre">	</span>数据不存在重边和自环。</div><br/>
<div><span style="color: rgb(255, 0, 0);">此题存在版权，故不再支持提交，保留在此只供大家参考题面！ 望见谅！</span></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

