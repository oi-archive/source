
# Description

<div class="content"><div>在Byteland一共有n个城市，编号依次为1到n，它们之间计划修建m条双向道路，其中修建第i条道路的费用为ci。B</div>
<div>yteasar作为Byteland公路建设项目的总工程师，他决定选定一个区间[l,r]，仅使用编号在该区间内的道路。他希</div>
<div>望选择一些道路去修建，使得连通块的个数尽量少，同时，他不喜欢修建多余的道路，因此每个连通块都可以看成</div>
<div>一棵树的结构。为了选出最佳的区间， Byteasar会不断选择 q个区间，请写一个程序，帮助 Byteasar计算每个区</div>
<div>间内修建公路的最小总费用。 </div></div>

# Input

<div class="content"><div>第一行包含三个正整数n; m; q，表示城市数、道路数和询问数。</div>
<div>接下来m 行，每行三个正整数ui; vi; ci，表示一条连接城市ui 和vi 的双向道路，费用为ci。</div>
<div>接下来q 行，每行两个正整数li; ri，表示一个询问。</div>
<div>
<div>1 ≤ ui, vi ≤ n, ui ̸= vi, 1 ≤ li ≤ ri ≤ m, 1 ≤ ci ≤ 10^6</div>
<div>N&lt;=100,M&lt;=100000,Q&lt;=15000</div>
</div>
<div></div></div>

# Output

<div class="content"><div>输出q 行，每行一个整数，即最小总费用。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 5 2<br/>
1 3 2<br/>
2 3 1<br/>
2 1 6<br/>
3 1 7<br/>
2 3 7<br/>
2 5<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
13</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Claris原创，本站版权所有">Claris原创，本站版权所有</a></p></div>

