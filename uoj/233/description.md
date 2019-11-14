# 题目描述

<p>Aizhan 有⼀个由 $N$ 个互不相同的整数组成的序列 $S[0], S[1], \ldots, S[N - 1]$，其中 $S[i]$ 取值范围是$[0, N - 1]$。Aizhan 试图通过交换某些元素对的⽅法将这个序列按照升序排序。Aizhan 的朋友 Ermek 也想交换某些元素对，Ermek 的交换未必有助于 Aizhan 的排序。</p>
<p>Ermek 和 Aizhan 打算通过若⼲轮次来修改这个序列。在每⼀轮，Ermek ⾸先做⼀次交换，然后 Aizhan 做另⼀次交换。更确切地说，做交换的⼈选择两个有效的下标并交换这两个下标的元素。请注意这两个下标可能相同。如果它们相等，则对这个元素⾃⾝做交换，并不改变这个序列。</p>
<p>Aizhan 知道 Ermek 并不关⼼对序列 $S$ 排序的事情。Aizhan 还知道 Ermek 将会选择哪些下标。Ermek 打算参加 $M$ 轮交换，将这些轮次从 $0$ 到 $M - 1$ 编号。对于 $0$ 到 $M - 1$ 之间的每个 $i$，Ermek 在第 $i$ 轮将选择下标 $X[i]$ 和 $Y[i]$ 的元素进⾏交换。</p>
<p>Aizhan 要对序列 $S$ 按升序进⾏排序。在每⼀轮之前，如果 Aizhan 看到当前的序列已经按升序排列，她将结束这个排序过程。给定初始序列 $S$ 以及 Ermek 要选择的下标，请你找出⼀个交换的序列，使得 Aizhan 能完成对序列 $S$ 的排序。此外，在有些⼦任务中，你还要找出尽可能短的交换序列来完成排序任务。题⽬保证通过 $M$ 或更少的轮次能够将序列 $S$ 排好序。</p>
<p>请注意如果 Aizhan 发现在 Ermek 的交换之后，序列 $S$ 已经排好序，则Aizhan可以选择交换两个相同下标（例如 $0$ 和 $0$）的元素。这样，序列 $S$ 在这⼀轮次之后也完成排序，于是也达到了 Aizhan 的⽬标。另外，如果初始序列 $S$ 就已经排好序，那么所需的最少排序轮数就是 $0$。</p>

# 样例一


<p>设：</p>
<ul><li>初始序列为 $S = 4, 3, 2, 1, 0$。</li>
<li>Ermek 打算做 $M = 6$ 轮交换。</li>
<li>Ermek打算选择的下标序列 $X$ 和 $Y$ 分别是 $X = 0, 1, 2, 3, 0, 1$ 和 $Y = 1, 2, 3, 4, 1, 2$。换句话说，Ermek 打算交换的下标对是 $(0, 1), (1, 2), (2, 3), (3, 4), (0, 1)$ 和 $(1, 2)$。</li>
</ul><p>按照上述设定，Aizhan 能够通过三轮排序，将序列 $S$ 排序为 $0, 1, 2, 3, 4$。这三轮排序所选择的下标分别是 $(0, 4), (1, 3)$ 和 $(3, 4)$。</p>
<p>下表给出了 Ermek 和 Aizhan 修改这个序列的过程。</p>
<div class="row">
<div class="col-sm-offset-4 col-sm-4">
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>轮次</th>
<th>操作者</th>
<th>交换的下标对</th>
<th>序列</th>
</tr></thead><tbody><tr><td>初态</td><td></td><td></td><td>$4, 3, 2, 1, 0$</td></tr><tr><td>0</td><td>Ermek</td><td>$(0, 1)$</td><td>$3, 4, 2, 1, 0$</td></tr><tr><td>0</td><td>Aizhan</td><td>$(0, 4)$</td><td>$0, 4, 2, 1, 3$</td></tr><tr><td>1</td><td>Ermek</td><td>$(1, 2)$</td><td>$0, 2, 4, 1, 3$</td></tr><tr><td>1</td><td>Aizhan</td><td>$(1, 3)$</td><td>$0, 1, 4, 2, 3$</td></tr><tr><td>2</td><td>Ermek</td><td>$(2, 3)$</td><td>$0, 1, 2, 4, 3$</td></tr><tr><td>2</td><td>Aizhan</td><td>$(3, 4)$</td><td>$0, 1, 2, 3, 4$</td></tr></tbody></table></div>
</div>
</div>


# 样例二


<p>设：</p>
<ul><li>初始序列为 $S = 3, 0, 4, 2, 1$。</li>
<li>Ermek 打算做 $M = 5$ 轮交换。</li>
<li>Ermek 打算交换的下标对是 $(1, 1), (4, 0), (2, 3), (1, 4)$ 和 $(0, 4)$。</li>
</ul><p>按照上述设定，Aizhan 能够通过三轮完成对序列 $S$ 的排序。例如可通过选择下标对 $(1, 4), (4, 2)$ 和 $(2, 2)$ 来实现。下表给出了 Ermek 和 Aizhan 修改这个序列的过程。</p>
<div class="row">
<div class="col-sm-offset-4 col-sm-4">
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>轮次</th>
<th>操作者</th>
<th>交换的下标对</th>
<th>序列</th>
</tr></thead><tbody><tr><td>初态</td><td></td><td></td><td>$3, 0, 4, 2, 1$</td></tr><tr><td>0</td><td>Ermek</td><td>$(1, 1)$</td><td>$3, 0, 4, 2, 1$</td></tr><tr><td>0</td><td>Aizhan</td><td>$(1, 4)$</td><td>$3, 1, 4, 2, 1$</td></tr><tr><td>1</td><td>Ermek</td><td>$(4, 0)$</td><td>$0, 1, 4, 2, 3$</td></tr><tr><td>1</td><td>Aizhan</td><td>$(4, 2)$</td><td>$0, 1, 3, 2, 4$</td></tr><tr><td>2</td><td>Ermek</td><td>$(2, 3)$</td><td>$0, 1, 2, 3, 4$</td></tr><tr><td>2</td><td>Aizhan</td><td>$(2, 2)$</td><td>$0, 1, 2, 3, 4$</td></tr></tbody></table></div>
</div>
</div>


# 任务


<p>给定序列 $S$、$M$ 和下标序列 $X$ 和 $Y$，请找出 Aizhan 对序列 $S$ 完成排序所需的交换的序列。在⼦任务 5-6 中，你找出的交换序列必须是最短的。</p>
<p>你需要实现函数 findSwapPairs：</p>
<ul><li>findSwapPairs(N, S, M, X, Y, P, Q) — grader调⽤这个函数刚好⼀次。<ul><li>N: 序列 $S$ 的⻓度.</li>
<li>S: ⼀个整数数组，表⽰初始序列 $S$。</li>
<li>M: Ermek 打算做交换的次数。</li>
<li>X, Y: ⻓度为 $M$ 的整数数组. 对于 $0\le i \le M - 1$, 在第 $i$ 轮 Ermek 打算交换下标为 $X[i]$ 和 $Y[i]$ 的数组。</li>
<li>P, Q: 整数数组。利⽤这两个数组报告 Aizhan 完成对序列 $S$ 排序的⼀种可能的交换序列，假设这个交换序列的⻓度为 $R$，对于 $0$ 到 $R$ 之间的每个 $R$，Aizhan在轮次 $i$ 选择的下标将被存⼊ $P[i]$ 和 $Q[i]$。 你可以假设数组 $P$ 和 $Q$ 均已分别被分配了 $M$ 个元素。<ul><li>这个函数应返回 $R$ 的值(定义如上)。</li>
</ul></li>
</ul></li>
</ul>
# 子任务


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>得分</th>
<th>$N$</th>
<th>$M$</th>
<th>$X, Y$ 的额外限制</th>
<th>对 $R$ 的要求</th>
</tr></thead><tbody><tr><td>1</td><td>8</td><td>$1 \leq N \leq 5$</td><td>$M = N^2$</td><td>$X[i] = Y[i] = 0$</td><td>$R \le M$</td></tr><tr><td>2</td><td>12</td><td>$1 \le N \le 100$</td><td>$M = 30N$</td><td>$X[i] = Y[i] = 0$</td><td>$R \le M$</td></tr><tr><td>3</td><td>16</td><td>$1 \leq N \leq 100$</td><td>$M = 30N$</td><td>$X[i] = 0, Y[i] = 1$</td><td>$R \le M$</td></tr><tr><td>4</td><td>18</td><td>$1 \leq N \leq 500$</td><td>$M = 30N$</td><td>无</td><td>$R \le M$</td></tr><tr><td>5</td><td>20</td><td>$1 \leq N \leq 2000$</td><td>$M = 3N$</td><td>无</td><td>最小</td></tr><tr><td>6</td><td>26</td><td>$1 \leq N \leq 200000$</td><td>$M = 3N$</td><td>无</td><td>最小</td></tr></tbody></table></div>

<p>数据保证存在⼀个仅需 $M$ 或更少轮次的交换序列来完成排序。</p>

# 实现细节


<p>你只能提交一个源文件实现如上所述的 findSwapPairs 函数，并且遵循下面的命名和接口。你需要包含头文件 sorting.h。</p>
<pre><code class="sh_cpp">int findSwapPairs(int N, int S[], int M, int X[], int Y[], int P[], int Q[]);</code></pre>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ul><li>第 $1$ 行：$N$</li>
<li>第 $2$ 行：$S[0] \ldots S[N-1]$</li>
<li>第 $3$ 行：$M$</li>
<li>第 $4，\ldots, M + 3$ 行：$X[i]\ Y[i]$</li>
</ul><p>评测系统将按下列格式输出：</p>
<ul><li>第 $1$ 行：findSwapPairs 函数的返回值 $R$</li>
<li>第 $2 + i(0 \le i &lt; R)$ 行：$P[i]\ Q[i]$</li>
</ul><p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$1500\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=233">样例及测评库下载</a></p>
