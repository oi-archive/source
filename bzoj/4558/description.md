
# Description

<div class="content"><div>上帝说，不要圆，要方，于是便有了这道题。由于我们应该方，而且最好能够尽量方，所以上帝派我们来找正方形</div>
<div>上帝把我们派到了一个有N行M列的方格图上，图上一共有(N+1)×(M+1)个格点，我们需要做的就是找出这些格点形</div>
<div>成了多少个正方形（换句话说，正方形的四个顶点都是格点）。但是这个问题对于我们来说太难了，因为点数太多</div>
<div>了，所以上帝删掉了这(N+1)×(M+1)中的K个点。既然点变少了，问题也就变简单了，那么这个时候这些格点组成</div>
<div>了多少个正方形呢？</div></div>

# Input

<div class="content"><div>第一行三个整数 N, M, K， 代表棋盘的行数、 列数和不能选取的顶点个数。 保证 N, M &gt;= 1， K &lt;=(N + 1) ×</div>
<div>(M + 1)。约定每行的格点从上到下依次用整数 0 到 N 编号，每列的格点依次用 0到 M 编号。接下来 K 行，每</div>
<div>行两个整数 x,y 代表第 x 行第 y 列的格点被删掉了。保证 0 &lt;=x &lt;=N&lt;=10^6, 0 &lt;=y&lt;=M&lt;=10^6，K&lt;=2*1000且不</div>
<div>会出现重复的格点。</div></div>

# Output

<div class="content"><p> 仅一行一个正整数， 代表正方形个数对 100000007（ 10^8 + 7） 取模之后的值</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 4<br/>
1 0<br/>
1 2<br/>
0 1<br/>
2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

