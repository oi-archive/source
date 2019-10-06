# 题目描述

<p>题目名称是吸引你点进来的。</p>
<p>从前有个 $n$ 个方格排成一行，从左至右依此编号为 $1, 2, \cdots, n$。</p>
<p>有一天思考熊想给这 $n$ 个方格染上黑白两色。</p>
<p>第 $i$ 个方格上有 $6$ 个属性：$a_i, b_i, w_i, l_i, r_i, p_i$。</p>
<p>如果方格 $i$ 染成黑色就会获得 $b_i$ 的好看度。</p>
<p>如果方格 $i$ 染成白色就会获得 $w_i$ 的好看度。</p>
<p>但是太多了黑色就不好看了。如果方格 $i$ 是黑色，并且存在一个 $j$ 使得 $1 \leq j &lt; i$ 且 $l_i \leq a_j \leq r_i$ 且方格 $j$ 为白色，那么方格 $i$ 就被称为奇怪的方格。</p>
<p>如果方格 $i$ 是奇怪的方格，就会使总好看度减少 $p_i$。</p>
<p>也就是说对于一个染色方案，好看度为：
\begin{equation}
\sum_{\text{方格}i\text{为黑色}}{b_i} + \sum_{\text{方格}i\text{为白色}}{w_i} - \sum_{\text{方格}i\text{为奇怪的方格}}{p_i}
\end{equation}</p>
<p>现在给你 $n, a, b, w, l, r, p$，问所有染色方案中<strong>最大</strong>的好看度是多少。</p>

# 输入格式


<p>第一行一个正整数 $n$。</p>
<p>接下来 $n$ 行中第 $i$ 行有用空格隔开的 $6$ 个非负整数依次表示 $a_i, b_i, w_i, l_i, r_i, p_i$。</p>
<p>保证 $l_i \leq r_i$。</p>

# 输出格式


<p>一个非负整数表示所有染色方案中最大的好看度。</p>

# 样例一


<h4>input</h4>
<pre>10
0 1 7 3 9 2
7 4 0 9 10 5
1 0 4 2 10 2
7 9 1 5 7 2
6 3 5 3 6 2
6 6 4 1 8 1
6 1 6 0 6 5
2 2 5 0 9 3
5 1 3 0 2 5
5 6 7 1 1 2

</pre>

<h4>output</h4>
<pre>55

</pre>

<h4>explanation</h4>
<p>最优染色方案为：白 黑 白 黑 白 黑 白 白 白 白</p>
<p>可以发现只有方格 $6$ 为奇怪的方格。</p>
<p>所以好看度为：
\begin{eqnarray}
&amp;   &amp; w_1 + b_2 + w_3 + b_4 + w_5 + b_6 + w_7 + w_8 + w_9 + w_{10} - p_6 \\
&amp; = &amp; 7 + 4 + 4 + 9 + 5 + 6 + 6 + 5 + 3 + 7 - 1 \\
&amp; = &amp; 55
\end{eqnarray}</p>

# 限制与约定


<p>设 $a_{\max}$ 为 $a, l, r$ 中的最大值，$v_{\max}$ 为 $b, w$ 中的最大值, $p_{\max}$ 为 $p$ 中的最大值。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$a_{\max}$</th>
<th>$v_{\max}$</th>
<th>$p_{\max}$</th>
</tr></thead><tbody><tr><td>1</td><td>$=5$</td><td>$\leq 10$</td><td>$\leq 10$</td><td>$\leq 10$</td></tr><tr><td>2</td><td>$=20$</td><td>$\leq 40$</td><td>$\leq 40$</td><td>$\leq 40$</td></tr><tr><td>3</td><td>$=20$</td><td>$\leq 40$</td><td>$\leq 40$</td><td>$\leq 40$</td></tr><tr><td>4</td><td>$=5000$</td><td>$\leq 10$</td><td>$\leq 200000$</td><td>$\leq 100000$</td></tr><tr><td>5</td><td>$=5000$</td><td>$\leq 10$</td><td>$\leq 200000$</td><td>$\leq 300000$</td></tr><tr><td>6</td><td>$=200$</td><td>$\leq 10^9$</td><td>$\leq 200000$</td><td>$\leq 200000$</td></tr><tr><td>7</td><td>$=300$</td><td>$\leq 10^9$</td><td>$\leq 200000$</td><td>$\leq 220000$</td></tr><tr><td>8</td><td>$=500$</td><td>$\leq 10^9$</td><td>$\leq 200000$</td><td>$\leq 400000$</td></tr><tr><td>9</td><td>$=5000$</td><td>$\leq 5000$</td><td>$\leq 200000$</td><td>$\leq 150000$</td></tr><tr><td>10</td><td>$=5000$</td><td>$\leq 10^9$</td><td>$\leq 200000$</td><td>$\leq 300000$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$48\texttt{MB}$</p>

# 来源


<p>VFleaKing</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=77">样例数据下载</a></p>
