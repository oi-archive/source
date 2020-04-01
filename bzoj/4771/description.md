
# Description

<div class="content"><div>给定一棵n个点的有根树，编号依次为1到n，其中1号点是根节点。每个节点都被染上了某一种颜色，其中第i个节</div>
<div>点的颜色为c[i]。如果c[i]=c[j]，那么我们认为点i和点j拥有相同的颜色。定义depth[i]为i节点与根节点的距离</div>
<div>，为了方便起见，你可以认为树上相邻的两个点之间的距离为1。站在这棵色彩斑斓的树前面，你将面临m个问题。</div>
<div>每个问题包含两个整数x和d，表示询问x子树里且depth不超过depth[x]+d的所有点中出现了多少种本质不同的颜色</div>
<div>。请写一个程序，快速回答这些询问。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数T(1&lt;=T&lt;=500)，表示测试数据的组数。</div>
<div>每组数据中，第一行包含两个正整数n(1&lt;=n&lt;=100000)和m(1&lt;=m&lt;=100000)，表示节点数和询问数。</div>
<div>第二行包含n个正整数，其中第i个数为c[i](1&lt;=c[i]&lt;=n)，分别表示每个节点的颜色。</div>
<div>第三行包含n-1个正整数，其中第i个数为f[i+1](1&lt;=f[i]&lt;i)，表示节点i+1的父亲节点的编号。</div>
<div>接下来m行，每行两个整数x(1&lt;=x&lt;=n)和d(0&lt;=d&lt;n)，依次表示每个询问。</div>
<div>输入数据经过了加密，对于每个询问，如果你读入了x和d，那么真实的x和d分别是x xor last和d xor last，</div>
<div>其中last表示这组数据中上一次询问的答案，如果这是当前数据的第一组询问，那么last=0。</div>
<div>输入数据保证n和m的总和不超过500000。</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问输出一行一个整数，即答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5 8<br/>
1 3 3 2 2<br/>
1 1 3 3<br/>
1 0<br/>
0 0<br/>
3 0<br/>
1 3<br/>
2 1<br/>
2 0<br/>
6 2<br/>
4 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
3<br/>
1<br/>
1<br/>
2<br/>
1<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Claris">By Claris</a></p></div>

