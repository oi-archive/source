# 题目描述

<p>厨师准备给小朋友们制作 $m$ 道菜，每道菜均使用 $k$ 克原材料。为此，厨师购入了 $n$ 种原材料，原材料从 $1$ 到 $n$ 编号，第 $i$ 种原材料的质量为 $d_i$ 克。$n$ 种原材料的<strong>质量之和恰好为 $m \times k$ 克</strong>，其中 $d_i$ 与 $k$ 都是<strong>正整数</strong>。</p>
<p>制作菜品时，一种原材料可以被用于多道菜，但为了让菜品的味道更纯粹，厨师打算每道菜<strong>至多使用 $2$ 种</strong>原材料。现在请你判断是否存在一种满足要求的制作方案。更具体地，方案应满足下列要求：</p>
<ul><li>共做出 $m$ 道菜。</li>
<li>每道菜至多使用 $2$ 种原材料。</li>
<li>每道菜恰好使用 $k$ 克原材料。</li>
<li>每道菜使用的每种原材料的质量都为正整数克。</li>
<li>$n$ 种原材料都被恰好用完。</li>
</ul><p>若存在满足要求的制作方案，你还应该给出一种具体的制作方案。</p>

# 输出格式


<p><strong>本题单个测试点包含多组测试数据。</strong></p>
<p>第一行一个整数 $T$ 表示数据组数。对于每组数据：</p>
<ul><li>第一行三个正整数 $n,m,k$ 分别表示原材料种数、需要制作的菜品道数、每道菜品需使用的原材料的质量。</li>
<li>第二行 $n$ 个整数，第 $i$ 个整数表示第 $i$ 种原材料的质量 $a_i$。</li>
</ul>
# 输出格式


<p>对于每组测试数据：</p>
<ul><li><strong>若不存在满足要求的制作方案，则输出一行一个整数</strong> <samp>-1</samp>；</li>
<li>否则你需要输出 $m$ 行，每行表示一道菜品的制作方案，根据使用的原材料种数，格式为下列两种之一：<ul><li>依次输出一行两个整数 $i$ 和 $x$，表示该道菜使用 $i$ 克第 $x$ 种原材料制作。你应保证 $1 \le i \le n,x=k$。</li>
<li>依次输出一行四个整数 $i$、$x$、$j$ 和 $y$，表示该道菜使用 $x$ 克第 $i$ 种原材料与 $y$ 克第 $j$ 种原材料制作。你应保证 $1 \le i, j \le n,i \neq j$，$x+y=k$，$x,y&gt;0$。</li>
</ul></li>
</ul><p>本题使用<strong>自定义校验器</strong>检验你的答案是否正确，因此若有多种满足条件的方案，你只需要输出<strong>任意一种</strong>。</p>
<p>你应保证方案输出的格式正确，且同一行中相邻的两个数使用单个空格分隔，除此之外你的输出中<strong>不应包含其他多余字符</strong>。</p>

# 样例一


<h4>input</h4>
<pre>4
1 1 10
10
4 3 100
80 30 90 100
5 3 1000
200 400 500 900 1000
6 4 100
25 30 50 80 95 120
</pre>

<h4>output</h4>
<pre>1 10
1 80 2 20
2 10 3 90
4 100
-1
1 5 5 95
1 20 4 80
2 30 6 70
3 50 6 50
</pre>

<h4>explanation</h4>
<p>对于第二组数据，一种满足要求的制作方案为：</p>
<ul><li>使用 $80$ 克原材料 $1$ 与 $20$ 克原材料 $2$ 做第一道菜。</li>
<li>使用 $10$ 克原材料 $2$ 与 $90$ 克原材料 $3$ 做第二道菜。</li>
<li>使用 $100$ 克原材料 $4$ 做第三道菜。</li>
</ul>
# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 数据范围


<p>对于所有测试点：</p>
<p>$1 \le T \le 10,1 \le n \le 500,n-2 \le m \le 5000, m \ge 1$，</p>
<p>$1 \le k \le 5000,\sum_{i=1}^{n} d_i = m \times k$。</p>
<p>每个测试点的具体限制见下表：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m$</th><th>$k$</th></tr></thead><tbody><tr><td>$1 \sim 3$</td><td>$\le 4$</td><td>$\le 4$</td><td>$\le 50$</td></tr><tr><td>$4 \sim 5$</td><td>$\le 10$</td><td>$\le 10$</td><td rowspan="4">$\le 5000$</td></tr><tr><td>$6 \sim 7$</td><td rowspan="2">$\le 500$</td><td>$=n-1$</td></tr><tr><td>$8 \sim 9$</td><td>$n-1 \le m \le 5000$</td></tr><tr><td>$10$</td><td rowspan="2">$\le 25$</td><td rowspan="5">$\le 5000$</td></tr><tr><td>$11 \sim 12$</td><td rowspan="2">$\le 500$</td></tr><tr><td>$13 \sim 14$</td><td>$\le 50$</td></tr><tr><td>$15 \sim 17$</td><td>$\le 100$</td><td rowspan="2">$\le 50$</td></tr><tr><td>$18 \sim 20$</td><td>$\le 500$</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=561">样例数据下载</a></p>
