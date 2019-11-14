# 题目描述

<p>Snuke 有一棵 $n$ 个点的有根树，每个点有权值 $w_i$，初始每个结点上都没有石子。</p>
<p>Snuke 准备了一些石子，并把它们拿在手中。她可以进行以下两种操作任意多次：</p>
<ol><li>从手中取 $w_i$ 个石子放在结点 $i$ 上，进行该操作要求结点 $i$ 的所有孩子 $j$ 上都有 $w_j$ 个石子。</li>
<li>将结点 $i$ 上的所有石子收回手中。</li>
</ol><p>Takahashi 想知道对于每个 $i$，为了在结点 $i$ 上放 $w_i$ 个石子，Snuke 至少需要准备多少石子。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行一个数字 $T$ 表示这个子任务的编号。</p>
<p>第二行一个正整数 $n$ 。$(n \leq 2 \times 10^5)$</p>
<p>第三行 $n-1$ 个正整数，第 $i-1$ 个数 $p_i$ 表示 $i$ 的父亲。$(p_i &lt; i)$</p>
<p>第四行 $n$ 个正整数，第 $i$ 个数为 $w_i$ 。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出一行 $n$ 个正整数，第 $i$ 个数为结点 $i$ 的答案。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">0
3
1 2
1 1 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">2 2 1</code></pre>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">0
3
1 1
1 1 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">3 1 1</code></pre>

# 限制及约定


<p>对于所有数据，保证：</p>
<ul><li>$n \leq 2 \times 10^5$</li>
<li>$1 \le p_i &lt; i$</li>
<li>$1 \le w_i \le 10^9$</li>
</ul><div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务编号</th><th rowspan="1">特殊性质</th><th rowspan="1">分值</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$n \leq 15$</td><td rowspan="1">9</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$n \leq 2000$</td><td rowspan="1">19</td></tr><tr><td rowspan="1">3</td><td rowspan="1">所有$w$相同</td><td rowspan="1">6</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$w_i \leq w_{i+1}$</td><td rowspan="1">12</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$n \leq 2000$ 且所有点度数 $\leq 2$</td><td rowspan="1">5</td></tr><tr><td rowspan="1">6</td><td rowspan="1">除根结点外所有点度数 $\leq 2$</td><td rowspan="1">13</td></tr><tr><td rowspan="1">7</td><td rowspan="1">无特殊限制</td><td rowspan="1">36</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$3\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=418">样例数据下载</a></p>
