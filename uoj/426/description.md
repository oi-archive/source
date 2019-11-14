# 题目描述

<p>复活节岛上有 $n$ 个石像，每个石像的高度是一个 $[1,m]$ 之间的整数。设第 $i$ 个石像的高度为 $a_i$。</p>
<p>实际上，还有很多个像复活节岛一样的岛屿，一共有 $m^n$ 个（包括复活节岛），每个岛上都有 $n$ 个石像。由于某些原因，每个岛屿（包括复活节岛）都是独一无二的，即没有两个岛屿上的石像的高度是完全相同的。</p>
<p>每个岛上都聚集着很多能量，准确来说，有 $(\sigma_0(\gcd(a_1,a_2,\ldots,a_n)^3))^3$ 点能量。其中 $\sigma_0(n)$ 表示 $n$ 的因子个数。</p>
<p>几百年前，黑恶势力登陆地球，诅咒了所有岛屿：一共有 $k$ 个诅咒。第 $i$ 个诅咒可以用两个整数 $x_i,y_i$ 来表示，表示第 $x_i$ 个石像的高度不能超过第 $y_i$ 个石像的高度，即 $a_{x_i}\leq a_{y_i}$。如果一个岛上的石像的高度满足所有诅咒的要求，那么就不会发生任何事，否则整个岛屿就会被毁灭。所有岛上的诅咒都是相同的。</p>
<p>有些岛屿因此消失了，剩下的岛屿上的人把能量汇集在一起，击败了黑恶势力。</p>
<p>作为一名考古学家，你想知道剩下的岛屿的能量值的和是多少。</p>
<p>答案可能会很大，所以你只需要求出答案模 $2^{32}$ 的值。</p>
<p>一句话题意：求 
$$
\left(\sum_{a_1=1}^m\sum_{a_2=1}^m\cdots\sum_{a_n=1}^m{\left(\sigma_0\left(\gcd\left(a_1,a_2,\ldots,a_n\right)^3\right)\right)}^3\prod_{i=1}^k\left[a_{x_i}\leq a_{y_i}\right]\right)\bmod 2^{32}
$$</p>

# 输入格式


<p>第一行有三个整数 $n,m,k$。</p>
<p>接下来 $k$ 行每行有两个整数：第 $i$ 行的两个整数为 $x_i,y_i$。</p>

# 输出格式


<p>一个整数：答案。</p>

# 样例一


<h4>input</h4>
<pre>2 2 1
1 2

</pre>

<h4>output</h4>
<pre>66

</pre>

<h4>explanation</h4>
<p>总共有三种不同的情况：</p>
<ul><li>$a_1=1,a_2=1,s=1,\sigma_0(s^3)^3=1$。</li>
<li>$a_1=1,a_2=2,s=1,\sigma_0(s^3)^3=1$。</li>
<li>$a_1=2,a_2=2,s=2,\sigma_0(s^3)^3=64$。</li>
</ul>
# 样例二


<h4>input</h4>
<pre>5 10 4
1 2
1 3
2 4
2 5

</pre>

<h4>output</h4>
<pre>54283

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th width="200">子任务</th><th>分值</th><th>$n$</th><th>$m$</th><th>$k$</th></tr></thead><tbody><tr><td>$1$</td><td>$5$</td><td>$\leq 5$</td><td>$\leq 10$</td><td rowspan="3">$\leq n(n-1)$</td></tr><tr><td>$2$</td><td>$15$</td><td>$\leq 13$</td><td>$\leq 13$</td></tr><tr><td>$3$</td><td>$30$</td><td rowspan="3">$\leq 20$</td><td>$\leq {10}^7$</td></tr><tr><td>$4$</td><td>$30$</td><td rowspan="2">$\leq {10}^{10}$</td><td>$=0$</td></tr><tr><td>$5$</td><td>$20$</td><td>$\leq n(n-1)$</td></tr></tbody></table></div>

<p>对于所有数据：$1\leq n\leq 20,1\leq m\leq {10}^{10},0\leq k\leq n(n-1)$，不存在两个相同的诅咒。</p>
<p><strong>时间限制</strong>：$\texttt{4s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=426">样例数据下载</a></p>
