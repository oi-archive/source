
# Description

<div class="content"><div>给定d张无向图，每张图都有n个点。一开始，在任何一张图中都没有任何边。接下来有m次操作，每次操作会给出a,b,k，意为在第k张图中的点a和点b之间添加一条无向边。你需要在每次操作之后输出有序数对(a,b)的个数，使得1&lt;=a,b&lt;=n，且a点和b点在d张图中都连通。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含三个正整数d,n,m(1&lt;=d&lt;=200，1&lt;=n&lt;=5000，1&lt;=m&lt;=1000000)，依次表示图的个数，点的个数和操作的个数。</div>
<div>接下来m行，每行包含三个正整数a,b,k(1&lt;=a,b&lt;=n，1&lt;=k&lt;=d)，依次描述每一个操作。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出m行m个正整数，依次表示每次操作之后满足条件的有序数对(a,b)的个数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 10<br/>
1 2 1<br/>
2 1 2<br/>
1 2 3<br/>
3 4 1<br/>
1 3 2<br/>
2 3 3<br/>
2 4 2<br/>
3 4 3<br/>
3 4 2<br/>
1 3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
4<br/>
6<br/>
6<br/>
6<br/>
6<br/>
6<br/>
8<br/>
8<br/>
16<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Claris">By Claris</a></p></div>

