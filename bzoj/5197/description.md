
# Description

<div class="content"><div>给定一张n个点，m条双向边的无向图。</div>
<div>你要从1号点走到n号点。当你位于x点时，你需要花1元钱，等概率随机地买到与x相邻的一个点的票，只有通过票才能走到其它点。</div>
<div>每当完成一次交易时，你可以选择直接使用那张票，也可以选择扔掉那张票然后再花1元钱随机买另一张票。注意你可以无限次扔票。</div>
<div>请使用最佳的策略，使得期望花的钱数最少。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(1&lt;=n,m&lt;=300000)，表示点数和边数。</div>
<div>接下来m行，每行两个正整数u,v(1&lt;=u,v&lt;=n)，表示一条双向边。</div>
<div>输入数据保证无重边、无自环，且1号点一定可以走到n号点。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个实数，即最少的期望花费，当绝对或者相对误差不超过10^{-6}时视为正确。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 8<br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 3<br/>
2 4<br/>
3 5<br/>
5 4<br/>
2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.1111111111</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

