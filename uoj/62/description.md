# 题目描述

<div class="hide">
$\newcommand\lcm{\mathbin{\mathrm{lcm}}}$
</div>

<p>大力水手问禅师：“大师，我觉得我光有力气是不够的。比如我吃菠菜可以让力气更大，但是却没有提升跑步的速度。请问怎样才能跑得更快？我试过吃白菜，没有效果。”</p>
<p>禅师浅笑，答：“方法很简单，不过若想我教你，你先看看这道UOJ Round的C题。”</p>
<p>令 $p = 998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）。</p>
<p>给你整数 $n, c, d$。现在有整数 $x_1, \dots, x_n$ 和 $b_1, \dots, b_n$ 满足 $0 \leq x_1, \dots, x_n, b_1, \dots, b_n &lt; p$，且对于 $1 \leq i \leq n$ 满足：</p>
<p>\begin{equation}
\sum_{j = 1}^{n} \gcd(i, j)^c \cdot \lcm(i, j)^d \cdot x_j \equiv b_i \pmod{p}
\end{equation}
其中 $v \equiv u \pmod{p}$ 表示 $v$ 和 $u$ 除以 $p$ 的余数相等。$\gcd(i, j)$ 表示 $i$ 和 $j$ 的最大公约数，$\lcm(i, j)$ 表示 $i$ 和 $j$ 的最小公倍数。</p>
<p>有 $q$ 个询问，每次给出 $b_1, \dots, b_n$，请你解出 $x_1, \dots, x_n$ 的值。</p>

# 输入格式


<p>第一行四个整数 $n, c, d, q$。保证 $n, q \geq 1$。</p>
<p>接下来 $q$ 行，每行 $n$ 个整数依次表示 $b_1, \dots, b_n$。保证 $0 \leq b_1, \dots, b_n &lt; p$。</p>

# 输出格式


<p>共 $q$ 行，每行对给出的 $b_1, \dots, b_n$，输出对应的 $x_1, \dots, x_n$。如果有多组解输出任意一组即可。如果无解那么这一行只用输出一个整数 $-1$。</p>

# 样例一


<h4>input</h4>
<pre>3 1 0 2
1 0 0
1 2 3

</pre>

<h4>output</h4>
<pre>499122179 998244352 499122176
998244352 1 1

</pre>

<h4>explanation</h4>
<p>对于第一个询问，要满足的等式为：</p>
<p>\begin{eqnarray}
\begin{cases}
x_1 + x_2 + x_3 &amp; \equiv &amp; 1 &amp; \pmod{p}\\
x_1 + 2x_2 + x_3 &amp; \equiv &amp; 0 &amp; \pmod{p}\\
x_1 + x_2 + 3x_3 &amp; \equiv &amp; 0 &amp; \pmod{p}
\end{cases}
\end{eqnarray}</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有数据，$nq \leq 3 \times 10^5$，$0 \leq c, d \leq 10^9$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$q$</th>
<th>其他</th>
</tr></thead><tbody><tr><td>1</td><td>$\leq 3$</td><td>$=1$</td><td>$c, d \leq 1000$</td></tr><tr><td>2</td><td rowspan="7">$\leq 100$</td><td>$=1$</td><td>$c = d$</td></tr><tr><td>3</td><td rowspan="2">$\leq 10$</td><td rowspan="2">保证有唯一解</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="4">$\leq 1000$</td><td>$c = 1, d = 0$</td></tr><tr><td>6</td><td rowspan="3">保证有唯一解</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="6">$\leq 1000$</td><td rowspan="3">$=1$</td><td rowspan="3">保证有唯一解</td></tr><tr><td>10</td></tr><tr><td>11</td></tr><tr><td>12</td><td rowspan="3">$\leq 10$</td><td>$c = d$</td></tr><tr><td>13</td><td rowspan="2">保证有唯一解</td></tr><tr><td>14</td></tr><tr><td>15</td><td rowspan="6">$\leq 10^5$</td><td rowspan="6">$\leq 3$</td><td rowspan="2">$c = 1, d = 0$</td></tr><tr><td>16</td></tr><tr><td>17</td><td>$c = d$</td></tr><tr><td>18</td><td rowspan="3">无</td></tr><tr><td>19</td></tr><tr><td>20</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 后记


<p>还没听完题，大力水手就嘶吼着：“太难了我不会我不会！”，飞快地跑掉了。</p>
<p>禅师看着大力水手消失的背影，叹了口气说：“你们这些人啊，每天就想做些大水题，一碰到难题，跑得不知道比谁都快。”</p>
<p>后来大力水手把UOJ Round的C题题面贴在了汽车的后挡风玻璃上，人类从此掌握了光速旅行的正确方式。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=62">样例数据下载</a></p>
