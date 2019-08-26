
# Description

<div class="content"><div>给你一棵 n 个点的无根树。树上的每条边具有颜色。 一共有 m 种颜色，编号为 1 到 m。第 i 种颜色的权值为 </div>
<div>ci。对于一条树上的简单路径，路径上经过的所有边按顺序组成一个颜色序列，序列可以划分成若干个相同颜色段</div>
<div>。 定义路径权值为颜色序列上每个同颜色段的颜色权值之和。请你计算，经过边数在 l 到 r 之间的所有简单路</div>
<div>径中， 路径权值的最大值。</div>
<div></div></div>

# Input

<div class="content"><div>第一行， 四个整数 n, m, l, r。</div>
<div>第二行， n 个整数 c1, c2, ……, cm，由空格隔开。依次表示每个颜色的权值。</div>
<div>接下来 n-1 行，每行三个整数 u, v, c，表示点 u 和点 v 之间有一条颜色为 c 的边。</div>
<div>n = 2*105</div>
<div>m&lt;=n</div>
<div></div></div>

# Output

<div class="content"><div>输出一行， 一个整数， 表示答案。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 1 4<br/>
-1 -5 -2<br/>
1 2 1<br/>
1 3 1<br/>
2 4 2<br/>
2 5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">-1<br/>
【样例解释 】<br/>
颜色权值均为负，最优路径为 (1, 2) 或 (1, 3)。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

