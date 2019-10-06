# 题目描述

<p>给定两个长度为 $n$ 的正整数序列 $\{a_i\}$ 与 $\{b_i\}$，序列的下标为 $1, 2, \ldots , n$。现在你需要分别对两个序列各指定<strong>恰好</strong> $K$ 个下标，要求<strong>至少</strong>有 $L$ 个下标在两个序列中都被指定，使得这 $2K$ 个下标在序列中对应的元素的总和<strong>最大</strong>。</p>
<p>形式化地说，你需要确定两个长度为 $K$ 的序列 $\{c_i\}, \{d_i\}$，其中</p>
<p>$$
1 \le c_1 &lt; c_2 &lt; \ldots &lt; c_K \le n , 1 \le d_1 &lt; d_2 &lt; \ldots &lt; d_K \le n
$$</p>
<p>并要求</p>
<p>$$
\Big| \{c_1, c_2, \ldots , c_K\} \cap \{d_1, d_2, \ldots , d_K\} \Big| \ge L
$$</p>
<p>目标是最大化</p>
<p>$$
\sum_{i=1}^K a_{c_i}+\sum_{i=1}^K b_{d_i}
$$</p>

# 输入格式


<p>从标准输入中读入数据。</p>
<p><strong>本题输入文件包含多组数据。</strong></p>
<p>第一行一个正整数 $T$ 表示数据组数。接下来每三行表示一组数据。</p>
<p>每组数据第一行三个整数 $n, K, L$，变量意义见题目描述。</p>
<p>每组数据第二行 $n$ 个整数表示序列 $\{a_i\}$。</p>
<p>每组数据第三行 $n$ 个整数表示序列 $\{b_i\}$。</p>

# 输出格式


<p>输出到标准输出中。</p>
<p>对于每组数据输出一行一个整数表示答案。</p>

# 样例一


<h4>input</h4>
<pre><code>5
1 1 1
7
7
3 2 1
4 1 2
1 4 2
5 2 1
4 5 5 8 4
2 1 7 2 7
6 4 1
1 5 8 3 2 4
2 6 9 3 1 7
7 5 4
1 6 6 6 5 9 1
9 5 3 9 1 4 2</code></pre>
<h4>output</h4>
<pre><code>14
12
27
45
62</code></pre>
<h4>explanation</h4>
<p>第一组数据选择的下标为： $\{c_i\} = \{1\}, \{d_i\} = \{1\}$；  </p>
<p>第二组数据选择的下标为： $\{c_i\} = \{1 , 3\} ,\{d_i\} = \{2,3\}$；  </p>
<p>第三组数据选择的下标为： $\{c_i\} = \{3, 4\} , \{d_i\} = \{3,5\}$；  </p>
<p>第四组数据选择的下标为： $\{c_i\} = \{2, 3, 4, 6\} , \{d_i\} = \{2,3, 4, 6\}$；  </p>
<p>第五组数据选择的下标为： $\{c_i\} = \{2 ,3, 4, 5, 6\} , \{d_i\} = \{1,2, 3, 4, 6\}$。</p>

# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有测试数据：$T \leq 10 , 1 \le \sum n \le 10^6, 1 \le L \le K \le n \le 2 \times 10^5, 1 \le a_i,b_i \le 10^9$。</p>
<p>每个测试点的具体限制见下表：</p>
 <div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n\le$</th><th>特殊性质</th></tr></thead><tbody><tr><td>$1 \sim 3$</td><td>$10$</td><td rowspan="6">$3 \times 10^5$</td></tr><tr><td>$4, 5$</td><td>$18$</td></tr><tr><td>$6, 7$</td><td>$30$</td></tr><tr><td>$8 \sim 10$</td><td>$150$</td></tr><tr><td>$11 \sim 16$</td><td>$2 \times 10^3$</td></tr><tr><td>$17 \sim 21$</td><td rowspan="2">$2 \times 10^5$</td></tr><tr><td>$22 \sim 25$</td><td>$10^6$</td></tr></tbody></table></div>


<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=480">样例数据下载</a></p>
