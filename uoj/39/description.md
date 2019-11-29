# 题目描述

<p>在一个有障碍点的 $n$ 行 $m$ 列的网格图中，我们用 $(x,y)$ 来表示第 $x$ 行第 $y$ 列的格子。如果该网格图中的回路满足下面两个条件：</p>
<ol><li>不经过任何一个障碍点</li>
<li>回路不自交</li>
</ol><p>则我们称该回路为合法的简单回路。</p>
<p>现在有 $Q$ 个询问，每次询问有多少条合法的简单回路经过了 $(x,y)$ 与 $(x+1,y)$ 之间的边。</p>

# 输入格式


<p>第一行输入三个非负整数 $n$, $m$, $k$，表示 $n$ 行 $m$ 列的网格图中有 $k$ 个障碍点。</p>
<p>接下来 $k$ 行，每行两个正整数$x, y$ $(1 \leq x \leq n,1 \leq y \leq m)$，表示 $(x,y)$ 为一个障碍点（可能重复）</p>
<p>接下来一个整数 $Q$，表示 $Q$ 个询问。</p>
<p>接下来 $Q$ 行，每行两个正整数 $x,y$ $(1 \leq x \leq n-1, 1 \leq y \leq m)$，询问有多少条合法的简单回路经过了格子 $(x,y)$ 与 $(x+1,y)$ 之间的边。</p>

# 输出格式


<p>输出 $Q$ 行，每行对应一组询问。请将答案 $\bmod (1000000000+7)$ 之后输出。</p>

# 样例一


<h4>input</h4>
<pre>4 4 4
2 2
2 4
3 2
4 4
4
1 1
1 4
3 3
2 2

</pre>

<h4>output</h4>
<pre>1
0
1
0

</pre>


# 样例二


<h4>input</h4>
<pre>1000 2 10
426 2
595 2
665 1
447 2
604 2
202 1
26 1
79 1
291 2
6 2
10
932 1
857 2
31 1
458 1
793 1
691 1
438 1
404 1
541 1
872 2

</pre>

<h4>output</h4>
<pre>18156
27456
235
1496
26496
8034
96
2373
4982
26496

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>$k$</th>
<th>$q$</th>
</tr></thead><tbody><tr><td>1</td><td>$100$</td><td>$1$</td><td>$\leq 100$</td><td>$\leq 100$</td></tr><tr><td>2</td><td>$1000$</td><td>$2$</td><td>$\leq 100$</td><td>$\leq 100$</td></tr><tr><td>3</td><td>$1000$</td><td>$2$</td><td>$\leq 100$</td><td>$\leq 100$</td></tr><tr><td>4</td><td>$1000$</td><td>$3$</td><td>$\leq 100$</td><td>$\leq 100$</td></tr><tr><td>5</td><td>$1000$</td><td>$5$</td><td>$\leq 100$</td><td>$\leq 100$</td></tr><tr><td>6</td><td>$1000$</td><td>$6$</td><td>$\leq 100$</td><td>$\leq 100$</td></tr><tr><td>7</td><td>$1000$</td><td>$6$</td><td>$\leq 100$</td><td>$\leq 10000$</td></tr><tr><td>8</td><td>$1000$</td><td>$6$</td><td>$\leq 100$</td><td>$\leq 10000$</td></tr><tr><td>9</td><td>$1000$</td><td>$6$</td><td>$\leq 100$</td><td>$\leq 10000$</td></tr><tr><td>10</td><td>$1000$</td><td>$6$</td><td>$\leq 100$</td><td>$\leq 10000$</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 来源


<p>中国国家队清华集训2014~2015 Day 2 - By 彭天翼</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=39">样例数据下载</a></p>
