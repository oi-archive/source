# 题目描述

<p>有一天，ydc 在网上乱逛的时候，发现了一场比赛。这场比赛共 $n$ 位选手参加，编号为 $1, \dots, n$，且 ydc 的编号为 $n$。</p>
<p>如果你能在这场比赛中获得第 $i$ 名，那么你可以得到 $p_i$ 块软妹币作为奖金。有奖金可以拿，ydc 是自然不会放过这个便宜的，而且软妹币肯定是拿得越多越好。所以 ydc 进行了充分的研究，分别计算出了所有选手得分的概率分布（包括自己）。</p>
<p>这场考试的得分可以为任意 $[0, 1]$ 中的实数。对于第 $i$ 个人，他得 $x$ 分的概率，与一个多项式函数 $f_i(x)$ 成正比。当然，$f_i(x)$ 的定义域为 $[0, 1]$。</p>
<p>如果第 $i$ 个人的函数为 $f_i(x)=2$，那么他获得任意分数的概率都是相等的；如果一个人的函数为 $f_i(x)=x+1$，那么他获得 $0$ 分的概率是获得 $1$ 分的概率二分之一倍。</p>
<p>你需要计算的是 ydc 得到的奖金的期望。由于分数是实数所以两个人分数相等的概率为无穷小，所以无需考虑排名相等的情况。</p>
<p>ydc 当然早就算出来啦！但是他想考考你。</p>
<p>对于一个有理数一定能表示成 $\frac{a}{b}$ 的形式，其中 $a \geq 0, b &gt; 0$，且 $a, b$ 互质。对于一个质数 $p$，如果 $b$ 不是 $p$ 的倍数那么我们可以定义 $\frac{a}{b} \bmod p$ 为使 $bx \equiv a \pmod{p}$ 的最小非负整数 $x$。如果 $b$ 是 $p$ 的倍数那么 $\frac{a}{b} \bmod p$ 未定义。</p>
<p>答案一定是个有理数，输出对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）取模后的结果（保证有定义）。</p>

# 输入格式


<p>第一行包含一个整数 $n$。</p>
<p>在第二行有 $n$ 个整数，第 $i$ 个数代表 $p_i$。保证 $p_1 \geq p_2 \geq \dots \geq p_n$。</p>
<p>接下来 $n$ 行，每行第一个数为正整数 $t_i$，代表第 $i$ 个人所对应的函数是一个定义域在 $[0, 1]$ 上的 $t_i - 1$ 次的多项式函数，接下来 $t_i$ 个非负整数，第 $j$ 个数代表该函数中 $x^{j-1}$ 项的系数。所有系数均小于 $998244353$。</p>
<p>显然所有人的函数在 $[0,1]$ 的范围以内大于等于 $0$。保证所有函数在 $[0,1]$ 的范围内与 $x$ 轴所成的面积在模 $998244353$ 意义下有定义且不等于 $0$。</p>

# 输出格式


<p>输出一行，包含一个整数，表示 ydc 获得的软妹币数量的期望对 $998244353$ 取模后的结果。</p>

# 样例一


<h4>input</h4>
<pre>2
2 1
1 1
2 0 1

</pre>

<h4>output</h4>
<pre>665496237

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$\sum_{i = 1}^{n} t_i$</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$=2$</td><td>$= 5$</td><td rowspan="10">无</td></tr><tr><td>2</td><td>$=10$</td></tr><tr><td>3</td><td rowspan="4">$=10$</td><td>$= 40$</td></tr><tr><td>4</td><td>$= 60$</td></tr><tr><td>5</td><td>$= 80$</td></tr><tr><td>6</td><td>$= 100$</td></tr><tr><td>7</td><td rowspan="4">$=100$</td><td>$= 400$</td></tr><tr><td>8</td><td>$= 600$</td></tr><tr><td>9</td><td>$= 800$</td></tr><tr><td>10</td><td>$= 1000$</td></tr><tr><td>11</td><td rowspan="10">$=500$</td><td rowspan="4">$= 4000$</td><td>所有名次奖金相等</td></tr><tr><td>12</td><td>所有人的函数相同</td></tr><tr><td>13</td><td rowspan="2">除了第一名与最后一名外其它名次奖金相等</td></tr><tr><td>14</td></tr><tr><td>15</td><td>$= 1500$</td><td rowspan="6">无</td></tr><tr><td>16</td><td>$= 2000$</td></tr><tr><td>17</td><td>$= 2500$</td></tr><tr><td>18</td><td>$= 3000$</td></tr><tr><td>19</td><td>$= 3500$</td></tr><tr><td>20</td><td>$= 4000$</td></tr></tbody></table></div>

<p><strong>保证数据为均匀随机生成。</strong></p>
<p>对于 $1 \leq i \leq n$ 有 $0 \leq p_i \leq 10000$。</p>
<p><strong>时间限制：</strong>$6\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 来源


<p>中国国家集训队互测2015 - By 刘剑成</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=102">样例数据下载</a></p>
