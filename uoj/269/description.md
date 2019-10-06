# 题目描述

<p>$\pi\text{+}e$ 在高中上数学课时经常睡觉，然而每次考试都能 $AK$，这让他的同桌叶子很是膜拜。</p>
<p>某天，老师在课上讲二项分布的题目：</p>
<pre><code>(2010天津,18改)
某射手每次射击击中目标的概率p=1/3, 且各次射击的结果相互独立, 互不影响。
记4次中击中的次数为X, 求X的数学期望与期望的方差。
(答案：4/3，8/9)</code></pre>
<p>老师说：“这个，二项分布的期望就是 $np$，方差就是 $np(1-p)$，不信你们自己课后回去算。”</p>
<p>$\pi\text{+}e$ 一听有附加题，马上打起了精神，三下五除二用了他的黑科技“母函数求导”就轻而易举的解决了这个问题。顺便帮叶子也给科普了一下。</p>
<p>2016年暑假的某天，$\pi\text{+}e$ 突然想起了这件事。他想了想，把原来的问题加强了一下，变成下面这个样子：</p>
<p>有一个多项式函数 $f(x)$，最高次幂为 $x^m$，定义变换 $Q$：</p>
<p>$$Q(f,n,x) = \sum_{k = 0}^{n}f(k){n\choose k}x^k(1 - x) ^{n - k}$$</p>
<p>现在给定函数 $f$ 和 $n,x$，求 $Q(f,n,x)\bmod 998244353$。</p>
<p>然而，众所周知，高考考完是会掉很多智商的。$\pi\text{+}e$ 发现自己已经忘记掉怎么用的黑科技了；他打电话给叶子，叶子也说不记得了。</p>
<p>你能帮帮他吗？</p>
<p>出于某种原因，函数 $f$ 由点值形式给出，即给定 $a_0,a_1,\cdots,a_m$ 共 $m+1$ 个数，$f(x)=a_x$。可以证明该函数唯一。</p>

# 输入格式


<p>第一行三个整数 $n,m,x$，意义如前所述。</p>
<p>第二行共 $m+1$ 个整数，表示 $a_0,a_1,\cdots,a_m$。</p>

# 输出格式


<p>输出一行一个数表示答案，请对 $998,244,353$ 取模。</p>

# 样例一


<h4>input</h4>
<pre>4 1 332748118
0 1

</pre>

<h4>output</h4>
<pre>332748119

</pre>

<h4>explanation</h4>
<p>注意到 $332748118 \equiv \frac{1}{3} \pmod{ 998244353 }$, $332748119 \equiv \frac{4}{3} \pmod{ 998244353 }$, $f(x)=x$, 题目中所求的表达式为：</p>
<p>$$\sum_{k=0}^4 k{4\choose k}\left(\frac{1}{3}\right)^k\left(\frac{2}{3}\right)^{4-k}=\frac{4}{3}$$</p>
<p>此即为题目开头二项分布例题计算期望的表达式。</p>

# 样例二


<h4>input</h4>
<pre>4 3 12
0 1 8 27

</pre>


<h4>output</h4>
<pre>46704

</pre>

<h4>explanation</h4>
<p>经计算可得 $f(x)=x^3$</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有的测试点，保证 $1 \le n \le 10^{9},\ 1 \le m \le 2 \times 10^{4},\ 0\le a_i,x&lt; 998,244,353$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$n \le$</th><th rowspan="1">$m \le$</th><th rowspan="1">特殊限制</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$10^{2}$</td><td rowspan="1">$10^{2}$</td><td rowspan="2">$n=m$</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$10^{3}$</td><td rowspan="1">$10^{3}$</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$10^{4}$</td><td rowspan="3">$10^{2}$</td><td rowspan="4">无约束</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$10^{5}$</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$10^{6}$</td></tr><tr><td rowspan="1">6</td><td rowspan="12">$10^{9}$</td><td rowspan="1">$= 1$</td></tr><tr><td rowspan="1">7</td><td rowspan="2">$= 2$</td><td rowspan="1">$f(x)=x^2$</td></tr><tr><td rowspan="1">8</td><td rowspan="1">$f(x)=x^2-x$</td></tr><tr><td rowspan="1">9</td><td rowspan="1">$= 3$</td><td rowspan="10">无约束</td></tr><tr><td rowspan="1">10,11</td><td rowspan="1">$10$</td></tr><tr><td rowspan="1">12,13,14</td><td rowspan="1">$10^{2}$</td></tr><tr><td rowspan="1">15</td><td rowspan="1">$10^{3}$</td></tr><tr><td rowspan="1">16</td><td rowspan="1">$2,000$</td></tr><tr><td rowspan="1">17</td><td rowspan="1">$4,000$</td></tr><tr><td rowspan="1">18</td><td rowspan="1">$8,000$</td></tr><tr><td rowspan="1">19</td><td rowspan="1">$12,000$</td></tr><tr><td rowspan="1">20</td><td rowspan="1">$2 \times 10^{4}$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=269">样例数据下载</a></p>
