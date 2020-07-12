# 题目描述

<p>2048年，第三十届 CSP 认证的考场上，作为选手的小明打开了第一题。这个题的样例有$n$组数据，数据从$1 \sim n$标号，$i$号数据的规模为$a_i$。</p>
<p>小明对该题设计出了一个暴力程序，对于一组规模为$u$的数据，该程序的<strong>运行时间</strong>为$u^2$。然而这个程序运行完一组规模为$u$的数据之后，它将在任何一组规模<strong>小于</strong>$u$的数据上运行错误。样例中的$a_i$不一定递增，但小明又想在不修改程序的情况下正确运行样例，于是小明决定使用一种非常原始的解决方案：将所有数据划分成若干个数据段，段内编号连续，接着将同一段内的数据合并成新数据，其规模等于段内原数据的<strong>规模之和</strong>，小明将让新数据的规模能够递增。</p>
<p>也就是说，小明需要找到一些分界点$1 \leq k_1 &lt; k_2 &lt; \cdots &lt; k_p &lt; n$，使得</p>
<p>$$\sum\limits_{i=1}^{k_1}a_i \leq \sum\limits_{i=k_1+1}^{k_2}a_i \leq  \cdots \leq \sum\limits_{i=k_p+1}^{n}a_i$$</p>
<p>注意$p$可以为$0$且此时$k_0=0$，也就是小明可以将所有数据合并在一起运行。</p>
<p>小明希望他的程序可以在正确运行样例情况下， 运行时间也能尽量小，也就是<strong>最小化</strong></p>
<p>$$(\sum\limits_{i=1}^{k_1}a_i)^2+(\sum\limits_{i=k_1+1}^{k_2}a_i)^2+\cdots+(\sum\limits_{i=k_p+1}^{n}a_i)^2$$</p>
<p>小明觉得这个问题非常有趣，并向你请教：给定$n$和$a_i$，请你求出最优划分方案下，小明的程序的运行时间。</p>

# 输入格式


<p><strong>由于本题的数据范围较大，部分测试点的</strong>$a_i$<strong>将在程序内生成。</strong></p>
<p>第一行两个整数$n,type$。$n$的意义见题目描述，$type$表示输入方式。</p>
<ol><li>若$type=0$，则该测试点的$a_i$<strong>直接给出</strong>。输入文件接下来：第二行$n$个以空格分隔的整数$a_i$，表示每组数据的规模。</li>
<li>若$type=1$，则该测试点的$a_i$将<strong>特殊生成</strong>，生成方式见后文。输入文件接下来：第二行六个以空格分隔的整数$x,y,z,b_1,b_2,m$。接下来$m$行中，第 $i(1 \leq i \leq m)$ 行包含三个以空格分隔的正整数$p_i,l_i,r_i$。</li>
</ol><p>对于$type=1$的$23\sim 25$号测试点，$a_i$的生成方式如下：</p>
<p>给定整数$x,y,z,b_1,b_2,m$，以及$m$个三元组 $(p_i,l_i,r_i)$。</p>
<p>保证$n \geq 2$。若$n &gt; 2$，则 $\forall 3\leq i \leq n,b_i=(x\times b_{i-1} + y \times b_{i-2} + z) \bmod 2^{30}$。</p>
<p>保证$1 \leq p_i \leq n, p_m=n$。令$p_0=0$，则$p_i$还满足 $\forall 0 \leq i &lt; m$有$p_i &lt; p_{i+1}$。</p>
<p>对于所有$1 \leq j \leq m$，若下标值 $i (1 \leq i \leq n)$ 满足 $p_{j-1} &lt; i \leq p_j$，则有</p>
<p>$$a_i=(b_i \bmod (r_j-l_j+1)) + l_j$$</p>
<p><strong>上述数据生成方式仅是为了减少输入量大小，标准算法不依赖于该生成方式，</strong></p>

# 输出格式


<p>输出一行一个整数，表示答案。</p>

# 样例1


<h4>input</h4>
<pre><code class="sh_plain">5 0
5 1 7 9 9</code></pre>
<h4>output</h4>
<pre><code>247</code></pre>
<h4>explanation</h4>
<p>最优的划分方案为 $\{5, 1\},\{7\},\{9\},\{9\}$。由$5+1 \leq 7 \leq 9 \leq 9$知该方案合法。</p>
<p>答案为 $(5+1)^2+7^2+9^2+9^2=247$。</p>
<p>虽然划分方案  $\{5\},\{1\},\{7\},\{9\},\{9\}$ 对应的运行时间比 $247$小，但它不是一组合法方案，因为$5&gt;1$。</p>
<p>虽然划分方案 $\{5\},\{1,7\},\{9\},\{9\}$ 合法，但该方案对应的运行时间为$251$，比 $247$大。</p>

# 样例2


<h4>input</h4>
<pre><code class="sh_plain">10 0
5 6 7 7 4 6 2 13 19 9</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">1256</code></pre>
<h4>explanation</h4>
<p>最优的划分方案为 $\{5\},\{6\},\{7\},\{7\},\{4,6,2\},\{13\},\{19,9\}$。</p>

# 样例3


<h4>input</h4>
<pre><code class="sh_plain">10000000 1
123 456 789 12345 6789 3
2000000 123456789 987654321
7000000 234567891 876543219
10000000 456789123 567891234</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">4972194419293431240859891640</code></pre>

# 限制与约定


<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
    <th>$n \leq$</th>
    <th>$a_i \leq$<br/></th>
    <th>$type =$</th>
    </tr></thead><tbody><tr><td>$1 \sim 3$<br/></td>
    <td>$10$<br/></td>
    <td>$10$<br/></td>
    <td rowspan="5">$0$<br/></td>
  </tr><tr><td>$4 \sim 6$</td>
    <td>$50$<br/></td>
    <td>$10^3$<br/></td>
  </tr><tr><td>$7 \sim 9$</td>
    <td>$400$</td>
    <td>$10^4$</td>
  </tr><tr><td>$10 \sim 16$<br/></td>
    <td>$5000$</td>
    <td>$10^5$</td>
  </tr><tr><td>$17 \sim 22$</td>
    <td>$5 \times 10^5$</td>
    <td>$10^6$</td>
  </tr><tr><td>$23 \sim 25$</td>
    <td>$4 \times 10^7$</td>
    <td>$10^9$</td>
    <td>$1$<br/></td>
  </tr></tbody></table><p>对于所有测试数据满足$type \in {0,1},2 \leq n \leq 4 \times 10^7,1 \leq a_i \leq 10^9,1 \leq m \leq 10^5,1 \leq l_i \leq r_i \leq 10^9,0 \leq x,y,z,b_1,b_2 &lt; 2^{30}$</p>
<p>对于所有 $type=0$ 的测试点，保证最终答案不超过 $4 \times 10^{18}$。</p>
<p><strong>时间限制:</strong> $2\texttt{s}$</p>
<p><strong>空间限制:</strong> $1\texttt{GB}$</p>

# 关于Hack数据


<p>本题的hack数据对于$type = 0$需满足$2 \le n \le 500000$，对于$type = 1$需满足$2 \le n \le 40,000,000$。 ——matthew99</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=492">样例数据下载</a></p>
