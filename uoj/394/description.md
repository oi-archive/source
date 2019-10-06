# 题目描述

<p>最近，小S对冒泡排序产生了浓厚的兴趣。为了问题简单，小 S 只研究对 <strong>$1$ 到 $n$ 的排列</strong>的冒泡排序。</p>
<p>下面是对冒泡排序的算法描述。</p>
<pre><code class="sh_cpp">input：一个长度为 n 的排列 p[1...n]
output：p排序后的结果。
for i = 1 to n do
    for j = 1 to n - 1 do
        if(p[j] &gt; p[j + 1])
            交换 p[j] 与 p[j + 1] 的值</code></pre>
<p>冒泡排序的交换次数被定义为交换过程的执行次数。可以证明交换次数的一个下界是 $\frac{1}{2}\sum_{i=1}^{n}{|i-p_i|}$，其中$p_i$ 是排列 $p$ 中第 $i$ 个位置的数字。如果你对证明感兴趣，可以看提示。</p>

# 题目描述


<p>小S开始专注于研究长度为 $n$ 的排列中，满足 交换次数$=\frac{1}{2}\sum_{i=1}^{n}{|i-p_i|}$ 的排列（在后文中，为了方便，我们把所有这样的排列叫“好”的排列）。他进一步想，这样的排列到底多不多？它们分布的密不密集？</p>
<p>小S想要对于一个给定的长度为 $n$ 的排列 $q$，计算字典序严格大于 $q$ 的“好”的排列个数。但是他不会做，于是求助于你，希望你帮他解决这个问题，考虑到答案可能会很大，因此只需输出答案对 $998244353$ 取模的结果。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入第一行包含一个正整数 $T$，表示数据组数。</p>
<p>对于每组数据，第一行有一个正整数 $n$, 保证 $n \le 6 \times 10^{5}$。</p>
<p>接下来一行会输入 $n$ 个正整数，对应于题目描述中的 $q_i$，保证输入的是一个$1$ 到 $n$ 的排列。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出共 $T$ 行，每行一个整数。</p>
<p>对于每组数据，输出一个整数，表示字典序严格大于 $q$ 的“好”的排列个数对 998244353 取模的结果。</p>

# 样例一


<h4>input</h4>
<pre>1
3
1 3 2
</pre>



<h4>output</h4>
<pre>3
</pre>

<h4>解释</h4>
<p>字典序比 $1~~3~~2$ 大的排列中，除了 $3~~2~~1$ 以外都是“好”的排列，故答案为 3。</p>

# 样例二


<h4>input</h4>
<pre>1
4
1 4 2 3
</pre>



<h4>output</h4>
<pre>9
</pre>





# 样例三


<p>见<a href="/download.php?type=problem&amp;id=394">下载目录</a>下的 <em>ex_3.in</em> 与 <em>ex_3.ans</em>。</p>

# 子任务


<p>下面是对本题每个测试点的input规模的说明。</p>
<p>对于所有数据，均满足 $T = 5$ (样例可能不满足). </p>
<p>记 $n_{max}$ 表示每组数据中 $n$ 的最大值，$\sum{n}$ 表示所有数据的 $n$ 的和。</p>
<div class="table-responsive"><table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$n_{max}=$</th><th rowspan="1">$\sum n\leq$</th><th rowspan="1">特殊性质</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$8$</td><td rowspan="11">$5n_{max}$</td><td rowspan="11">$\text{无}$</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$9$</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$10$</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$12$</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$13$</td></tr><tr><td rowspan="1">6</td><td rowspan="1">$14$</td></tr><tr><td rowspan="1">7</td><td rowspan="2">$16$</td></tr><tr><td rowspan="1">8</td></tr><tr><td rowspan="1">9</td><td rowspan="1">$17$</td></tr><tr><td rowspan="1">10</td><td rowspan="2">$18$</td></tr><tr><td rowspan="1">11</td></tr><tr><td rowspan="1">12</td><td rowspan="1">$122$</td><td rowspan="5">$700$</td><td rowspan="1">$\forall i ~~p_i=i$</td></tr><tr><td rowspan="1">13</td><td rowspan="1">$144$</td><td rowspan="4">$\text{无}$</td></tr><tr><td rowspan="1">14</td><td rowspan="1">$166$</td></tr><tr><td rowspan="1">15</td><td rowspan="1">$200$</td></tr><tr><td rowspan="1">16</td><td rowspan="1">$233$</td></tr><tr><td rowspan="1">17</td><td rowspan="1">$777$</td><td rowspan="4">$4000$</td><td rowspan="1">$\forall i ~~p_i=i$</td></tr><tr><td rowspan="1">18</td><td rowspan="1">$888$</td><td rowspan="3">$\text{无}$</td></tr><tr><td rowspan="1">19</td><td rowspan="1">$933$</td></tr><tr><td rowspan="1">20</td><td rowspan="1">$1000$</td></tr><tr><td rowspan="1">21</td><td rowspan="1">$266666$</td><td rowspan="5">$2000000$</td><td rowspan="1">$\forall i ~~p_i=i$</td></tr><tr><td rowspan="1">22</td><td rowspan="1">$333333$</td><td rowspan="4">$\text{无}$</td></tr><tr><td rowspan="1">23</td><td rowspan="1">$444444$</td></tr><tr><td rowspan="1">24</td><td rowspan="1">$555555$</td></tr><tr><td rowspan="1">25</td><td rowspan="1">$600000$</td></tr></tbody></table></div> 

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 提示


<p>下面是对交换次数下界是 $\frac{1}{2}\sum_{i=1}^{n}{|i-p_i|}$ 的证明。</p>
<p>排序本质上就是数字的移动，因此排序的交换次数应当可以用数字移动的总距离来描述。对于第 $i$ 个位置，假设在初始排列中，这个位置上的数字是 $p_i$，那么我们需要将这个数字移动到第 $p_i$ 个位置上，移动的距离是 $|i - p_i|$。从而移动的总距离就是 $\sum_{i=1}^n |i - p_i|$，而冒泡排序每次会交换两个相邻的数字，每次交换可以使移动的总距离至多减少 2。因此 $\frac{1}{2}{\sum_{i=1}^{n}{|i-p_i|}}$ 是冒泡排序的交换次数的下界。</p>
<p>并不是所有的排列都达到了下界，比如在 $n=3$ 的时候，考虑排列 $3 ~~ 2~~1$, 这个排列进行冒泡排序以后的交换次数是 3，但是 $\frac{1}{2}\sum_{i=1}^{n}{|i-p_i|}$ 只有 2。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=394">样例数据下载</a></p>
