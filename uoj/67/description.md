# 题目描述

<p>辞旧迎新之际，喜羊羊正在打理羊村的绿化带，然后他发现了一棵长着毒瘤的树。</p>
<p>这个长着毒瘤的树可以用 $n$ 个结点 $m$ 条无向边的无向图表示。这个图中有一些结点被称作是毒瘤结点，即<strong>删掉这个结点</strong>和与之相邻的边之后，这个图会变为一棵树。树也即无简单环的无向连通图。</p>
<p>现在给你这个无向图，喜羊羊请你帮他求出所有毒瘤结点。</p>

# 输入格式


<p>第一行两个正整数 $n, m$，表示有 $n$ 个点 $m$ 条边。保证 $n \geq 2$。</p>
<p>接下来 $m$ 行，每行两个整数 $v, u$，表示 $v$ 和 $u$ 之间有一条无向边。$1 \leq v, u \leq n$。保证没有重边和自环。</p>

# 输出格式


<p>第一行一个正整数 $n_s$，表示这个图中有 $n_s$ 个结点是毒瘤。</p>
<p>接下来一行，共 $n_s$ 个整数，每个整数表示一个毒瘤结点的编号。<strong>请按编号从小到大的顺序输出。</strong></p>
<p>数据保证图中至少存在一个毒瘤结点。</p>

# 样例一


<h4>input</h4>
<pre>6 6
1 2
1 3
2 4
2 5
4 6
5 6

</pre>

<h4>output</h4>
<pre>3
4 5 6

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n, m$</th>
<th>其它限制</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="4">$n, m \leq 1000$</td><td rowspan="4">无</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="6">$n, m \leq 10^5$</td><td>$m = n - 1$</td></tr><tr><td>6</td><td rowspan="2">$m = n$</td></tr><tr><td>7</td>
</tr><tr><td>8</td><td rowspan="3">无</td>
</tr><tr><td>9</td>
</tr><tr><td>10</td>
</tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 来源


<p>UOJ Goodbye Jiawu</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=67">样例数据下载</a></p>
