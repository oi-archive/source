# 题目描述

<p>牛牛是一个热爱算法设计的高中生。在他设计的算法中，常常会使用带小数的数进行计算。牛牛认为，如果在 $k$ 进制下，一个数的小数部分是<strong>纯循环</strong>的，那么它就是美的。</p>
<p>现在，牛牛想知道：对于已知的十进制数 $n$ 和 $m$，在 $k$ 进制下，有多少个数值上<strong>互不相等</strong>的纯循环小数，可以用分数 $\frac{x}{y}$ 表示,其中 $1\le x \le n, 1 \le y \le m$，且 $x, y$ 是整数。</p>
<p>一个数是纯循环的，当且仅当其可以写成以下形式：</p>
<p>$$a.\dot{c_1} c_2 c_3 \ldots c_{p - 1} \dot{c_p}$$</p>
<p>其中，$a$ 是一个整数，$p\ge 1$；对于 $1 \le i \le p$，$c_i$ 是 $k$ 进制下的一位数字。</p>
<p>例如，在十进制下，$0.45454545 \ldots \ldots = 0.\dot{4}\dot{5}$是纯循环的，它可以用 $\frac{5}{11}$、$\frac{10}{22}$ 等分数表示；在十进制下，$0.1666666\ldots \ldots = 0.1\dot{6}$则不是纯循环的，它可以用 $\frac{1}{6}$ 等分数表示。</p>
<p>需要特别注意的是，我们认为一个整数是纯循环的，因为它的小数部分可以表示成 $0$ 的循环或是 $k - 1$ 的循环；而一个小数部分非 $0$ 的有限小数不是纯循环的。</p>

# 输入格式


<p>输入文件只有一行，包含三个十进制数 $n, m, k$，意义如题所述。</p>

# 输出格式


<p>只输出一行一个整数，表示满足条件的美的数的个数。</p>

# 样例一


<h4>input</h4>
<pre>2 6 10

</pre>

<h4>output</h4>
<pre>4

</pre>

<h4>explanation</h4>
<p>满足条件的数分别是：</p>
<p>$$1/1 = 1.0000 \ldots \ldots$$
$$1/3 = 0.3333 \ldots \ldots$$
$$2/1 = 2.0000 \ldots \ldots$$
$$2/3 = 0.6666 \ldots \ldots$$</p>
<p>$1/1$ 和 $2/2$ 虽然都是纯循环小数，但因为它们相等，因此只计数一次；同样，$1/3$ 和 $2/6$ 也只计数一次。</p>

# 样例二


<h4>input</h4>
<pre>23333 666666 310

</pre>

<h4>output</h4>
<pre>5089564081

</pre>


# 提示


<p>这部分将提供一个将分数化为对应的小数的方法，如果你已经熟悉这个方法，你不必阅读本提示。</p>
<p>分数可以通过除法，用分子除以分母化为对应的小数。有些分数在除法过程中无法除尽,这样的分数在不断进行的除法过程中<strong>余数</strong>一定会重复出现。从商数的个位所对应的余数起，设第一次重复出现的余数前两次出现的位置所对应的商数位分别是小数点后第 $a$ 位和小数点后第 $b$ 位（特殊地：如果其中一个对应的商数位是个位，则认为 $a = 0$；不妨设 $a &lt; b$），则其循环部分可以用小数点后第 $a + 1$ 位到小数点后第 $b$ 位的循环来表示。</p>
<p>例如：在十进制下，将 $\frac{5}{11}$ 转化为小数时，个位开始的商数依次为 $4, 5, 4, \ldots$，对应的余数分别为 $6, 5, 6, \ldots$。余数第一次重复出现的位置是个位和小数点后第 $2$ 位,那么 $a = 0, b = 2$ 即其循环部分可以用小数点第 $1$ 位到第 $3$ 位来表示。表示为：$\frac{5}{11} = 0.45454545 \ldots = 0. \dot{4}\dot{5}$。</p>
<p>在十进制下，将 $\frac{1}{6}$ 转化为小数时,个位开始的商数依次为 $1, 6, 6, \ldots$，对应的余数分别为 $4,4,4, \ldots$。余数第一次重复出现的位置是小数点后第 $1$ 位和小数点后第 $2$ 位,即其循环部分可以用小数点后第 $2$ 位来表示。表示为：$\frac{1}{6} = 0.1666 \ldots \ldots = 0.1\dot{6}$。</p>
<p>需要注意的是：商数重复出现并不代表进入了循环节。</p>

# 限制与约定


<p>对于所有的测试点，保证 $1 \le n \le 10^9, 1 \le m \le 10^9, 2 \le k \le 2000$。对于每个测试点，有以下约束（其中留空的表示没有特殊的约束）：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>$k$</th>
</tr></thead><tbody><tr><td>1</td><td>$\leq 10$</td><td>$\le 20$</td><td>$=2$</td></tr><tr><td>2</td><td>$\leq 100$</td><td>$\le 10^4$</td><td>$=2$</td></tr><tr><td>3</td><td>$\leq 1000$</td><td></td><td>$=2$</td></tr><tr><td>4</td><td>$\leq 10000$</td><td></td><td>$=2$</td></tr><tr><td>5</td><td>$\leq 10$</td><td>$\le 20$</td><td>$=3$</td></tr><tr><td>6</td><td>$\leq 100$</td><td>$\le 10^4$</td><td>$=3$</td></tr><tr><td>7</td><td>$\leq 1000$</td><td></td><td>$=3$</td></tr><tr><td>8</td><td>$\leq 10000$</td><td></td><td>$=3$</td></tr><tr><td>9</td><td>$\leq 10$</td><td>$\le 20$</td><td>$\le 100$</td></tr><tr><td>10</td><td>$\leq 100$</td><td>$\le 10^4$</td><td>$\le 100$</td></tr><tr><td>11</td><td>$\leq 1000$</td><td></td><td>$\le 1000$</td></tr><tr><td>12</td><td>$\leq 10000$</td><td></td><td></td></tr><tr><td>13</td><td>$\leq 10^5$</td><td>$\le 10^8$</td><td>$\le 100$</td></tr><tr><td>14</td><td>$\leq 2 \times 10^5$</td><td></td><td>$\le 1000$</td></tr><tr><td>15</td><td>$\leq 5 \times 10^5$</td><td></td><td></td></tr><tr><td>16</td><td>$\leq 10^6$</td><td>$\le 10^8$</td><td>$\le 100$</td></tr><tr><td>17</td><td>$\leq 2 \times 10^6$</td><td></td><td>$\le 1000$</td></tr><tr><td>18</td><td>$\leq 5 \times 10^6$</td><td></td><td></td></tr><tr><td>19</td><td>$\leq 10^7$</td><td>$\le 10^8$</td><td>$\le 100$</td></tr><tr><td>20</td><td>$\leq 2 \times 10^7$</td><td></td><td>$\le 1000$</td></tr><tr><td>21</td><td>$\leq 2 \times 10^7$</td><td></td><td></td></tr><tr><td>22</td><td>$\leq 10^8$</td><td>$\le 10^8$</td><td></td></tr><tr><td>23</td><td>$\leq 10^8$</td><td>$\le 10^8$</td><td></td></tr><tr><td>24、25</td><td></td><td></td><td></td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=221">样例数据下载</a></p>
