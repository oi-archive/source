# 题目描述

<p>九条可怜是一个贪玩的女孩子。</p>
<p>这天，她和她的好朋友法海哥哥去玩密室逃脱。在他们面前的是 $n$ 个开关，开始每个开关都是关闭的状态。要通过这关，必须要让开关达到指定的状态。目标状态由一个长度为 $n$ 的 $01$ 数组 $s$ 给出，$s_i = 0$ 表示第 $i$ 个开关在最后需要是关着的，$s_i=1$ 表示第 $i$ 个开关在最后需要被打开。</p>
<p>然而作为闯关者，可怜和法海并不知道 $s$。因此他们决定采用一个比较稳妥的方法：瞎按。他们根据开关的外形、位置，通过一些玄学的方法给每一个开关赋予了一个权值 $p_i(p_i &gt;0)$。每一次，他们会以正比于 $p_i$ 的概率（第 $i$ 个开关被选中的概率是 $\frac{p_i}{\sum_{j=1}^n p_j}$）选择并按下一个开关。开关被按下后，状态会被反转，即开变关，关变开。<strong>注意，每一轮的选择都是完全独立的</strong></p>
<p>在按开关的过程中，一旦当前开关的状态达到了 $s$，那么可怜和法海面前的门就会打开，他们会马上停止按开关的过程并前往下一关。作为一名欧皇，可怜在按了 $\sum_{i=1}^n s_i$ 次后，就打开了大门。为了感受一下自己的运气是多么的好，可怜想要让你帮她计算一下，用这种随机按的方式，期望需要按多少次开关才能通过这一关。</p>

# 输入格式


<p>第一行输入一个整数 $n$，表示开关的数量。</p>
<p>第二行输入 $n$ 个整数 $s_i(s_i \in \{0,1\})$，表示开关的目标状态。第三行同样输入 $n$ 个整数 $p_i$，表示每个开关的权值。</p>

# 输出格式


<p>输出一行一个整数，表示答案对 $998244353$ 取模后的值。即如果答案的最简分数表示为 $\frac{x}{y}(x \geq 0, y \geq 1, \gcd(x,y) = 1)$，你需要输出 $x \times y^{-1} \text{ mod } 998244353$。</p>

# 样例一


<h4>input</h4>
<pre><code>2
1 1
1 1</code></pre>
<h4>output</h4>
<pre><code>4</code></pre>
<h4>explanation</h4>
<p>前两次按开关，有 $\frac{1}{2}$ 的概率达到 $s$，有 $\frac{1}{2}$ 的概率回到原状。因此期望的按开关数量为：</p>
<p>\begin{align*}
\sum_{i=1}^{+\infty} 2i \times \left(\frac{1}{2}\right)^i &amp;= 4
\end{align*}</p>

# 样例二


<h4>input</h4>
<pre><code>8
1 1 0 0 1 1 0 0
1 2 3 4 5 6 7 8</code></pre>
<h4>output</h4>
<pre><code>858924815</code></pre>

# 限制与约定


<p>对于 $100\%$ 的数据，保证 $n \geq 1, \sum_{i=1}^n p_i \leq 5 \times 10^4,p_i \geq 1$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点</th>
    <th>$n$</th>
    <th>其他限制</th>
  </tr></thead><tbody><tr><td>1</td>
    <td rowspan="2">$=2$</td>
    <td rowspan="4">无</td>
  </tr><tr><td>2</td>
  </tr><tr><td>3</td>
    <td rowspan="2">$\leq 8$</td>
  </tr><tr><td>4</td>
  </tr><tr><td>5</td>
    <td rowspan="6">$\leq 100$</td>
    <td>$p_i=1$</td>
  </tr><tr><td>6</td>
    <td rowspan="2">$p_i\leq 2,s_i=1$</td>
  </tr><tr><td>7</td>
  </tr><tr><td>8</td>
    <td rowspan="2">$\sum p_i \leq 2000$</td>
  </tr><tr><td>9</td>
  </tr><tr><td>10</td>
    <td>无</td>
  </tr></tbody></table></div>

<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=469">样例数据下载</a></p>
