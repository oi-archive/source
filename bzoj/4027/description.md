
# Description

<div class="content"><p>很久很久之前，森林里住着一群兔子。有一天，兔子们突然决定要去看樱花。兔子们所在森林里的樱花树很特殊。樱花树由n个树枝分叉点组成，编号从0到n-1，这n个分叉点由n-1个树枝连接，我们可以把它看成一个有根树结构，其中0号节点是根节点。这个树的每个节点上都会有一些樱花，其中第i个节点有c_i朵樱花。樱花树的每一个节点都有最大的载重m，对于每一个节点i，它的儿子节点的个数和i节点上樱花个数之和不能超过m，即son(i) + c_i &lt;= m，其中son(i)表示i的儿子的个数，如果i为叶子节点，则son(i) = 0</p>
<div>现在兔子们觉得樱花树上节点太多，希望去掉一些节点。当一个节点被去掉之后，这个节点上的樱花和它的儿子节点都被连到删掉节点的父节点上。如果父节点也被删除，那么就会继续向上连接，直到第一个没有被删除的节点为止。</div>
<div>现在兔子们希望计算在不违背最大载重的情况下，最多能删除多少节点。</div>
<div>注意根节点不能被删除，被删除的节点不被计入载重。</div></div>

# Input

<div class="content"><p>第一行输入两个正整数，n和m分别表示节点个数和最大载重</p>
<div>
<div>第二行n个整数c_i，表示第i个节点上的樱花个数</div>
<div>接下来n行，每行第一个数k_i表示这个节点的儿子个数，接下来k_i个整数表示这个节点儿子的编号</div>
</div></div>

# Output

<div class="content"><p> 一行一个整数，表示最多能删除多少节点。</p></div>

# Sample Input

<div class="content"><span class="sampledata">10 4<br/>
0 2 2 2 4 1 0 4 1 1<br/>
3 6 2 3<br/>
1 9<br/>
1 8<br/>
1 1<br/>
0<br/>
0<br/>
2 7 4<br/>
0<br/>
1 5<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1 &lt;= n &lt;= 2000000, 1 &lt;= m &lt;= 100000, 0 &lt;= c_i &lt;= 1000</p><br/>
<div>数据保证初始时，每个节点樱花数与儿子节点个数之和大于0且不超过m</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

