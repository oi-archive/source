# 题目描述

<p>给定一棵 $n$ 个结点的有根树 $T$，结点从 $1$ 开始编号，根结点为 $1$ 号结点，每个结点有一个正整数权值 $v_i$。</p>
<p>设 $x$ 号结点的子树内（包含 $x$ 自身）的所有结点编号为 $c_1, c_2, \dots, c_k$，定义 $x$ 的价值为：</p>
<p>$$
val(x) = (v_{c_1} + d(c_1, x)) \oplus (v_{c_2} + d(c_2, x)) \oplus \cdots \oplus (v_{c_k} + d(c_k, x))
$$</p>
<p>其中 $d(x, y)$ 表示树上 $x$ 号结点与 $y$ 号结点间唯一简单路径所包含的边数，$d(x, x) = 0$。$\oplus$ 表示异或运算。</p>
<p>请你求出 $\sum_{i=1}^n val(i)$ 的结果。</p>

# 输入格式


<p>第一行一个正整数 $n$ 表示树的大小。</p>
<p>第二行 $n$ 个正整数表示 $v_i$。</p>
<p>接下来一行 $n-1$ 个正整数，依次表示 $2$ 号结点到 $n$ 号结点，每个结点的父亲编号 $p_i$。</p>

# 输出格式


<p>一行一个整数表示答案。</p>

# 样例1


<h4>input</h4>
<pre><code class="sh_plain">5
5 4 1 2 3
1 1 2 2</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">12</code></pre>
<h4>explanation</h4>
<p>$val(1) = (5 + 0)\oplus(4 + 1)\oplus(1 + 1)\oplus(2 + 2)\oplus(3 + 2) = 3$。</p>
<p>$val(2) = (4 + 0)\oplus(2 + 1)\oplus(3 + 1) = 3$。</p>
<p>$val(3) = (1 + 0) = 1$。</p>
<p>$val(4) = (2 + 0) = 2$。</p>
<p>$val(5) = (3 + 0) = 3$。</p>
<p>和为 $12$。</p>

# 样例2


<p>见附加文件中 <code>ex_tree2.in</code> 与 <code>ex_tree2.ans</code>。</p>

# 数据范围


<p>对于前 $10\%$ 的数据：$1\le n\le 2501$。</p>
<p>对于前 $40\%$ 的数据：$1\le n\le 152501$。</p>
<p>另有 $20\%$ 的数据：所有 $p_i = i - 1 (2\le i\le n)$。</p>
<p>另有 $20\%$ 的数据：所有 $v_i = 1 (1\le i\le n)$。</p>
<p>对于 $100\%$ 的数据：$1\le n, v_i \le 525010, 1\le p_i\le n$。</p>
<p><strong>时间限制:</strong> $2\texttt{s}$</p>
<p><strong>空间限制:</strong> $512\texttt{MB}$</p>
<p><a href="http://uoj.ac/download.php?type=problem&amp;id=543">附加文件</a></p>
