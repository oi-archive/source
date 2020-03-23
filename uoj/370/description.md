# 题目描述

<p>“滑稽树上滑稽果，滑稽树下你和我” 听到这熟悉的句子，他猛然忆起年少时最喜欢的节目，彼时单纯而简单的生活，以及那幼稚而天真的苦恼。</p>
<p>幼年的他常常苦恼这么一个问题：</p>
<p>他有 $n$ 个滑稽果，第 $i$ 个滑稽果的大小为 $a_i$。</p>
<p>他现在想把它们构成一棵任意形态的有根树，每个点的<strong>滑稽度</strong>为它的<strong>大小</strong>和它父亲的<strong>滑稽度</strong>的 $\mathrm{and}$，其中 $\mathrm{and}$ 表示按位与运算，例如 $2\ \mathrm{and}\ 3=2，1\ \mathrm{and}\ 0=0，1\ \mathrm{and}\ 1=1$。特别地，根的滑稽度等于他的大小。</p>
<p>为了世界的和平，他希望能最小化这棵树上所有滑稽果的滑稽度之和。请问你能帮他解决这个问题吗？</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/370/huajiguo.jpeg" alt="滑稽树上滑稽果"/></p>

# 输入格式


<p>第一行一个正整数 $n$。</p>
<p>接下来一行有 $n$ 个正整数 $a_i$，表示 $i$ 个滑稽果的大小。</p>

# 输出格式


<p>一行一个整数，表示最小的滑稽度之和。</p>

# 样例一


<h4>input</h4>
<pre>5
12 9 14 17 15

</pre>

<h4>output</h4>
<pre>10

</pre>


# 样例二


<h4>input</h4>
<pre>10
42256 116359 103553 58560 49680 99204 37408 57353 110732 33797

</pre>

<h4>output</h4>
<pre>328709

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th width="10%">子任务</th>
<th width="10%">分值</th>
<th width="13%">$n$的规模</th>
<th width="13%">$a_i$的规模</th>
<th>特殊性质</th>
</tr></thead><tbody><tr><td>1</td><td>5</td><td>$n \leq 9$</td><td rowspan="6">$1 \leq a_i \leq 2 \times 10^5$</td><td>无</td></tr><tr><td>2</td><td>10</td><td>$n \leq 12$</td><td>保证存在合法的最优解是一条链</td></tr><tr><td>3</td><td>10</td><td>$n \leq 100$</td><td rowspan="2">保证存在合法的最优解是一条链。并且从根开始的每个滑稽值构成了一个序列，保证解的这个序列的字典序，在所有链对应的序列中最小</td></tr><tr><td>4</td><td>15</td><td>$n \leq 10^5$</td></tr><tr><td>5</td><td>30</td><td>$n \leq 100$</td><td rowspan="2">无</td></tr><tr><td>6</td><td>30</td><td>$n \leq 10^5$</td></tr></tbody></table></div>


<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=370">样例数据下载</a></p>
