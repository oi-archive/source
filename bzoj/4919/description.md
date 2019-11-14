
# Description

<div class="content"><div>给定一棵n个节点的有根树，编号依次为1到n，其中1号点为根节点。每个点有一个权值v_i。</div>
<div>你需要将这棵树转化成一个大根堆。确切地说，你需要选择尽可能多的节点，满足大根堆的性质：对于任意两个点i,j，如果i在树上是j的祖先，那么v_i&gt;v_j。</div>
<div>请计算可选的最多的点数，注意这些点不必形成这棵树的一个连通子树。</div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=200000)，表示节点的个数。</div>
<div>接下来n行，每行两个整数v_i,p_i(0&lt;=v_i&lt;=10^9,1&lt;=p_i&lt;i,p_1=0)，表示每个节点的权值与父亲。</div></div>

# Output

<div class="content"><div>输出一行一个正整数，即最多的点数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
3 0<br/>
1 1<br/>
2 1<br/>
3 1<br/>
4 1<br/>
5 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获得">本OJ付费获得</a></p></div>

