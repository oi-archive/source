# 题目描述

<p>很久很久以前，有一棵树加入了 UOJ 群。</p>
<p>这天，在它讨论“一棵树应该怎么旋转”的时候一不小心被删除了，变成了被删除的树。</p>
<p>突然间，它突然发现它失去了颜色，变成了一棵纯白的树。这让它感觉很焦躁，于是它来拜托你给自己染上一些颜色。</p>
<p>我们可以把它描述为一棵 $n$ 个节点的有根树（默认树的根为 $1$ 号节点），所有非根的度数为 $1$ 的节点被称为叶子节点。最开始所有的节点都是白色的。</p>
<p>现在你需要选出一些节点并把这些节点染成黑色的。为了迎合树的审美，你的染色方案必须要满足所有叶子节点到根路径上的黑色节点个数相同。</p>
<p>你发现黑色节点个数越多，树就会越高兴，所以你想要知道在所有合法的染色方案中，黑色节点总个数最多是多少。</p>

# 输入格式


<p>第一行一个正整数 $n$ 表示树的节点个数。</p>
<p>接下来的 $n-1$ 行，每行是两个整数 $u,v\ (1 \leq u,v \leq n,u \neq v)$ 表示树上的一条边。</p>

# 输出格式


<p>一个整数，表示在所有合法方案中黑色节点的最多数量。</p>

# 样例一


<h4>input</h4>
<pre>7
1 2
1 3
2 4
2 5
3 6
3 7

</pre>

<h4>output</h4>
<pre>7

</pre>

<h4>explanation</h4>
<p>所有节点都染黑是一个合法的方案。</p>

# 样例二


<h4>input</h4>
<pre>6
1 2
2 3
1 4
4 5
5 6

</pre>

<h4>output</h4>
<pre>5

</pre>

<h4>explanation</h4>
<p>一个最优的染色方案是把集合 $\{1,2,3,4,5\}$ 染黑。</p>

# 样例三


<p>见样例数据下载</p>

# 限制与约定


<p>由于一些原因，本题使用捆绑测试。每个子任务有若干个测试点，分为 $3$ 个子任务，你只有通过一个子任务的所有测试点才能得到这个子任务的分数。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$n$ 的规模</th>
</tr></thead><tbody><tr><td>1</td><td>30</td><td>$n \leq 20$</td></tr><tr><td>2</td><td>30</td><td>$n \leq 1000$</td></tr><tr><td>3</td><td>40</td><td>$n \leq 100000$</td></tr></tbody></table></div>


<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=139">样例数据下载</a></p>
