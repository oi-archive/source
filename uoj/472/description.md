# 题目描述

<p>有一个 $n\times m\times l$ 的立方体，立方体中每个格子上都有一个数，如果某个格子上的数比三维坐标<strong>至少有一维</strong>相同的其他格子上的数都要大的话，我们就称它是极大的。  </p>
<p>现在将 $1\sim n\times m\times l$ 这 $n\times m\times l$ 个数等概率随机填入 $n\times m\times l$ 个格子（即任意数字出现在任意格子上的概率均相等），使得每个数恰出现一次，求恰有 $k$ 个极大的数的概率。答案对 $998244353$（一个质数）取模。</p>

# 输入格式


<p>输入包含多组数据。输入第一行包含一个正整数 $T$，表示数据组数。  </p>
<p>接下来 $T$ 行，每行一组数据，包含 $4$ 个正整数 $n,m,l,k$，表示一次询问。 </p>

# 输出格式


<p>对于每次询问，输出一行一个整数，表示答案对 $998244353$ 取模的余数。  </p>
<p>可以证明，答案一定为有理数。设其为 $a/b$（$a$ 和 $b$ 为互质的正整数，数据保证 $b$ 不为 $998244353$ 的倍数），则你需要保证输出的数 $x$ 满足 $0\le x &lt; 998244353$ 且 $a\equiv bx \pmod{998244353}$。可以证明这样的 $x$ 唯一存在。</p>

# 样例一


<h4>input</h4>
<pre><code>5
1 1 1 1
2 2 2 1
7 8 9 3
123 456 789 1
1000 1000 1000 10</code></pre>
<h4>output</h4>
<pre><code>1
142606337
736950806
246172965
189652652</code></pre>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>对于 $100\%$ 的数据，$1\le n,m,l\le 5000000$，$1\le k\le 100$，$1\le T\le 10$。</p>
<p>其中有 $50\%$ 的数据保证 $k=1$。</p>
<p>每个测试点的具体限制见下表：</p>
 <div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th><th>$n$</th><th>$m$</th><th>$l$</th><th>$k$</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$\le 2$</td><td>$\le 2$</td><td>$\le 3$</td><td>$=1$</td><td>$10$</td></tr><tr><td>$2$</td><td>$\le 12$</td><td>$\le 12$</td><td>$\le 12$</td><td>$\le 12$</td><td>$20$</td></tr><tr><td>$3$</td><td>$\le 100$</td><td>$\le 100$</td><td>$\le 100$</td><td>无</td><td>$10$</td></tr><tr><td>$4$</td><td>$\le 1000$</td><td>$\le 1000$</td><td>$\le 1000$</td><td>其中有占全部数据 $30\%$ 的数据保证 $k=1$</td><td>$10$</td></tr><tr><td>$5$</td><td>$\le 100000$</td><td>$\le 100000$</td><td>$\le 100000$</td><td>其中有占全部数据 $40\%$ 的数据保证 $k=1$</td><td>$10$</td></tr><tr><td>$6$</td><td>$\le 1000000$</td><td>$\le 1000000$</td><td>$\le 1000000$</td><td>其中有占全部数据 $40\%$ 的数据保证 $k=1$</td><td>$20$</td></tr></tbody></table></div>

<p><strong>时间限制: <del>5s</del> 12s</strong></p>
<p><strong>空间限制: 512MB</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=472">样例数据下载</a></p>
