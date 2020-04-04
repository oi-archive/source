# 题目描述

<p>完成清扫银河计划带来的信心并不能让跳蚤们的航天科技突飞猛进，你看不到任何用现有的工质发动机技术完成环银河系航行的可能性。但这时，章北蚤向你展示了最新的通用测评号恒星级宇宙飞船 —— 它拥有最新一代的工质发动机，全功率推进时，理论上可以加速到光速的千分之五。</p>
<p>为了实验通用测评号的实际效果，你被安排给通用测评号装填燃料。通用测评号上有 $n$ 个燃料舱，初始时均为空。一个燃料舱被填满时可以储藏 $a$ 单位的燃料。但为了完成本次实验，只需要每个燃料舱装填至少 $b$ 单位的燃料即可。</p>
<p>装填燃料是个非常无聊的事情，因此你每次会等概率随机选一个<strong>没有满的燃料舱</strong>，并且在其中放入 $1$ 单位的燃料，直至所有燃料舱均包含至少 $b$ 单位的燃料。</p>
<p>但是由于设计上的失误，一个燃料舱被填满 $a$ 单位的燃料后，该燃料舱与发动机连接的管道由于压力过大会坏掉。章北蚤发现了这个问题，他想估计坏掉的管道数量，所以想请你算一算期望有多少个燃料舱被填满了。</p>
<p>为了避免实数计算带来的浮点误差，你只需要输出答案对 $998244353$ 取模后的结果。</p>

# 输入格式


<p>输入共一行，包含三个正整数 $n,a,b$，含义如前所述。</p>

# 输出格式


<p>输出共一行，包含一个整数，表示期望对 $998244353$ 取模后的值。即如果答案的最简分数表示为 $\frac{x}{y}(x \geq 0, y \geq 1, \gcd(x,y) = 1)$，你需要输出满足 $ay \equiv x \pmod{998244353}$ 的那个唯一的整数 $a$ 。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">2 2 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">499122177</code></pre>
<h4>explaination</h4>
<p>设在第一次操作中放入燃料的燃料舱为燃料舱1，剩下的为燃料舱2。</p>
<p>在第二次操作中有$\frac{1}{2}$的概率将燃料放入燃料舱2，此时填充过程结束，满的燃料舱个数为$0$。</p>
<p>在第二次操作中有$\frac{1}{2}$的概率将燃料放入燃料舱1，此时第三次仅能将燃料放入燃料舱2，然后填充过程结束，满的燃料舱个数为$1$。</p>
<p>因此答案为$\frac{1}{2} \times 0+\frac{1}{2} \times 1=\frac{1}{2}$。对$998244353$取模后答案为$499122177$。</p>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">3 3 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">804141285</code></pre>
<h4>explaination</h4>
<p>答案为$\frac{23}{36}$。</p>

# 样例三和样例四


<p>见样例数据下载。</p>

# 数据范围


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$a$</th><th>特殊性质</th></tr></thead><tbody><tr><td>$1$</td> <td>$\le 5$</td>  <td>$\le 5$</td>  <td rowspan="3">无</td></tr><tr><td>$2$</td> <td>$\le 10$</td> <td>$\le 10$</td> </tr><tr><td>$3$</td> <td>$\le 30$</td> <td>$\le 30$</td> </tr><tr><td>$4$</td> <td>$\le 50$</td> <td>$\le 50$</td> <td>$b=1$</td></tr><tr><td>$5$</td> <td>$\le 50$</td> <td>$\le 50$</td> <td>无</td></tr><tr><td>$6$</td> <td>$\le 100$</td><td>$\le 100$</td><td>$b=1$</td></tr><tr><td>$7$</td> <td>$\le 100$</td><td>$\le 100$</td><td rowspan="4">无</td></tr><tr><td>$8$</td> <td>$\le 150$</td><td>$\le 150$</td></tr><tr><td>$9$</td> <td>$\le 200$</td><td>$\le 200$</td></tr><tr><td>$10$</td><td>$\le 250$</td><td>$\le 250$</td></tr></tbody></table></div>

<p>对于所有测试数据，满足 $1 \le n \le 250,1 \le b &lt; a \le 250$。</p>
<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=514">样例数据下载</a></p>
