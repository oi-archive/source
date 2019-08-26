
# Description

<div class="content"><div>
<div>Zgg是一个吃货。他面前有一堆的食品。不妨把它看成一个序列，序列从1~N编号，第i个位置上有美味度为A[i]的</div>
<div>食品。Zgg有很多只手(为什么他有这么多手？我也不知道)。他的手的作用，就是抓起一段连续序列中的食物，并</div>
<div>且不限长度。总共有M个时刻，在每个时刻，可能会有一些奇怪的人将他面前的某一个位置的食物美味度改变。或</div>
<div>者zgg突然心血来潮，想要用他的其中k只手来抓取某段区间中的食物。这时候，他就需要你告诉他，在用不超过k</div>
<div>只手的情况下，他能获得的最大美味度是多少。</div>
</div></div>

# Input

<div class="content"><div>
<div>第一行一个整数N，表示食品的个数，即序列长度。</div>
<div>第2行有N个数依次表示A[i]。</div>
<div>第三行一个整数M，表示有M个时刻。</div>
<div>接下来的M行，每行有形如0 i val来表示有人将第i位置的食物的美味度改成了val</div>
<div>或者1 l r k，来表示zgg想知道，他只用k只手，在[l,r]这段区间内抓取，能获得的最大美味度。</div>
<div>N,M&lt;=100000 ,1&lt;=k&lt;=20.l&lt;=l&lt;=r&lt;=n.数值的绝对值不会超过500.</div>
<div>Zgg是可以有手空闲的…</div>
</div></div>

# Output

<div class="content"><div>对于每次形如1 l r k的询问你都要输出一个数，表示最大美味度。</div></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
9 -8 9 -1 -1 -1 9 -8 9<br/>
5<br/>
1 1 9 1<br/>
1 1 9 2<br/>
1 4 6 3<br/>
0 3 -8<br/>
1 1 9 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
25<br/>
0<br/>
10</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

