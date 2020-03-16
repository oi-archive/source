# 题目描述

<p>漆黑的晚上，九条可怜躺在床上辗转反侧。难以入眠的她想起了若干年前她的一次悲惨的 OI 比赛经历。那是一道基础的树状数组题。</p>
<p>给出一个长度为 $n$ 的数组 $A$，初始值都为 $0$，接下来进行 $m$ 次操作，操作有两种：</p>
<ul><li>$1~x$, 表示将 $A_x$ 变成 $(A_x + 1) \bmod{2}$。</li>
<li>$2~l~r$, 表示询问 $(\sum_{i=l}^r A_i) \bmod{2}$。</li>
</ul><p>尽管那个时候的可怜非常的 simple，但是她还是发现这题可以用树状数组做。当时非常 young 的她写了如下的算法：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/291/code.png" alt="Algorithm 1"/></p>
<p>其中 $\mathrm{lowbit}(x)$ 表示数字 $x$ <strong>最低</strong>的非 $0$ 二进制位，例如 $\mathrm{lowbit}(5) = 1, \mathrm{lowbit}(12) = 4$。进行第一类操作的时候就调用 $\mathrm{Add}(x)$，第二类操作的时候答案就是 $\mathrm{Query}(l, r)$。</p>
<p>如果你对树状数组比较熟悉，不难发现可怜把树状数组写错了：<strong>$\mathrm{Add}$ 和 $\mathrm{Find}$ 中 $x$ 变化的方向反了</strong>。因此这个程序在最终测试时华丽的爆 $0$ 了。</p>
<p>然而奇怪的是，在当时，这个程序通过了出题人给出的大样例——这也是可怜没有进行对拍的原因。</p>
<p>现在，可怜想要算一下，这个程序回答对每一个询问的概率是多少，这样她就可以再次的感受到自己是一个多么非的人了。然而时间已经过去了很多年，即使是可怜也没有办法完全回忆起当时的大样例。幸运的是，她回忆起了大部分内容，唯一遗忘的是每一次第一类操作的 $x$ 的值，因此她假定这次操作的 $x$ 是在 $[l_i, r_i]$ 范围内<strong>等概率随机</strong>的。</p>
<p>具体来说，可怜给出了一个长度为 $n$ 的数组 $A$，初始为 $0$，接下来进行了 $m$ 次操作：</p>
<ul><li>$1~l~r$, 表示在区间 $[l, r]$ 中等概率选取一个 $x$ 并执行 $\mathrm{Add}(x)$。</li>
<li>$2~l~r$, 表示询问执行 $\mathrm{Query}(l, r)$ 得到的结果是正确的概率是多少。</li>
</ul>
# 输入格式


<p>第一行输入两个整数 $n, m$。
接下来 $m$ 行每行描述一个操作，格式如题目中所示。</p>

# 输出格式


<p>对于每组询问，输出一个整数表示答案。如果答案化为最简分数后形如 $\frac{x}{y}$，那么你只需要输出 $x \times y^{-1} \bmod{998244353}$ 后的值。(即输出答案模 $998244353$)。</p>

# 样例一


<h4>input</h4>
<pre>5 5
1 3 3
2 3 5
2 4 5
1 1 3
2 2 5

</pre>

<h4>output</h4>
<pre>1
0
665496236

</pre>

<h4>explanation</h4>
<p>在进行完 $\mathrm{Add}(3)$ 之后，$A$ 数组变成了 $[0, 1, 1, 0, 0]$。所以前两次询问可怜的程序答案都是 $1$，因此第一次询问可怜一定正确，第二次询问可怜一定错误。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>其他约定</th>
</tr></thead><tbody><tr><td>1</td><td>$\le 5$</td><td>$\le 10$</td><td rowspan="5">无</td></tr><tr><td>2</td><td rowspan="2">$\le 50$</td><td rowspan="2">$\le 50$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="2">$\le 3000$</td><td rowspan="2">$\le 3000$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">$\le 10^5$</td><td rowspan="5">$\le 10^5$</td><td rowspan="2">所有询问都在修改后</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">无</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于 100% 的数据，保证 $1 \le l \le r \le n$。</p>
<p><strong>时间限制：</strong>$4\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=291">样例数据下载</a></p>
