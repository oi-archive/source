# 题目描述

<p>小Y家里有一个大森林，里面有 $n$ 棵树，编号从 $1$ 到 $n$ 。一开始这些树都只是树苗，只有一个节点，标号为 $1$ 。这些树都有一个特殊的节点，我们称之为生长节点，这些节点有生长出子节点的能力。 </p>
<p>小Y掌握了一种魔法，能让第 $l$ 棵树到第 $r$ 棵树的生长节点长出一个子节点。同时她还能修改第 $l$ 棵树到第 $r$ 棵树的生长节点。 </p>
<p>她告诉了你她使用魔法的记录，你能不能管理她家的森林，并且回答她的询问呢？ </p>

# 输入格式


<p>第一行包含 2 个正整数 $n,m$，共有 $n$ 棵树和 $m$ 个操作。</p>
<p>接下来 $m$ 行，每行包含若干非负整数表示一个操作，操作格式为： </p>
<ol><li>$0$ $l$ $r$ 表示将第 $l$ 棵树到第 $r$ 棵树的生长节点下面长出一个子节点，子节点的标号为上一个 $0$ 号操作叶子标号加 $1$（例如，第一个 $0$ 号操作产生的子节点标号为 $2$），$l$ 到 $r$ 之间的树长出的节点标号都相同。保证 $1\leq l \leq r \leq n$。 </li>
<li>$1$ $l$ $r$ $x$ 表示将第 $l$ 棵树到第 $r$ 棵树的生长节点改到标号为 $x$ 的节点。对于区间内的每棵树，如果标号 $x$ 的点不在其中，那么这个操作对该树不产生影响。保证 $1 \leq l \leq r \leq n$，$x$ 不超过当前所有树中节点最大的标号。 </li>
<li>$2$ $x$ $u$ $v$ 询问第 $x$ 棵树中节点 $u$ 到节点 $v$ 的距离，也就是在第 $x$ 棵树中从节点 $u$ 和节点 $v$ 的最短路上边的数量。保证 $1 \leq x \leq n$，这棵树中节点 $u$ 和节点 $v$ 存在。</li>
</ol>
# 输出格式


<p>输出包括若干行，按顺序对于每个小Y的询问输出答案。</p>

# 样例一


<h4>input</h4>
<pre>5 5
0 1 5
1 2 4 2
0 1 4
2 1 1 3
2 2 1 3

</pre>

<h4>output</h4>
<pre>1
2

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m$</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td>$\leq 10^3$</td><td>$\leq 10^3$</td><td></td></tr><tr><td>2</td><td rowspan="9">$\leq 10^5$</td><td rowspan="9">$\leq 2 \times 10^5$</td><td rowspan="2">保证每次 $0$ 和 $1$ 操作修改的是 $1$ 到 $n$ 所有的树</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="2">保证每次 $0$ 操作生长节点都是这些树中编号最大的节点</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5"></td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=195">样例数据下载</a></p>
