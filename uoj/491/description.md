# 题目描述

<p>Emiya 是个擅长做菜的高中生，他共掌握 $n$ 种<strong>烹饪方法</strong>,且会使用 $m$ 种<strong>主要食材</strong> 做菜。为了方便叙述，我们对烹饪方法从 $1∼n$ 编号，对主要食材从 $1∼m$ 编号。 </p>
<p>Emiya 做的每道菜都将使用<strong>恰好一种</strong>烹饪方法与<strong>恰好一种</strong>主要食材。更具体地， Emiya 会做 $a_{i,j}$ 道不同的使用烹饪方法 $i$ 和主要食材 $j$ 的菜 $(1 \leq i \leq n,1 \leq j \leq m)$，这也意味着 Emiya 总共会做 $\sum\limits_{i=1}^{n} \sum\limits_{i=1}^{m} a_{i,j}$ 道不同的菜。</p>
<p>Emiya 今天要准备一桌饭招待 Yazid 和 Rin 这对好朋友，然而三个人对菜的搭配 有不同的要求，更具体地，对于一种包含 $k$ 道菜的搭配方案而言：</p>
<ul><li>Emiya 不会让大家饿肚子，所以将做<strong>至少一道菜</strong>，即 $k \geq 1$。</li>
<li>Rin 希望品尝不同烹饪方法做出的菜，因此她要求每道菜的<strong>烹饪方法互不相同</strong>。</li>
<li>Yazid 不希望品尝太多同一食材做出的菜，因此他要求每种<strong>主要食材</strong>至多在<strong>一半</strong>的菜（即 $\lfloor \frac{k}{2} \rfloor$ 道菜）中被使用 </li>
</ul><p>这里的 $\lfloor x \rfloor$ 为下取整函数，表示不超过 $x$ 的最大整数。</p>
<p>这些要求难不倒 Emiya，但他想知道共有多少种不同的符合要求的搭配方案。两种方案不同，当且仅当存在至少一道菜在一种方案中出现，而不在另一种方案中出现。 </p>
<p>Emiya 找到了你，请你帮他计算，你只需要告诉他符合所有要求的搭配方案数对质数 $998,244,353$ 取模的结果。</p>

# 输入格式


<p>第 1 行两个用单个空格隔开的整数 $n,m$。</p>
<p>第 2 行至第 $n + 1$ 行，每行 $m$ 个用单个空格隔开的整数，其中第 $i + 1$ 行的 $m$ 个 数依次为 $a_{i,1},a_{i,2},...,a_{i,m}$。</p>

# 输出格式


<p>仅一行一个整数，表示所求方案数对 $998,244,353$ 取模的结果。</p>

# 样例1


<h4>input</h4>
<pre><code>2 3
1 0 1
0 1 1</code></pre>

# output


<pre><code>3</code></pre>

# explanation


<p>由于在这个样例中，对于每组 $i, j$，Emiya 都最多只会做一道菜，因此我们直接通 过给出烹饪方法、主要食材的编号来描述一道菜。 </p>
<p>符合要求的方案包括：</p>
<ul><li>做一道用烹饪方法 1、主要食材 1 的菜和一道用烹饪方法 2、主要食材 2 的菜</li>
<li>做一道用烹饪方法 1、主要食材 1 的菜和一道用烹饪方法 2、主要食材 3 的菜</li>
<li>做一道用烹饪方法 1、主要食材 3 的菜和一道用烹饪方法 2、主要食材 2 的菜 </li>
</ul><p>因此输出结果为 3 mod 998,244,353 = 3。 </p>
<p>需要注意的是，所有只包含一道菜的方案都是不符合要求的，因为唯一的主要食材 在超过一半的菜中出现，这不满足 Yazid 的要求。</p>

# 样例2


<h4>input</h4>
<pre><code>3 3
1 2 3
4 5 0
6 0 0</code></pre>

# output


<pre><code>190</code></pre>

# explanation


<p>Emiya 必须至少做 2 道菜。</p>
<p>做 2 道菜的符合要求的方案数为 100。</p>
<p>做 3 道菜的符合要求的方案数为 90。</p>
<p>因此符合要求的方案数为 100 + 90 = 190。</p>

# 样例3


<h4>input</h4>
<pre><code>5 5
1 0 0 1 1
0 1 0 1 0
1 1 1 1 0
1 0 1 0 1
0 1 1 0 1</code></pre>

# output


<pre><code>742</code></pre>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n \leq $</th><th>$m \leq $</th><th>$a_{i,j} &lt;$</th></tr></thead><tbody><tr><td>$1$</td><td rowspan="2">$2$</td><td>$2$</td><td rowspan="6">$2$</td></tr><tr><td>$2$</td><td>$3$</td></tr><tr><td>$3$</td><td rowspan="2">$5$</td><td>$2$</td></tr><tr><td>$4$</td><td>$3$</td></tr><tr><td>$5$</td><td rowspan="4">$10$</td><td>$2$</td></tr><tr><td>$6$</td><td>$3$</td></tr><tr><td>$7$</td><td>$2$</td><td rowspan="5">$1000$</td></tr><tr><td>$8$</td><td>$3$</td></tr><tr><td>$9 \sim 12$</td><td rowspan="3">$40$</td><td>$2$</td></tr><tr><td>$13 \sim 16$</td><td>$3$</td></tr><tr><td>$17 \sim 21$</td><td>$500$</td></tr><tr><td>$22 \sim 25$</td><td>$100$</td><td>$2000$</td><td>$998,244,353$</td></tr></tbody></table></div>

<p>对于所有测试点，保证 $1 \leq n \leq 100，1 \leq m \leq 2000，0 \leq a_{i,j} &lt; 998,244,353$。</p>
<p><strong>时间限制:</strong> $1\texttt{s}$</p>
<p><strong>空间限制:</strong> $256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=491">样例数据下载</a></p>
