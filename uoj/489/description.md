# 题目描述

<p>本题中<strong>合法括号</strong>串的定义如下:</p>
<ol><li>() 是合法括号串。</li>
<li>如果 A 是合法括号串,则 (A) 是合法括号串。</li>
<li>如果 A,B 是合法括号串,则 AB 是合法括号串。</li>
</ol><p>本题中<strong>子串</strong>与<strong>不同的子串</strong>的定义如下:</p>
<ol><li>字符串 $S$ 的子串是 $S$ 中<strong>连续</strong>的任意个字符组成的字符串。$S$ 的子串可用起始位置 $l$ 与终止位置 $r$ 来表示,记为 $S(l, r)$ ($1 \leq l \leq r \leq |S |$,$|S |$ 表示 $S$ 的长度)。</li>
<li>$S$ 的两个子串视作不同<strong>当且仅当</strong>它们在 $S$ 中的位置不同，即 $l$ 不同或 $r$ 不同。</li>
</ol><p>一个大小为 $n$ 的树包含 $n$ 个结点和 $n − 1$ 条边,每条边连接两个结点,且任意两个结点间<strong>有且仅有</strong>一条简单路径互相可达。</p>
<p>小 Q 是一个充满好奇心的小朋友，有一天他在上学的路上碰见了一个大小为 $n$ 的树,树上结点从 $1 ∼ n$ 编号, $1$ 号结点为树的根。除 $1$ 号结点外,每个结点有一个父亲
结点,$u(2 \leq  u \leq n)$号结点的父亲为 $f_u (1 \leq f_u &lt; u)$ 号结点。</p>
<p>小 Q 发现这个树的每个结点上<strong>恰有</strong>一个括号，可能是<code>(</code>或<code>)</code>。</p>
<p>小 Q 定义 $s_i$ 为：将根结点到 $i$ 号结点的简单路径上的括号，按结点经过顺序依次排列组成的字符串。</p>
<p>显然 $s_i$ 是个括号串，但不一定是合法括号串，因此现在小 Q 想对所有的 $n（1 \leq i \leq n）$求出，$s_i$ 中有多少个互不相同的子串是合法括号串。</p>
<p>这个问题难倒了小 Q，他只好向你求助。设 $s_i$ 共有 $k_i$ 个不同子串是合法括号串， 你只需要告诉小 Q 所有 $i \times k_i$ 的异或和，即：</p>
<p>$$ (1 \times k_1)\ xor\ (2 \times k_2)\ xor\ \cdots \ xor\ (n \times k_n)$$</p>
<p>其中 $xor$ 是位异或运算。</p>

# 输入格式


<p>第一行一个整数 $n$ ,表示树的大小。</p>
<p>第二行一个长为 $n$ 的由 <code>(</code> 与 <code>)</code> 组成的括号串,第 $i$ 个括号表示 $i$ 号结点上的括号。</p>
<p>第三行包含 $n − 1$ 个整数,第 $i(1 \leq i &lt; n)$ 个整数表示 $i + 1$ 号结点的父亲编号 $f_{i+1}$ 。</p>

# 输出格式


<p>仅一行一个整数表示答案。</p>

# 样例1


<h4>input</h4>
<pre><code class="sh_plain">5
(()()
1 1 2 2</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">6</code></pre>
<h4>explanation</h4>
<p>树的形态如下图:</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/489/kuohaoshu.webp" style="width:200px;" alt="括号树"/></p>
<p>将根到 1 号结点的简单路径上的括号，按经过顺序排列所组成的字符串为 <code>(</code>，子串是合法括号串的个数为 $0$。</p>
<p>将根到 2 号结点的字符串为 <code>((</code>，子串是合法括号串的个数为 $0$。</p>
<p>将根到 3 号结点的字符串为 <code>()</code>，子串是合法括号串的个数为 $1$。</p>
<p>将根到 4 号结点的字符串为 <code>(((</code>，子串是合法括号串的个数为 $0$。</p>
<p>将根到 5 号结点的字符串为 <code>(()</code>，子串是合法括号串的个数为 $1$。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n \leq $</th><th>特殊性质</th></tr></thead><tbody><tr><td>$1 \sim 2$</td><td>$8$</td><td rowspan="3">$f_i=i-1$</td></tr><tr><td>$3 \sim 4$</td><td>$200$</td></tr><tr><td>$5 \sim 7$</td><td rowspan="2">$2000$</td></tr><tr><td>$8 \sim 10$</td><td></td></tr><tr><td>$11 \sim 14$</td><td rowspan="2">$10^5$</td><td>$f_i=i-1$</td></tr><tr><td>$15 \sim 16$</td><td rowspan="2"></td></tr><tr><td>$17 \sim 20$</td><td>$5 \times 10^5$</td></tr></tbody></table></div>

<p><strong>时间限制:</strong> $1\texttt{s}$</p>
<p><strong>空间限制:</strong> $256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=489">样例数据下载</a></p>
