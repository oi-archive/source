
# Description

<div class="content"><div>给定一个n个点，m条边的强连通有向图。请保留其中恰好2n条边，使得它还是强连通的。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数T，表示测试数据的组数。</div>
<div>每组数据第一行包含两个正整数n,m(n&gt;=4,m&gt;2n)，表示点数和边数。</div>
<div>接下来m行，每行两个正整数x,y(1&lt;=x,y&lt;=n,x!=y)，表示一条x到y的单向边。</div>
<div>数据保证图强连通，且不存在重边，sum(n),sum(m)&lt;=100000。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，输出m-2n行</div>
<div>每行描述一条要被删除的边，和输入格式一样，有多解输出任意一组。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
4 9<br/>
1 2<br/>
1 3<br/>
2 3<br/>
2 4<br/>
3 2<br/>
3 4<br/>
4 1<br/>
4 2<br/>
4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供翻译及SPJ">鸣谢Claris提供翻译及SPJ</a></p></div>

