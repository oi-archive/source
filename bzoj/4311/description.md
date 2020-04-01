
# Description

<div class="content"><div>你要维护一个向量集合，支持以下操作：</div>
<div>1.插入一个向量(x,y)</div>
<div>2.删除插入的第i个向量</div>
<div>3.查询当前集合与(x,y)点积的最大值是多少。如果当前是空集输出0</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行输入一个整数n，表示操作个数</div>
<div>接下来n行，每行先是一个整数t表示类型，如果t=1，输入向量</div>
<div>(x,y)；如果t=2，输入id表示删除第id个向量；否则输入(x,y)，查询</div>
<div>与向量(x,y)点积最大值是多少。</div>
<div>保证一个向量只会被删除一次，不会删没有插入过的向量</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每条t=3的询问，输出一个答案</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 3 3<br/>
1 1 4<br/>
3 3 3<br/>
2 1<br/>
3 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">18<br/>
15</span></div>

# Hint

<div class="content"><p></p><div>n&lt;=200000 1&lt;=x,y&lt;=10^6</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

