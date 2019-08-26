
# Description

<div class="content"><div>给出一个无根树。树有N个点，边有权值。每个点都有颜色，是黑色、白色、灰色这三种颜色之一，称为一棵三色</div>
<div>树。可爱的Alice觉得，一个三色树为均衡的，当且仅当，树中不含有黑色结点或者含有至多一个白色节点。然而</div>
<div>，给出的三色树可能并不满足这个性质。所以，Alice打算删去若干条边使得形成的森林中每棵树都是均衡的，花</div>
<div>费的代价等于删去的边的权值之和。请你计算需要花费的代价最小是多少。注意，输入文件包含多组测试数据。</div></div>

# Input

<div class="content"><div>
<div>第一行包含一个正整数T，表示有T组测试数据。</div>
<div>接下来依次是T组测试数据。</div>
<div>每组测试数据的第一行包含一个正整数N。</div>
<div>第二行包含N个0、1、2之一的整数，依次表示点1到点N的颜色。</div>
<div>其中，0表示黑色，1表示白色，2表示灰色。</div>
<div>接下来N-1行，每行为三个整数ui、vi、ci，表示一条权值等于ci的边(ui,vi)。</div>
<div>1≤N≤300000，1≤T≤5，0≤ci&lt;=10^9</div>
</div></div>

# Output

<div class="content"><p>输出 T行，每行一个整数，依次表示每组测试数据的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 <br/>
5 <br/>
0  1 1 1 0<br/>
1  2 5<br/>
1  3 3<br/>
5  2 5<br/>
2  4 16<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10 <br/>
//花费 10的代价删去边(1, 2)和边(2, 5)</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

