# 题目描述

<p>婷婷是个喜欢矩阵的小朋友,有一天她想用电脑生成一个巨大的 $n$ 行 $m$ 列的矩阵（你不用担心她如何存储）。她生成的这个矩阵满足一个神奇的性质：
若用 $F_{i,j}$ 来表示矩阵中第 $i$ 行第 $j$ 列的元素，则 $F_{i,j}$ 满足下面的递推式：</p>
<p>\begin{cases}
F_{1,1} &amp; = &amp; 1 \\
F_{i,j} &amp; = &amp; a \cdot F_{i,j - 1} + b &amp; j \neq 1 \\
F_{i,1} &amp; = &amp; c \cdot F_{i - 1,m} + d &amp; i \neq 1
\end{cases}</p>
<p>递推式中 $a, b, c, d$ 都是给定的常数。
现在婷婷想知道 $F_{n,m}$ 的值是多少，请你帮助她。由于最终结果可能很大，你只需要输出 $F_{n,m}$ 除以 $1000000007$ 的余数。</p>

# 输入格式


<p>包含一行有六个整数 $n, m, a, b, c, d$。意义如题所述。</p>

# 输出格式


<p>表示 $F_{n,m}$ 除以 $1000000007$ 的余数。</p>

# 样例一


<h4>input</h4>
<pre>3 4 1 3 2 6

</pre>

<h4>output</h4>
<pre>85

</pre>

<h4>explanation</h4>
<p>样例中的矩阵为：</p>
<p>\begin{equation}
\left(\begin{array}{cccc}
1 &amp; 4 &amp; 7 &amp; 10\\
26 &amp; 29 &amp; 32 &amp; 35\\
76 &amp; 79 &amp; 82 &amp; 85
\end{array}
\right)
\end{equation}</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>数据范围</th>
</tr></thead><tbody><tr><td>1</td><td>$1 \leq n, m \leq 10$；$1 \leq a, b, c, d \leq 1000$</td></tr><tr><td>2</td><td>$1 \leq n, m \leq 100$；$1 \leq a, b, c, d \leq 1000$</td></tr><tr><td>3</td><td>$1 \leq n, m \leq 10^3$；$1 \leq a, b, c, d \leq 10^9$</td></tr><tr><td>4</td><td>$1 \leq n, m \leq 10^3$；$1 \leq a, b, c, d \leq 10^9$</td></tr><tr><td>5</td><td>$1 \leq n, m \leq 10^9$；$1 \leq a = c \leq 10^9$；$1 \leq b = d \leq 10^9$</td></tr><tr><td>6</td><td>$1 \leq n, m \leq 10^9$；$a = c = 1$；$1 \leq b, d \leq 10^9$</td></tr><tr><td>7</td><td>$1 \leq n, m, a, b, c, d \leq 10^9$</td></tr><tr><td>8</td><td>$1 \leq n, m, a, b, c, d \leq 10^9$</td></tr><tr><td>9</td><td>$1 \leq n, m, a, b, c, d \leq 10^9$</td></tr><tr><td>10</td><td>$1 \leq n, m, a, b, c, d \leq 10^9$</td></tr><tr><td>11</td><td>$1 \leq n, m \leq 10^{1000}$；$a = c = 1$；$1 \leq b, d \leq 10^9$</td></tr><tr><td>12</td><td>$1 \leq n, m \leq 10^{1000}$；$1 \leq a = c \leq 10^9$；$1 \leq b = d \leq 10^9$</td></tr><tr><td>13</td><td>$1 \leq n, m \leq 10^{1000}$；$1 \leq a, b, c, d \leq 10^9$</td></tr><tr><td>14</td><td>$1 \leq n, m \leq 10^{1000}$；$1 \leq a, b, c, d \leq 10^9$</td></tr><tr><td>15</td><td>$1 \leq n, m \leq 10^{20000}$；$1 \leq a, b, c, d \leq 10^9$</td></tr><tr><td>16</td><td>$1 \leq n, m \leq 10^{20000}$；$1 \leq a, b, c, d \leq 10^9$</td></tr><tr><td>17</td><td>$1 \leq n, m \leq 10^{1000000}$；$a = c = 1$；$1 \leq b, d \leq 10^9$</td></tr><tr><td>18</td><td>$1 \leq n, m \leq 10^{1000000}$；$1 \leq a = c \leq 10^9$；$1 \leq b = d \leq 10^9$</td></tr><tr><td>19</td><td>$1 \leq n, m \leq 10^{1000000}$；$1 \leq a, b, c, d \leq 10^9$</td></tr><tr><td>20</td><td>$1 \leq n, m \leq 10^{1000000}$；$1 \leq a, b, c, d \leq 10^9$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=124">样例数据下载</a></p>
