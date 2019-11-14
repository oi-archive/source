
# Description

<div class="content"><div>小A有一张n个点的图，点的标号为0到n-1。点i到点j有Ai,j条有向边。可能有自环。现在小A要在图上进行若干次</div>
<div>旅行。每次旅行都是选任意一个起点，走至少一步，走到任意一个终点。定义一次旅行的愉悦值为起点与终点编号</div>
<div>按位与的值。好奇的小B想要知道：对于所有x∈[1,m]和y∈[0,n)，小A进行了若干次旅行，总共走了x步，且所有</div>
<div>旅行的愉悦值的按位与为y的方案数。两种方案不同当且仅当旅行次数不同或某一次旅行不完全相同。为了防止输</div>
<div>出过多，你只需要输出这n×m个数对998244353取模后的结果的按位异或值。为方便起见，保证n是2的幂次。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数n,m。</div>
<div>后面一个n×n的矩阵，第i行第j列的数表示点i-1到点j-1的有向边的数量。</div>
<div>对于所有数据，2≤n≤64,1≤m≤20000,0≤Ai,j&lt;998244353，保证n是2的幂。</div>
<p></p></div>

# Output

<div class="content"><div>输出一个数表示n×m个答案取模后的异或值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
1 2<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1770<br/>
样例解释<br/>
走 1 步，愉悦值的按位与 =0,1 的方案数分别为 6,4。<br/>
走 2 步的方案数分别为 116,38。<br/>
走 3 步的方案数分别为 2012,358。<br/>
异或值为 1770。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=day1">day1</a></p></div>

