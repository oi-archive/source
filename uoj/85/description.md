# 题目描述

<p>给定一张带权简单无向图，请输出这张图从 $S$ 到 $T$ 的最小割的个数。</p>
<p>从 $S$ 到 $T$ 的割即一个原图中的边的子集，使得去掉这些边后图中不存在从编号为 $S$ 的结点到编号为 $T$ 的结点的路径。一个 $S$ 到 $T$ 的割的权值即这些边的权值之和。从 $S$ 到 $T$ 的最小割即从 $S$ 到 $T$ 的割中权值最小的。</p>
<p>你只用输出答案对 $998244353$ （$7 \times 17 \times 2^{23}+1$，一个质数）取模后的结果。</p>

# 输入格式


<p>该题为提交答案型试题，所有输入数据 mincut1.in ~ mincut10.in 见输入数据下载。</p>
<p>输入文件的第一行包含四个整数 $n,m,S,T$。$n$ 和 $m$ 分别表示这张图的点数和边数。保证 $1 \leq S, T \leq n$。</p>
<p>接下来 $m$ 行，每行三个正整数 $x,y,z$，代表第 $x$ 个点和第 $y$ 个点之间有一条权值为 $z$ 的无向边。</p>

# 输出格式


<p>针对给定的 10 个输入文件 mincut1.in ~ mincut10.in，你需要分别提交你的输出文件 mincut1.out ~ mincut10.out。</p>
<p>输出文件只包含一个正整数，代表这张无向图从 $S$ 到 $T$ 的最小割的个数。</p>

# 样例一


<h4>input</h4>
<pre>4 4 1 4
1 2 1
2 3 1
1 3 1
3 4 2

</pre>

<h4>output</h4>
<pre>3

</pre>

<h4>explanation</h4>
<p>从 $1$ 到 $4$ 的三种最小割如下图所示：</p>
<div class="row">
<div class="col-sm-4">
<img class="img-responsive center-block" src="//img.uoj.ac/problem/85/1.png" alt="1"/></div>
<div class="col-sm-4">
<img class="img-responsive center-block" src="//img.uoj.ac/problem/85/2.png" alt="2"/></div>
<div class="col-sm-4">
<img class="img-responsive center-block" src="//img.uoj.ac/problem/85/3.png" alt="3"/></div>
</div>


# 来源


<p>PoPoQQQ</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=85">输入数据下载</a></p>
