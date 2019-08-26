
# Description

<div class="content"><div>
<div>给出一个n个点的有向图，任意两个点之间有且仅一条有向边。</div>
<div>对于每个点v，求出从v出发的一条经过点数最多，且没有重复经过同一个点两次及两次以上的简单路径。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行包含一个正整数n(2&lt;=n&lt;=2000)，表示点数。</div>
<div>接下来n-1行，其中的第i行有i-1个数</div>
<div>如果第j个数是1，那么表示有向边j-&gt;i+1，如果是0，那么表示有向边j&lt;-i+1。</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出n行，第i行首先包含一个正整数k，表示从i点出发的最优路径所经过的点数</div>
<div>接下来k个正整数，依次表示路径上的每个点。</div>
<div>若有多组最优解，输出任意一组。</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1<br/>
1 1<br/>
1 0 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 1 2 3 4<br/>
3 2 3 4<br/>
3 3 4 2<br/>
3 4 2 3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

