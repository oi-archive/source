# 题目描述

<p>九条可怜是一个热爱出题的女孩子。</p>
<p>今天可怜想要出一道和图论相关的题。在一张无向图 $G$ 上，我们可以对它进行一些非常有趣的变换，比如说对偶，又或者说取补。这样的操作往往可以赋予一些传统的问题新的活力。例如求补图的连通性、补图的最短路等等，都是非常有趣的问题。
最近可怜知道了一种新的变换:求原图的线图 (line graph)。对于无向图 $G = ⟨V, E⟩$，它的线图 $L(G)$ 也是一个无向图:</p>
<ul><li>它的点集大小为 $E$，每个点唯一对应着原图的一条边。</li>
<li>两个点之间有边当且仅当这两个点对应的边在原图上有公共点(注意不会有自环)。</li>
</ul><p>下图是一个简单的例子，左图是原图，右图是它对应的线图。其中点 $1$ 对应原图的边 $(1, 2)$， 点 $2$ 对应 $(1,4)$，点 $3$ 对应 $(1,3)$，点 $4$ 对应 $(3,4)$。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/373/xiantu.webp" alt="线图"/></p>
<p>经过一些初步的摸索，可怜发现线图的性质要比补图复杂很多，其中突出的一点就是补图的补图会变回原图，而 $L(L(G))$ 在绝大部分情况下不等于 $G$，甚至在大多数情况下它的点数和边数会以很快的速度增长。</p>
<p>因此，可怜想要从最简单的入手，即计算 $L^k(G)$ 的点数($L^k(G)$ 表示对 $G$ 求 $k$ 次线图)。 </p>
<p>然而遗憾的是，即使是这个问题，对可怜来说还是太困难了，因此她进行了一定的弱化。她给出了一棵 $n$ 个节点的树 $T$ ，现在她想让你计算一下 $L^k (T )$ 的点数。</p>

# 输入格式


<p>第一行输入两个整数 $n$, $k$，表示树的点数以及连续求线图的次数。 </p>
<p>接下来 $n − 1$ 行每行两个整数 $u, v$ 表示树上的一条边。</p>

# 输出格式


<p>输出一行一个整数，表示答案对 $998244353$取模后的值。</p>

# 样例一


<h4>input</h4>
<pre>5 3
1 2
2 3
2 5
3 4

</pre>

<h4>output</h4>
<pre>5

</pre>

<h4>explanation</h4>
<p>如下图所示，左图为原树，中图为 $L(G)$，右图为 $L^2(G)$。这儿并未画出 $L^3(G)$，但是由于
$L^2(G)$ 有 $5$ 条边，因此 $L^3(G)$ 中有 $5$ 个点。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/373/xiantu2.png" alt="线图"/></p>

# 样例二


<p>见样例数据下载</p>

# 数据范围与约定


<p>$2\le n\le 5000$。</p>
<div class="table-responsive">
 <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点</th>
    <th>$k$</th>
   </tr></thead><tbody><tr><td>1</td>
    <td>$=2$</td>
   </tr><tr><td>2</td>
    <td>$=3$</td>
   </tr><tr><td>3</td>
    <td>$=4$</td>
   </tr><tr><td>4</td>
    <td>$=5$</td>
   </tr><tr><td>5</td>
    <td>$=5$</td>
   </tr><tr><td>6</td>
    <td>$=6$</td>
   </tr><tr><td>7</td>
    <td>$=7$</td>
   </tr><tr><td>8</td>
    <td>$=8$</td>
   </tr><tr><td>9</td>
    <td>$=9$</td>
   </tr><tr><td>10</td>
    <td>$=9$</td>
   </tr></tbody></table></div>



<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=373">样例数据下载</a></p>
