# 题目描述

<p>小 R 喜欢研究机器人。</p>
<p>最近，小 R 新研制出了两种机器人，分别是 P 型机器人和 Q 型机器人。现在他要测试这两种机器人的移动能力，测试在从左到右排成一排的 $n$ 个柱子上进行，柱子用 $1 \sim n$ 依次编号，$i$ 号柱子的高度为一个正整数 $h_i$。机器人<strong>只能</strong>在<strong>相邻</strong>柱子间移动，即：若机器人当前在 $i$ 号柱子上，它只能尝试移动到 $i − 1$ 号和 $i + 1$ 号柱子上。</p>
<p>每次测试，小 R 会选取一个起点 $s$，并将两种机器人均放置在 $s$ 号柱子上。随后它们会按自己的规则移动。</p>
<p>P 型机器人会一直<strong>向左</strong>移动，但它<strong>无法</strong>移动到比起点 $s$ <strong>更高</strong>的柱子上。更具体地，P 型机器人在 $l\ (l \le s)$ 号柱子停止移动，<strong>当且仅当</strong>下列两个条件均成立：</p>
<ul><li>$l = 1$ 或 $h_{l−1} &gt; h_s$；</li>
<li>对于满足 $l \le j \le s$ 的 $j$，有 $h_j \le h_s$。</li>
</ul><p>Q 型机器人会一直<strong>向右</strong>移动，但它<strong>只能</strong>移动到比起点 $s$ <strong>更低</strong>的柱子上。更具体地，Q 型机器人在 $r\ (r \ge s)$ 号柱子停止移动，<strong>当且仅当</strong>下列两个条件均成立：</p>
<ul><li>$r = n$ 或 $h_{r+1} \ge h_s$；</li>
<li>对于满足 $s &lt; j \le r$ 的 $j$，有 $h_j &lt; h_s$。</li>
</ul><p>现在，小 R 可以设置每根柱子的高度，$i$ 号柱子可选择的高度范围为 $[A_i, B_i]$，即 $A_i \le h_i \le B_i$。小 R 希望<strong>无论</strong>测试的起点 $s$ 选在哪里，两种机器人移动过的柱子数量的差的绝对值都<strong>小于等于</strong> $2$。他想知道有多少种柱子高度的设置方案满足要求，小 R 认为两种方案不同当且仅当存在一个 $k$，使得两种方案中 $k$ 号柱子的高度不同。请你告诉他满足要求的方案数模 $10^9 + 7$ 后的结果。</p>

# 输入格式


<p>从标准输入中读入数据。</p>
<p>第一行一个正整数 $n$，表示柱子的数量。</p>
<p>接下来 $n$ 行，第 $i$ 行两个正整数 $A_i, B_i$，分别表示 $i$ 号柱子的最小和最大高度。</p>

# 输出格式


<p>输出到标准输出中。</p>
<p>仅一行一个整数，表示答案模 $10^9 + 7$ 的值。</p>

# 样例一


<h4>input</h4>
<pre><code>5
3 3
2 2
3 4
2 2
3 3</code></pre>
<h4>output</h4>
<pre><code>1</code></pre>
<h4>explanation</h4>
<p>柱子高度共两种情况：
1. 高度为：$3, 2, 3, 2, 3$。此时若起点设置在 $5$，P 型机器人将停在 $1$ 号柱子，共移动 $4$ 个柱子。Q 型机器人停在 $5$ 号柱子，共移动 $0$ 个柱子，不符合条件；
2. 高度为：$3, 2, 4, 2, 3$。此时无论起点选在哪，都满足条件，具体见下表：</p>
 <div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>起点编号</th><th>P 型机器人</th><th>Q 型机器人</th></tr></thead><tbody><tr><td>1</td><td>停在 1 号柱子，移动过 0 个</td><td>停在 2 号柱子，移动过 1 个</td></tr><tr><td>2</td><td>停在 2 号柱子，移动过 0 个</td><td>停在 2 号柱子，移动过 0 个</td></tr><tr><td>3</td><td>停在 1 号柱子，移动过 2 个</td><td>停在 5 号柱子，移动过 2 个</td></tr><tr><td>4</td><td>停在 4 号柱子，移动过 0 个</td><td>停在 4 号柱子，移动过 0 个</td></tr><tr><td>5</td><td>停在 4 号柱子，移动过 1 个</td><td>停在 5 号柱子，移动过 0 个</td></tr></tbody></table></div>


# 样例二至样例四


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有测试数据：$1 \le n \le 300 , 1 \le A_i \le B_i \le 10^9$。</p>
<p>每个测试点的具体限制见下表：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n\le$</th><th>特殊性质</th></tr></thead><tbody><tr><td>$1,2$</td><td rowspan="2">$7$</td><td>$A_i=B_i,B_i\le 7$</td></tr><tr><td>$3,4$</td><td>$B_i\le 7$</td></tr><tr><td>$5\sim 7$</td><td>$50$</td><td>$B_i\le 100$</td></tr><tr><td>$8\sim 10$</td><td>$300$</td><td>$B_i\le 10^4$</td></tr><tr><td>$11,12$</td><td rowspan="2">50</td><td>$A_i=1,B_i=10^9$</td></tr><tr><td>$13 \sim 15$</td><td rowspan="4">无</td></tr><tr><td>$16,17$</td><td>150</td></tr><tr><td>$18,19$</td><td>200</td></tr><tr><td>$20$</td><td>300</td></tr></tbody></table></div>


<p><strong>时间限制</strong>：$3\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=479">样例数据下载</a></p>
