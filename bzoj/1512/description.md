
# Description

<div class="content"><p>Byteotian 大学由一幢主建筑和n个小别墅组成. 它们之间许多单向的道路连接,任意两个建筑之间可能有多条单向路,也有可能一条路从自己出发并回到自己.任意两个建筑之间都是连通的(即要么可以从A走到B,要么可以从B走到A).   现在Byteotian大学想聘请著名的professor Szu. 作为一名出众的教授,他的行为非常的奇特:他希望每天都能走一条不同的路径去大学主建筑,其中一条道路可以走多次,一个建筑也可以经过多次,两条道路只要经过的任意一条道路不同即不同(注意,两条不同的道路连接着两个同样的建筑也是不同的).   在知道了大学中所有道路的分布以后可以帮助我们知道从哪些地方出发可以有最多不同的道路去主建筑,因为知道了这些地方可以使得professor Szu在大学中工作的尽量久.如果有多个这样的地方,把他们都找出来. 如果从某个地方出发有超过36 500 条不同的路径通向主建筑,那么我们认为professor Szu可以在这里永远待下去.</p></div>

# Input

<div class="content"><div>第一行两个整数 n 和 m ( 1&lt;= n, m&lt;= 1 000 000) 表示大学里别墅的个数和道路条数(别墅编号从1到n,大学主建筑的编号为n + 1). 接下来m行每行两个整数 ai, bi ( 1 &lt;=ai, bi&lt;= n + 1 for 1 i m) 表示一条单向路.</div>
<div></div>
<div>注意：</div>
<div>1：所有方案数超过36500的点都是等价的</div>
<div>2：本题可能有自环</div>
<div></div></div>

# Output

<div class="content"><p>第一行输出路径最多条数,如果超过了36500,那么打印&#39;&#39;zawsze&#39;&#39; .第二行一个整数表示一共有多少个别墅可以满足第一行的条件,接下来第三行顺序给出这些别墅的编号.</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
1 2<br/>
1 3<br/>
2 3<br/>
3 4<br/>
3 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
1<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

