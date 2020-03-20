# 题目描述

<p>有 $N$ 个严格递增的非负整数 $a_1, a_2, \dots, a_N$（$0 \leq a_1 &lt; a_2 &lt; \cdots &lt; a_N \leq 10^{18}$）。你需要找出 $a_{i + 1} - a_i$（$0 \leq i \leq N - 1$）里的最大的值。</p>
<p>你的程序不能直接读入这个整数序列,但是你可以通过给定的函数来查询该序列的信息。关于查询函数的细节,请根据你所使用的语言,参考下面的实现细节部分。</p>
<p>你需要实现一个函数,该函数返回    $a_{i + 1} - a_i$（$0 \leq i \leq N - 1$）中的最大值。</p>

# 实现细节


<p>本题只支持 C/C++/Pascal。</p>
<h4>C/C++</h4>
<p>你需要包含头文件 gap.h。</p>
<p>你需要实现一个函数 findGap(T, N)，该函数接受下面的参数，并返回一个 <samp>long long</samp> 类型的整数：</p>
<ul><li>$T$：子任务的编号（$1$ 或者 $2$）</li>
<li>$N$：序列的长度</li>
</ul><p>你的函数 findGap 可以调用系统提供的查询函数 MinMax(s, t, &amp;mn, &amp;mx)，该函数的前两个参数 $s$ 和 $t$ 是 <samp>long long</samp> 类型的整数，后两个参数 &amp;mn 和 &amp;mx 是 <samp>long long</samp> 类型的整数的指针（mn 和 mx 是 <samp>long long</samp> 类型的整数）。当 MinMax(s, t, &amp;mn, &amp;mx) 返回时，变量 mn 将会存储满足 $a_i \in [s, t]$ 中 $a_i$ 的最小值，变量 mx 将会存储满足 $a_i \in [s, t]$，$a_i$ 的最大值。如果区间 $[s, t]$ 中没有序列中的数，则 mn 和 mx 都将存储 $-1$。在查询时需要满足 $s \leq t$，否则程序将会终止，该测试点计为 $0$ 分。</p>
<h4>Pascal</h4>
<p>你需要使用单元 graderhelperlib。</p>
<p>你需要实现一个函数 findGap(T, N)，该函数接受下面的参数，并返回一个 <samp>Int64</samp> 类型的整数：</p>
<ul><li>$T$：子任务的编号（$1$ 或者 $2$）（<samp>Integer</samp> 类型）</li>
<li>$N$：序列的长度（<samp>LongInt</samp> 类型）</li>
</ul><p>你的函数 findGap 可以调用系统提供的查询函数 MinMax(s, t, mn, mx)，该函数的前两个参数 $s$ 和 $t$ 是 <samp>Int64</samp> 类型的整数，后两个参数 mn 和 mx 是传引用方式的 <samp>Int64</samp> 类型的整数（过程内部对这两个变量的修改会影响到外部的对应变量的值）。当 MinMax(s, t, mn, mx) 执行完毕时，变量 mn 将会存储满足 $a_i \in [s, t]$ 中 $a_i$ 的最小值，变量 mx 将会存储满足 $a_i \in [s, t]$，$a_i$ 的最大值。如果区间 $[s, t]$ 中没有序列中的数，则 mn 和 mx 都将存储 $-1$。在查询时需要满足 $s \leq t$，否则程序将会终止，该测试点计为 $0$ 分。</p>

# 样例一


<h4>C/C++</h4>
<p>考虑 $N = 4, a_1 = 2, a_2 = 3, a_3 = 6, a_4 = 8$。</p>
<p>则答案应该是 $3$，可以通过下面的几组对 MinMax 的询问获得：</p>
<ul><li>调用 MinMax(1, 2, &amp;mn, &amp;mx)，则 mn 和 mx 皆返回 $2$。</li>
<li>调用 MinMax(3, 7, &amp;mn, &amp;mx)，则 mn 返回 $3$，mx 返回 $6$。</li>
<li>调用 MinMax(8, 9, &amp;mn, &amp;mx)，则 mn 和 mx 皆返回 $8$。</li>
</ul><h4>Pascal</h4>
<p>考虑 $N = 4, a_1 = 2, a_2 = 3, a_3 = 6, a_4 = 8$。</p>
<p>则答案应该是 $3$，可以通过下面的几组对 MinMax 的询问获得：</p>
<ul><li>调用 MinMax(1, 2, mn, mx)，则 mn 和 mx 皆返回 $2$。</li>
<li>调用 MinMax(3, 7, mn, mx)，则 mn 返回 $3$，mx 返回 $6$。</li>
<li>调用 MinMax(8, 9, mn, mx)，则 mn 和 mx 皆返回 $8$。</li>
</ul>
# 样例评测方式


<p>样例测评系统从标准输入中读入两行。第一行包含两个整数，子任务编号 $T$，和序列长度 $N$。第二行包含 $N$ 个严格递增的非负整数。然后该程序会向标准输出中写入两行，第一行为 findGap 的返回值，第二行为花费 $M$ 的值。</p>
<p>下面的输入描述了上面的样例：</p>
<pre>2 4
2 3 6 8

</pre>


# 限制与约定


<p>对于所有的测试点，有 $2 \leq N \leq 100000$。</p>
<p>每一个测试点开始测试之前，$M$ 都将被初始化为 $0$。</p>
<p>子任务 1（30 分）：每一次调用 MinMax 都将使 $M$ 加 $1$。为了获得所有分数，需要满足对于该子任务下的所有测试点，都有 $M \leq \frac{N + 1}{2}$。</p>
<p>子任务 2（70 分）：定义 $k$ 为调用 MinMax 时，区间 $[s, t]$ 中的序列中数的数量。每次调用 MinMax，将使 $M$ 加上 $k + 1$。对于每一个测试点，如果 $M \leq 3N$，你将得到 70 分，否则将得到 $\frac{60}{\sqrt{M/N + 1} - 1}$ 分。你的该子任务的得分是其下所有测试点中的最低分。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=206">样例及测评库下载</a></p>
