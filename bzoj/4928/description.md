
# Description

<div class="content"><div>对于一棵有根树，定义一个点u的k-子树为u的子树中距离u不超过k的部分。</div>
<div>注意，假如u的子树中不存在距离u为k的点，则u的k-子树是不存在的。</div>
<div>定义两棵子树是相同的，当且仅当不考虑点的标号时，他们的形态是</div>
<div>相同的（儿子的顺序也需要考虑）。给定一棵n个点，点的标号在[1,n]，</div>
<div>以1为根的有根树。问最大的k，使得存在两个点u !=v，满足u的k-子树与v的k-子树相同。</div>
<p></p></div>

# Input

<div class="content"><div>第一行输入一个正整数n。</div>
<div>接下来读入n个部分，第i个部分描述点i的儿子，且以顺序给出。</div>
<div>每个部分首先读入一个整数x，代表儿子个数。</div>
<div>接下来x个整数，代表从左到右儿子的标号</div>
<div>n ≤ 100000，保证给出的树是合法的</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一个整数k，代表最大的合法的k</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 <br/>
1 <br/>
2 <br/>
2<br/>
3 4<br/>
0 <br/>
1 <br/>
5 <br/>
2<br/>
6 7<br/>
0 <br/>
1 <br/>
8 <br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

