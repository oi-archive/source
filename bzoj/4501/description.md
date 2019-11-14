
# Description

<div class="content"><div>小C来到了F国，小C想好好地参观F国。F国可以看一个有n个点m条边的有向无环图，小C刚开始站在1号点。假设现在小C站在x号点：</div>
<div>1．点x没有出边，结束旅游。</div>
<div>2．点x有o条出边，小C等概率地选一条边走过去。</div>
<div></div>
<div>小J是小C的好朋友，小J可以使用魔法让一些边消失，但是有一些限制(x,y)：第y条边如果被删掉了，那么第x条边也会受到影响，导致x条边被删掉。</div>
<div>现在小J想知道，如何删边使得小C所经过的边数期望最大。</div>
<p></p></div>

# Input

<div class="content"><div>第一行三个整数，n,m,k(1 &lt;= n &lt;= 50, 0 &lt;= m &lt;= 500, 0 &lt;= k &lt;= 2000)，代表有n个点，m条边，k个限制。</div>
<div>接下来m行，第i行代表第i条边x,y(1 &lt;= x, y &lt;= n)，方向是从x到y。</div>
<div>接下来k行，每行有两个整数x,y(1 &lt;= x, y &lt;= m)，代表限制。</div>
<div>保证图是有向无环的，保证对于每个限制(x,y)，第x条边和第y条边的起点是相同的。可能有重边，限制可能重复。</div>
<div>1 &lt;= n &lt;= 50, 0 &lt;= m &lt;= 500, 0 &lt;= k &lt;= 2000</div>
<p></p></div>

# Output

<div class="content"><div>输出一个实数，最大的边数期望。只要和标准答案误差小于10^-2 就认为是相同的。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 0<br/>
1 2<br/>
1 3<br/>
2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2.0000000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢liuchenrui提供SPJ">鸣谢liuchenrui提供SPJ</a></p></div>

