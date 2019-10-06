# 题目描述

<p>猫国的铁路系统中有 $n$ 个站点，从 $1 \sim n$ 编号。小猫准备从 $1$ 号站点出发，乘坐列车回到猫窝所在的 $n$ 号站点。它查询了能够乘坐的列车，这些列车共 $m$ 班，从 $1 \sim m$ 编号。小猫将在 $0$ 时刻到达 $1$ 号站点。对于 $i$ 号列车，它将在时刻 $p_i$ 从站点 $x_i$ 出发，在时刻 $q_i$ 直达站点 $y_i$，小猫只能在时刻 $p_i$ 上 $i$ 号列车，也只能在时刻 $q_i$ 下 $i$ 号列车。</p>
<p>小猫可以通过多次换乘到达 $n$ 号站点。一次换乘是指对于两班列车，假设分别为 $u$ 号与 $v$ 号列车，若 $y_u = x_v$ 并且 $q_u \le p_v$，那么小猫可以乘坐完 $u$ 号列车后在 $y_u$ 号站点等待 $p_v − q_u$ 个时刻，并在时刻 $p_v$ 乘坐 $v$ 号列车。</p>
<p>小猫只想回到猫窝并且减少途中的麻烦，对此它用烦躁值来衡量。</p>
<ul><li>小猫在站点等待时将增加烦躁值，对于一次 $t\ (t \ge 0)$ 个时刻的等待，烦躁值将增加 $At^2 + Bt + C$，其中 $A, B, C$ 是给定的常数。注意：小猫登上第一班列车前，即从 $0$ 时刻起停留在 $1$ 号站点的那些时刻也算作一次等待。</li>
<li>若小猫最终在时刻 $z$ 到达 $n$ 号站点，则烦躁值将再增加 $z$。</li>
</ul><p>形式化地说，若小猫共乘坐了 $k$ 班列车，依次乘坐的列车编号可用序列 $s_1, s_2,\ldots , s_k$ 表示。该方案被称作一条可行的回家路线，当且仅当它满足下列两个条件：</p>
<ol><li>$x_{s_1} = 1 , y_{s_k} = n$；</li>
<li>对于所有 $j\ (1 \le j &lt; k)$，满足 $y_{s_j} = x_{s_{j+1}}$ 且 $q_{s_j} \le p_{s_{j+1}}$。</li>
</ol><p>对于该回家路线，小猫得到的烦躁值将为：</p>
<p>$$
q_{s_k}+(A\cdot p_{s_1}^2+B\cdot p_{s_1}+C)+\sum_{j=1}^{k-1} \left(A(p_{s_{j+1}}-q_{s_j})^2+B(p_{s_{j+1}}-q_{s_j})+C \right)
$$</p>
<p>小猫想让自己的烦躁值尽量小，请你帮它求出所有可行的回家路线中，能得到的最小的烦躁值。题目保证至少存在一条可行的回家路线。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行五个整数 $n, m, A, B, C$，变量意义见题目描述。</p>
<p>接下来 $m$ 行，第 $i$ 行四个整数 $x_i, y_i, p_i, q_i$，分别表示 $i$ 号列车的出发站、到达站、出发时刻与到达时刻。</p>

# 输出格式


<p>输出到标准输出中。</p>
<p>输出仅一行一个整数，表示所求的答案。</p>

# 样例一


<h4>input</h4>
<pre><code>3 4 1 5 10
1 2 3 4
1 2 5 7
1 2 6 8
2 3 9 10</code></pre>
<h4>output</h4>
<pre><code>94</code></pre>
<h4>explanation</h4>
<p>共有三条可行的回家路线：</p>
<ol><li>依次乘坐 $1, 4$ 号列车，得到的烦躁值为：$10 + (1 \times 3^2 + 5 \times 3 + 10) + \left (1 \times (9 − 4)^2 + 5 \times (9 − 4) + 10 \right) = 104$；</li>
<li>依次乘坐 $2, 4$ 号列车，得到的烦躁值为：$10 + (1 \times 5^2 + 5 \times 5 + 10) + \left (1 \times (9 − 7)^2 + 5 \times (9 − 7) + 10 \right ) = 94$；</li>
<li>依次乘坐 $3, 4$ 号列车，得到的烦躁值为：$10 + (1 \times 6^2 + 5 \times 6 + 10) + \left (1 \times (9 − 8)^2 + 5 \times (9 − 8) + 10 \right ) = 102$。</li>
</ol><p>第二条路线得到的烦躁值最小为 $94$。</p>

# 样例二


<h4>input</h4>
<pre><code>4 3 1 2 3
1 2 2 3
2 3 5 7
3 4 7 9</code></pre>
<h4>output</h4>
<pre><code>34</code></pre>

# 样例三至样例五


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有测试点：$2\le n\le 10^5,1\le m\le 2\times 10^5,0 \le A \le 10 , 0 \le B, C \le 10^6,1 \le x_i, y_i \le n , x_i \neq y_i , 0 \le p_i &lt; q_i \le 10^3$。</p>
<p>每个测试点的具体限制见下表：</p>
 <div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m$</th><th>$A,B,C$的特殊限制</th><th>其他特殊条件</th></tr></thead><tbody><tr><td>$1\sim 2$</td><td>$\le 100$</td><td>$=n-1$</td><td>无</td><td>$y_i=x_i+1$</td></tr><tr><td>$3\sim 4$</td><td>$\le 100$</td><td>$\le 100$</td><td>$A=B=C=0$</td><td>$y_i=x_i+1$</td></tr><tr><td>$5\sim 8$</td><td>$\le 2\times 10^3$</td><td>$\le 4\times 10^3$</td><td>$A=B=C=0$</td><td>$x_i&lt;y_i$</td></tr><tr><td>$9$</td><td>$\le 2\times 10^3$</td><td>$\le 4\times 10^3$</td><td>$A=B=0$</td><td>$x_i&lt;y_i$</td></tr><tr><td>$10$</td><td>$\le 2\times 10^3$</td><td>$\le 4\times 10^3$</td><td>$A=0$</td><td>$x_i&lt;y_i$</td></tr><tr><td>$11\sim 14$</td><td>$\le 2\times 10^3$</td><td>$\le 4\times 10^3$</td><td>无</td><td>无</td></tr><tr><td>$15$</td><td>$\le 10^5$</td><td>$\le 2\times 10^5$</td><td>$A=B=0$</td><td>无</td></tr><tr><td>$16\sim 17$</td><td>$\le 10^5$</td><td>$\le 2\times 10^5$</td><td>$A=0$</td><td>无</td></tr><tr><td>$18\sim 20$</td><td>$\le 10^5$</td><td>$\le 2\times 10^5$</td><td>无</td><td>无</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=478">样例数据下载</a></p>
