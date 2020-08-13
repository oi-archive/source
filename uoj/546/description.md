# 题目描述

<p>黑板上写有 $n$ 个互不相等且都小于 $p$ 的正整数 $a_1, a_2, \cdots, a_n$。小 J 想用这些数字和小 M 玩一个猜数游戏。</p>
<p>游戏规则十分简单：游戏开始时，小 J 会从这些数字中随机选择若干个让小 M 来猜，而小 M 则可以通过若干次询问来确定小 J 选择了哪些数字。</p>
<p>每一次询问的模式如下：小 M 可以任意指定一个数字 $a_k$，若它是小 J 所选择的数字之一，则小 J 会告诉小 M 他所选择的数字中所有能表示成 $(a_k)^m \bmod p$ 的数，其中 $m$ 是任意正整数，$\bmod$ 表示求二者做带余除法后的余数。反之，若 $a_k$ 没有被小 J 选中，则小 J 只会告诉小 M $a_k$ 没有被选中。</p>
<p>游戏会在小 M 确定小 J 所选中的所有数字后立刻结束。</p>
<p>例如，若 $n=4,p=7$，数字 $\{a_n\}$ 按下标顺序依次为 $\{1, 3, 4, 6\}$，小 J 选定的数字为 $\{1, 4, 6\}$，一种可能的游戏进行的过程（并非是最优过程）如下：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>小 M 的询问</th><th>小 J 的反馈</th></tr></thead><tbody><tr><td>$a_2=3$</td><td>$a_2$未选中</td></tr><tr><td>$a_4=6$</td><td>$a_1=1,a_4=6$</td></tr><tr><td>$a_3=4$</td><td>$a_1=1,a_3=4$</td></tr></tbody></table></div>

<p>3 次询问后小 J 所选出的所有数都已被小 M 确定，游戏结束。</p>
<p>小 M 还有作业没有写完，因此他需要对游戏进行的时间进行评估。他想知道为了使游戏结束，他所需要做出询问的最小次数的期望 $S$ 是多少。</p>
<p>为了避免精度误差，你需要输出答案乘 $(2^n - 1)$ 后模 $998244353$ 的余数。在本题中，你可以认为小 J 每次在选数时会在集合 $\{a_1, a_2, \cdots, a_n\}$ 的全部非空子集中等概率地选择一个，在这个前提下可以证明 $(2^n - 1) \times S$ 一定是一个整数。</p>

# 输入格式


<p>第一行两个正整数 $n$ 和 $p$。</p>
<p>第二行 $n$ 个正整数，依次表示 $a_1, a_2, \cdots, a_n$。</p>

# 输出格式


<p>仅一行一个整数表示答案。</p>

# 样例1


<h4>input</h4>
<pre><code class="sh_plain">4 7
1 3 4 6</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">17</code></pre>
<h4>explanation</h4>
<p>下表给出了小 J 所选的子集与小 M 最小询问次数的关系：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>小 J 所选的子集</th><th>最优的询问集合</th></tr></thead><tbody><tr><td>$\{1\}$</td><td>$\{1\}$</td></tr><tr><td>$\{3\},\{3,4\},\{3,6\},\{3,4,6\},\{3,1\},\{3,1,4\},\{3,1,6\},\{3,1,4,6\}$</td><td>$\{3\}$</td></tr><tr><td>$\{4\},\{1,4\}$</td><td>$\{4\}$</td></tr><tr><td>$\{6\},\{1,6\}$</td><td>$\{6\}$</td></tr><tr><td>$\{4,6\},\{1,4,6\}$</td><td>$\{4,6\}$</td></tr></tbody></table></div>

<p>因此最小询问次数的期望 $S = \frac{17}{15}$。</p>

# 样例2


<h4>input</h4>
<pre><code class="sh_plain">8 9
1 2 3 4 5 6 7 8</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">532</code></pre>

# 样例3


<p>见附加文件。</p>

# 数据范围


<p>对于所有测试点：$1 \leq n \leq 5000$，$3 \leq p \leq 10^8$ ，$1 \leq a_i &lt; p\ (1 \leq i \leq n)$且 $a_i$ 两两不同。</p>
<p>对于所有编号为奇数的测试点，保证 $p$ 是一个素数；对于所有编号为偶数的测试点，保证存在奇素数 $q$ 和正整数 $k &gt; 1$ 使得 $p = q^k$</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n \le$</th><th>$p \le$</th><th>特殊限制</th><th>测试点编号</th><th>$n \le$</th><th>$p \le$</th><th>特殊限制</th></tr></thead><tbody><tr><td>$1$</td><td rowspan="2">$10$</td><td rowspan="2">$100$</td><td rowspan="4">$无$</td><td>$2$</td><td rowspan="2">$10$</td><td rowspan="2">$100$</td><td rowspan="4">$无$</td></tr><tr><td>$3$</td><td>$4$</td></tr><tr><td>$5$</td><td>$200$</td><td>$5000$</td><td>$6$</td><td>$200$</td><td>$5000$</td></tr><tr><td>$7$</td><td rowspan="2">$300$</td><td rowspan="2">$10^6$</td><td>$8$</td><td rowspan="2">$300$</td><td rowspan="2">$10^6$</td></tr><tr><td>$9$</td><td rowspan="2">$A$</td><td>$10$</td><td>$B$</td></tr><tr><td>$11$</td><td rowspan="5">$5000$</td><td rowspan="2">$10^7$</td><td>$12$</td><td rowspan="5">$5000$</td><td rowspan="2">$10^7$</td><td rowspan="2">$无$</td></tr><tr><td>$13$</td><td>$无$</td><td>$14$</td></tr><tr><td>$15$</td><td rowspan="3">$10^8$</td><td>$A$</td><td>$16$</td><td rowspan="3">$10^8$</td><td>$B$</td></tr><tr><td>$17$</td><td rowspan="2">$无$</td><td>$18$</td><td rowspan="2">$无$</td></tr><tr><td>$19$</td><td>$20$</td></tr></tbody></table></div>

<p>特殊性质 $A$：在模 $p$ 意义下 $3^i\ (1 \leq i \leq p - 1)$两两不同余。</p>
<p>特殊性质 $B$：对所有的 $1 \leq i \leq n$ 都有 $(a_i, p) &gt; 1$。</p>
<p><strong>时间限制:</strong> $2\texttt{s}$</p>
<p><strong>空间限制:</strong> $128\texttt{MB}$</p>
<p><a href="http://uoj.ac/download.php?type=problem&amp;id=546">附加文件</a></p>
