
# Description

<div class="content"><div>
<div>在一个n*m的棋盘上要放置若干个守卫。对于n行来说，每行必须恰好放置一个横向守卫；同理对于m列来说，每列</div>
<div>必须恰好放置一个纵向守卫。每个位置放置守卫的代价是不一样的，且每个位置最多只能放置一个守卫，一个守卫</div>
<div>不能同时兼顾行列的防御。请计算控制整个棋盘的最小代价。</div>
<div></div>
</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(2&lt;=n,m&lt;=100000,n*m&lt;=100000)，分别表示棋盘的行数与列数。</div>
<div>接下来n行，每行m个正整数</div>
<div>其中第i行第j列的数w[i][j](1&lt;=w[i][j]&lt;=10^9)表示在第i行第j列放置守卫的代价。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，即占领棋盘的最小代价。</div>
<div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1 3 10 8<br/>
2 1 9 2<br/>
6 7 4 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">19<br/>
<br/>
HINT<br/>
在(1,1),(2,2),(3,1)放置横向守卫，在(2,1),(1,2),(3,3),(2,4)放置纵向守卫。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获得">本OJ付费获得</a></p></div>

