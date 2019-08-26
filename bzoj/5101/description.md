
# Description

<div class="content"><div>在地面上有一个水箱，它的俯视图被划分成了n行m列个方格，相邻两个方格之间有一堵厚度可以忽略不计的墙，水</div>
<div>箱与外界之间有一堵高度无穷大的墙，因此水不可能漏到外面。已知水箱内每个格子的高度都是[0,H]之间的整数</div>
<div>，请统计有多少可能的水位情况。因为答案可能很大，请对10^9+7取模输出。两个情况不同当且仅当存在至少一个</div>
<div>方格的水位在两个情况中不同。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含三个正整数n,m,H(n*m&lt;=500000,1&lt;=H&lt;=10^9)。</div>
<div>接下来n行，每行m-1个整数a[i][j](1&lt;=a[i][j]&lt;=H)，表示(i,j)和(i,j+1)之间的墙的高度。</div>
<div>接下来n-1行，每行m个整数b[i][j](1&lt;=b[i][j]&lt;=H)，表示(i,j)和(i+1,j)之间的墙的高度。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，即方案数模10^9+7的结果。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 2<br/>
1<br/>
1<br/>
1<br/>
1 2<br/>
1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">65<br/>
HINT<br/>
要么全部格子水位都是2，要么全部格子水位都在[0,1]之间，共1+2^6=65种情况。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传试题">鸣谢Claris上传试题</a></p></div>

