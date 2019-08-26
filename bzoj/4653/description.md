
# Description

<div class="content"><div>在数轴上有 n个闭区间 [l1,r1],[l2,r2],...,[ln,rn]。现在要从中选出 m 个区间，使得这 m个区间共同包含至少一个位置。换句话说，就是使得存在一个 x，使得对于每一个被选中的区间 [li,ri]，都有 li≤x≤ri。</div>
<div></div>
<div>对于一个合法的选取方案，它的花费为被选中的最长区间长度减去被选中的最短区间长度。区间 [li,ri] 的长度定义为 ri−li，即等于它的右端点的值减去左端点的值。</div>
<div></div>
<div>求所有合法方案中最小的花费。如果不存在合法的方案，输出 −1。</div></div>

# Input

<div class="content"><div>第一行包含两个正整数 n,m用空格隔开，意义如上文所述。保证 1≤m≤n</div>
<div></div>
<div>接下来 n行，每行表示一个区间，包含用空格隔开的两个整数 li 和 ri 为该区间的左右端点。</div>
<div>N&lt;=500000,M&lt;=200000,0≤li≤ri≤10^9</div></div>

# Output

<div class="content"><div>只有一行，包含一个正整数，即最小花费。</div></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
3 5<br/>
1 2<br/>
3 4<br/>
2 2<br/>
1 5<br/>
1 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

