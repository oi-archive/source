# 题目描述

<p>零点的钟声敲响，猴年终于到来啦~</p>
<p>在这新年的第一天，猴族首领猴腮雷打算重新规划一下猴族领地的交通。</p>
<p>猴族领地中有 $n$ 个城市，其中第 $i$ 座城市的繁荣度为 $a_i$。猴族领地中任意两个城市之间都可以修建双向道路，在第 $i$ 座城市和第 $j$ 座城市之间修建道路可以给新的一年带来 $a_i \mathbin{\mathrm{and}} a_j$ 的繁荣度。其中 $\mathbin{\mathrm{and}}$ 表示按位与运算，例如 $2 \mathbin{\mathrm{and}} 3=2$，$1 \mathbin{\mathrm{and}} 0=0$，$1 \mathbin{\mathrm{and}} 1=1$。</p>
<p>为了彰显自己的功绩，猴族首领猴腮雷决定修建若干条道路，使得<strong>任意两个城市之间都可以只通过他新修建的道路直接或者间接到达</strong>，为了发扬节约精神，<strong>他决定修建恰好 $n-1$ 条道路</strong>。一个修建方案的繁荣度是所有要修建的道路带来的繁荣程度之和。</p>
<p>作为一个英明的首领，猴腮雷决定在所有可行的方案中选择<strong>繁荣度最大</strong>的方案，现在他想要知道他选择的方案的繁荣度，但是因为他日理万机，没有时间来想这种简单的小问题，于是他就让你来帮忙啦。</p>

# 输入格式


<p>第一行两个正整数 $n,m$。</p>
<p>接下来一行 $n$ 个非负整数表示 $a_i$ ，满足 $0 \leq a_i &lt; 2^m$。</p>

# 输出格式


<p>输出所有方案中最大的繁荣度。</p>

# 样例一


<h4>input</h4>
<pre>3 2
1 2 3

</pre>

<h4>output</h4>
<pre>3

</pre>

<h4>explanation</h4>
<p>一个满足条件的方案是在城市 $\langle 1,3 \rangle, \langle 2,3 \rangle$ 之间修建道路。</p>

# 样例二


<h4>input</h4>
<pre>4 3
1 2 4 7

</pre>

<h4>output</h4>
<pre>7

</pre>

<h4>explanation</h4>
<p>一个满足条件的方案是在城市 $\langle 1,4 \rangle, \langle 2,4 \rangle, \langle 3,4 \rangle$ 之间修建道路。</p>

# 样例三


<p>见样例数据下载。</p>

# 样例四


<p>见样例数据下载。</p>

# 限制与约定


<p>由于一些原因，本题使用捆绑测试。每个子任务有若干个测试点，分为 $6$ 个子任务，你只有通过一个子任务的所有测试点才能得到这个子任务的分数。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$n$ 的规模</th>
<th>$m$ 的规模</th>
</tr></thead><tbody><tr><td>1</td><td>$15$</td><td>$n \leq 1000$</td><td rowspan="2">$m \leq 18$</td></tr><tr><td>2</td><td>$15$</td><td>$n \leq 5000$</td></tr><tr><td>3</td><td>$10$</td><td rowspan="4">$n \leq 10^5$</td><td>$m = 1$</td></tr><tr><td>4</td><td>$15$</td><td>$m \leq 12$</td></tr><tr><td>5</td><td>$15$</td><td>$m \leq 15$</td></tr><tr><td>6</td><td>$30$</td><td>$m \leq 18$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=176">样例数据下载</a></p>
