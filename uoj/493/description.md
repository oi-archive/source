# 题目描述

<p>小简单正在学习离散数学,今天的内容是图论基础,在课上他做了如下两条笔记:</p>
<ol><li>一个大小为 $n$ 的树由 $n$ 个结点与 $n − 1$ 条无向边构成,且满足任意两个结点间<strong>有且仅有</strong>一条简单路径。在树中删去一个结点及与它关联的边,树将分裂为若干个子树;而在树中删去一条边(保留关联结点,下同),树将分裂为<strong>恰好</strong>两个子树。</li>
<li>对于一个大小为 n 的树与任意一个树中结点 $c$,称 $c$ 是该树的<strong>重心</strong>当且仅当在树中删去 $c$ 及与它关联的边后,分裂出的所有子树的大小均<strong>不超过</strong> $\lfloor \frac{n}{2} \rfloor$(其中 $\lfloor x \rfloor$ 是下取整函数)。对于包含至少一个结点的树,它的重心只可能有 1 或 2 个。</li>
</ol><p>课后老师给出了一个大小为 $n$ 的树 $S$ ,树中结点从 $1 \sim n$ 编号。小简单的课后作业是求出 $S$ 单独删去每条边后,分裂出的两个子树的重心编号和之和。即:</p>
<p>$$ \sum \limits_{(u,v) \in E} \left( \sum \limits_{1 \leq x \leq n ,\atop  且 x 号点是 S_{u}^\prime 的重心}  x  +
                                                     \sum \limits_{1 \leq y \leq n ,\atop  且 y 号点是 S_{v}^\prime 的重心}  y   \right)$$</p>
<p>上式中,$E$ 表示树 $S$ 的边集, $(u, v)$ 表示一条连接 $u$ 号点和 $v$ 号点的边。$S_{u}^\prime$ 与 $S_{u}^\prime$ 分别表示树 $S$ 删去边 $(u, v)$ 后, $u$ 号点与 $v$ 号点所在的被分裂出的子树。</p>
<p>小简单觉得作业并不简单,只好向你求助,请你教教他。</p>

# 输入格式


<p><strong>本题输入包含多组测试数据</strong></p>
<p>第一行一个整数 $T$ 表示数据组数。</p>
<p>接下来依次给出每组输入数据,对于每组数据:</p>
<p>第一行一个整数 $n$ 表示树 $S$ 的大小。</p>
<p>接下来 $n − 1$ 行,每行两个以空格分隔的整数 $u_i , v_i$ ,表示树中的一条边 $u_i,v_i$。</p>

# 输出格式


<p>共 $T$ 行,每行一个整数,第 $i$ 行的整数表示:第 $i$ 组数据给出的树单独删去每条边后,分裂出的两个子树的重心编号和之和。</p>

# 样例1


<h4>input</h4>
<pre><code class="sh_plain">2
5
1 2
2 3
2 4
3 5
7
1 2
1 3
1 4
3 5
3 6
6 7</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">32
56</code></pre>
<h4>explanation</h4>
<p>对于第一组数据:</p>
<p>删去边 $(1, 2)$ , $1$ 号点所在子树重心编号为 {1}, $2$ 号点所在子树重心编号为 ${2, 3}$。</p>
<p>删去边 $(2, 3)$ , $2$ 号点所在子树重心编号为 {2}, $3$ 号点所在子树重心编号为 ${3, 5}$。</p>
<p>删去边 $(2, 4)$ , $3$ 号点所在子树重心编号为 {2, 3}, $4$ 号点所在子树重心编号为 ${4}$。</p>
<p>删去边 $(3, 5)$ , $3$ 号点所在子树重心编号为 {2}, $5$ 号点所在子树重心编号为 ${5}$。</p>
<p>因此答案为 $1 + 2 + 3 + 2 + 3 + 5 + 2 + 3 + 4 + 2 + 5 = 32$。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n = $</th><th>$特殊性质 $</th></tr></thead><tbody><tr><td>$1 \sim 2$</td><td>$7$</td><td rowspan="3"></td></tr><tr><td>$3 \sim 5$</td><td>$199$</td></tr><tr><td>$6 \sim 8$</td><td>$1999$</td></tr><tr><td>$9 \sim 11$</td><td>$49991$</td><td>$A$</td></tr><tr><td>$12 \sim 15$</td><td>$262143$</td><td>$B$</td></tr><tr><td>$16$</td><td>$99995$</td><td rowspan="3"></td></tr><tr><td>$17 \sim 18$</td><td>$199995$</td></tr><tr><td>$19 \sim 20$</td><td>$299995$</td></tr></tbody></table></div>

<p>表中特殊性质一栏,两个变量的含义为存在一个 $1 \sim n$ 的排列 $p_i (1 \leq i \leq n)$ ,使得:</p>
<p>A:树的形态是一条链。即 $\forall 1 \leq i &lt; n$,存在一条边 $(p_{i} , p_{i+1} )$。</p>
<p>B:树的形态是一个完美二叉树。即 $\forall 1 \leq i &lt; \lfloor \frac{n-1}{2} \rfloor$ ,存在两条边$(p_i , p_{2i} )$ 与 $(p_i , p_{2i+1} )$。</p>
<p>对于所有测试点: $1 \leq T \leq 5$ , $1 \leq u_i , v_i \leq n$。保证给出的图是一个树。</p>
<p><strong>时间限制:</strong> $3\texttt{s}$</p>
<p><strong>空间限制:</strong> $256\texttt{MB}$</p>

# 关于本题的Hack数据


<p>由于标准算法实际上并不需要利用到数据范围里给定的关于 $n$ 的限制。因此本题的Hack数据中 $n$ 仅需要满足 $n \in [7,299995]$ 且 $n$ 为整数即可，不需要满足题面中的限制。</p>
<p>其余输入条件仍然同题面。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=493">样例数据下载</a></p>
