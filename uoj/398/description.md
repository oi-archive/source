# 题目描述

<p>久莲是一个喜欢出题的女孩子。</p>
<p>在今年的 World Final 结束以后，久莲特别喜欢计算几何，于是她打算在 NOI 的考场上也出一个计算几何：这是一道只有题目名字和计算几何相关的题目。</p>
<p>首先，久莲给出了一棵 $n(n \ge 2)$ 个节点的有根树 T，根节点编号为 $1$。定义叶子节点为除了根以外所有度数恰好为 $1$ 的节点。下图是一个树 T 的例子，其中叶子节点集合为 $\{3, 4, 5\}$。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/398/398a.png" style="width:200px;" alt="例子"/></p>
<p>接着通过这棵树，久莲构造了一个序列 $A$：</p>
<ul><li>从根节点开始深度优先遍历整棵树，遍历时按照编号从小到大的顺序来访问孩子，这样可以得到一个树 $T$ 的 DFS 序。</li>
<li>接着按照在 DFS 序中的出现顺序从前往后，久莲把所有叶子节点排成一排得到了一个序列 $A$。</li>
</ul><p>更进一步地，通过序列 A，久莲定义了两个叶子节点 $u, v$ 的距离 $d(u, v)$：假设 $u$ 在 $A$ 中是第 $i$ 个元素，$v$ 是第 $j$ 个元素，则 $d(u, v) = \min(\lvert i − j \rvert, \lvert A \rvert − \lvert i − j\rvert)$。其中 $\lvert A \rvert$ 为序列的长度，即 $T$ 的叶子个数，$i, j$ 指的是出现的位置，从 $1$ 开始计数。</p>
<p>上面的例子中，序列 $A$ 为 $[4, 5, 3]$，其中 $d(3, 5) = d(3, 4) = d(4, 5) = 1$，$3, 4, 5$ 的出现位置分别为 $3, 1, 2$。</p>
<p>最后，久莲给出了一个参数 $K$，利用这棵有根树 $T$ 和序列 $A$，我们可以构造一张 $n$ 个点的<strong><em>无重边无自环</em></strong>的无向图 $G$：两个不同的点 $u, v$ 之间有边当且仅当它们满足下列条件中的至少一个：</p>
<ul><li>在树 $T$ 中存在连接 $u, v$ 的边。</li>
<li>在树 $T$ 中 $u, v$ 都是叶子节点且 $d(u, v) \le K$。</li>
</ul><p>当 $K = 1$ 或 $2$ 时，上面的例子得到的图 $G$ 都如下图所示：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/398/398b.png" style="width:200px;" alt="例子"/></p>
<p>现在久莲想让你来计算一下 $G$ 中不同的哈密尔顿回路数量有多少条，答案可能很大，请对 $998244353$ 取模后输出。</p>
<p>下面是一些补充定义：</p>
<ul><li>无重边无自环的无向图 $G$ 的一条哈密尔顿回路 $H$ 是 $G$ 中边的一个子集，其中每一个点恰好有两条不同的相邻边在 $H$ 中，且任意两个点都可以通过 $H$ 中的边直接或间接到达。</li>
<li>无重边无自环的无向图 $G$ 的两条哈密尔顿回路 $H_1, H_2$ 是不同的当且仅当存在一条边 $e$ 使得 $e$ 在 $H_1$ 中且不在 $H_2$ 中。</li>
<li>DFS 序是从 $1$ 号点开始对整棵树进行深度优先遍历时被访问节点按照从先到后的顺序形成的序列。</li>
</ul>
# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行输入两个整数 $n, K$，表示树 $T$ 的点数以及久莲选定的参数 $K$。</p>
<p>第二行输入 $n − 1$ 个整数 $f_i(1 \le f_i \le i)$，其中 $f_i$ 表示树 $T$ 上存在边 $(f_i, i + 1)$。</p>

# 输出格式


<p>输出到标准输出中。</p>
<p>输出一行一个整数，表示哈密尔顿回路数量对 $998244353$ 取模后的结果。</p>

# 样例一


<h4>input</h4>
<pre>5 1
1 1 2 2

</pre>

<h4>output</h4>
<pre>2

</pre>

<h4>explanation</h4>
<p>该样例和题面中的例子完全相同。两条哈密尔顿回路经过节点的顺序分别为 $(1, 2, 4, 5, 3)$ 和 $(1, 2, 5, 4, 3)$。</p>

# 样例二


<p>见下载文件中的 <code>ex_polygon2.in</code> 与 <code>ex_polygon2.ans</code>.</p>

# 样例三


<p>见下载文件中的 <code>ex_polygon3.in</code> 与 <code>ex_polygon3.ans</code>.</p>

# 样例四


<p>见下载文件中的 <code>ex_polygon4.in</code> 与 <code>ex_polygon4.ans</code>.</p>

# 限制与约定


<p>各测试点的数据规模和性质如下表：</p>
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>编号</th><th>$n$</th><th>$K$</th><th>特殊性质</th><th> </th><th>编号</th><th>$n$</th><th>$K$</th><th>特殊性质</th></tr></thead><tbody><tr><td>$1$</td><td>$\le 5$</td><td>$\le 3$</td><td>无</td><td></td><td>$11$</td><td>$\le 1000$</td><td>$\le 2$</td><td>A</td></tr><tr><td>$2$</td><td>$\le 10$</td><td>$\le 3$</td><td>无</td><td></td><td>$12$</td><td>$\le 1000$</td><td>$\le 2$</td><td>A</td></tr><tr><td>$3$</td><td>$\le 15$</td><td>$\le 3$</td><td>无</td><td></td><td>$13$</td><td>$\le 1000$</td><td>$\le 2$</td><td>A</td></tr><tr><td>$4$</td><td>$\le 20$</td><td>$\le 3$</td><td>无</td><td></td><td>$14$</td><td>$\le 1000$</td><td>$\le 2$</td><td>无</td></tr><tr><td>$5$</td><td>$\le 1000$</td><td>$=1$</td><td>A</td><td></td><td>$15$</td><td>$\le 1000$</td><td>$\le 2$</td><td>无</td></tr><tr><td>$6$</td><td>$\le 1000$</td><td>$=1$</td><td>A</td><td></td><td>$16$</td><td>$\le 1000$</td><td>$\le 2$</td><td>无</td></tr><tr><td>$7$</td><td>$\le 1000$</td><td>$=1$</td><td>A</td><td></td><td>$17$</td><td>$\le 1000$</td><td>$\le 3$</td><td>A</td></tr><tr><td>$8$</td><td>$\le 1000$</td><td>$=1$</td><td>无</td><td></td><td>$18$</td><td>$\le 1000$</td><td>$\le 3$</td><td>A</td></tr><tr><td>$9$</td><td>$\le 1000$</td><td>$=1$</td><td>无</td><td></td><td>$19$</td><td>$\le 1000$</td><td>$\le 3$</td><td>无</td></tr><tr><td>$10$</td><td>$\le 1000$</td><td>$=1$</td><td>无</td><td></td><td>$20$</td><td>$\le 1000$</td><td>$\le 3$</td><td>无</td></tr></tbody></table><p>其中性质 A 为保证树上所有节点至多有两个孩子。</p>
<p><strong>时间限制</strong>：$10\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=398">样例数据下载</a></p>
