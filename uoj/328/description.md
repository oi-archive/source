# 题目描述

<p>Scape下载了好久终于下完了关于量子巧克力的游戏——Quantum break，准备邀请Mythological来享受在一起的时光。可是谁知道积劳成疾的Scape，居然在Mythological到来之前就陷入了梦境之中。</p>
<p>Scape在梦境中隐隐约约看见了这样的一份题面：</p>
<p>Mythological应邀来和他一起隔膜，并且带来了一盒与游戏中同款的 ”黎明前就会破碎的量子巧克力“。</p>
<p>在游戏里量子巧克力可以看做一个数组 $a$，长度为 $2^n$，下标从 $0$ 开始到 $2^n-1$ 结束。</p>
<p>他们俩可以关于这些量子巧克力，向游戏做一些询问，但是不幸有的询问会导致量子破碎，此时游戏会刷新这个数组开始新的一轮....</p>
<p>即使是在梦中，Scape也想让Mythological开心，请你帮一帮他。</p>

# 任务


<p>每轮游戏开始的时候数组里只有 $a[x]=a[y]=\frac{1}{\sqrt{2}}$（$x \ne y$），剩下的元素都是 $0$。</p>
<p>你需要编写一个函数和交互库进行多轮交互，求出 $x \oplus y$ 的值（每轮中 $x \oplus y$ 不变）:</p>
<ul><li>query_xor(n, t);<ul><li>n 表示 a 的长度是 $2^n$，t 表示子任务编号。</li>
<li>你的返回值是 $x \oplus y$ 的答案。</li>
</ul></li>
</ul><p>你可以通过四种操作来确定这个值:</p>
<ul><li>query();<ul><li>向交互库做一次询问。</li>
<li>交互库会随机返回一个下标，具体来说返回 $x$ 的概率恰好是 $\frac{a[x]^2}{\sum_i a[i]^2}$。</li>
<li>返回 $x$ 之后，会开始新的一轮，交互库重新随机一对 $x$ 和 $y$ 保证 $x \oplus y$ 不变（在所有满足条件的 $x,y$ 中等概率随机，有可能不变），然后重新给数组 $a$ 赋值，使得数组里只有 $a[x]=a[y]=\frac{1}{\sqrt{2}}$（$x \ne y$），剩下的元素都是 $0$。</li>
</ul></li>
<li>manipulate(A, i);<ul><li>向交互库做一次操作，给出一个 $2 \times 2$ 的实数矩阵 $A$。</li>
<li>交互库会把数组 $a$ 更新，具体来说，对于每个二进制第 $i$（$i$ 是传入的参数）位为 $0$ 的数 $x$，令$$\begin{cases}a&#39;[x] = A[0][0]\cdot a[x] + A[1][0]\cdot a[x+2^i],\\a&#39;[x+2^i] = A[0][1]\cdot a[x] + A[1][1]\cdot a[x+2^i],\end{cases}$$则 $a[x]$ 将更新为 $a&#39;[x]$，$a[x+2^i]$ 将更新为 $a&#39;[x+2^i]$。</li>
<li>为了保证 $a[x]^2$ 的和 (概率和) 始终为1，你的矩阵必须满足 $AA^T=I$，可以证明此时 $a[x]^2$ 的和始终不变（$A^T$ 表示 $A$ 的转置，$I$ 为单位矩阵）。</li>
</ul></li>
<li>arbitary_manipulate(A, i);<ul><li>和 manipulate 不同的是，这里不强制 $AA^T=I$。</li>
<li>使用了这个函数后，$\sum a[x]^2$ 可能不为 $1$，询问的时候概率按照 $a[x]^2$ 的比例平均分配。</li>
<li>如果 $\sum a[x]^2 = 0$，交互库会返回 0。（请选手使用下发的 grader 判断自己程序的精度问题）</li>
</ul></li>
<li>arbitary_query(x);<ul><li>询问 a[x] 为多少。</li>
<li>和 query 不同，不会导致数组清空开始新的一轮。</li>
</ul></li>
</ul>
# 实现细节


<p>本题只支持 C/C++。</p>
<p>你只能提交一个源文件实现如上所述的 query_xor 函数，并且遵循下面的命名和接口。你需要包含头文件 quantumbreak.h。</p>
<pre><code class="sh_cpp">int query_xor(int n, int t);</code></pre>
<p>函数 query, manipulate, arbitary_manipulate, arbitary_query 的接口信息如下。</p>
<pre><code class="sh_cpp">int query();
void manipulate(double A[][2], int i);
void arbitary_manipulate(double A[][2], int i);
double arbitary_query(int x);</code></pre>
<p>如果有不清楚的地方，见样例及测评库下载，<strong>内附了样例程序，样例程序按照样例一的解释调用函数</strong>。</p>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<p>第一行三个整数 $n$，$seed$，$t$ 分别是这组测试数据的大小、随机种子和子任务编号。</p>
<p>第二行四个整数 $ok[1], ok[2], ok[3], ok[4]$，$ok[i] = 0$ 表示函数 $i$ 在这个子任务不可使用，$ok[i] = 1$ 表示可以使用。</p>

# 限制与约定


<p>一共五个子任务，每个子任务有对应的分数。</p>
<p>每个子任务都有对应的可以使用的函数，使用了不可使用的函数会失去这个子任务的分数。</p>
<p>为了拿到每个子任务的分数，你必须通过所有他依赖的子任务。</p>
<p>所有的子任务中都不能使用超过 $400$ 个操作。</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>$n$ 的规模</th><th>可以使用的函数</th><th>依赖的子任务</th></tr></thead><tbody><tr><td>1</td><td>5</td><td>$n = 8$</td><td>1, 2, 3, 4</td><td></td></tr><tr><td>2</td><td>15</td><td>$n = 16$</td><td>1, 2, 3, 4</td><td>1</td></tr><tr><td>3</td><td>20</td><td>$n = 16$</td><td>1, 2, 3</td><td>1, 2</td></tr><tr><td>4</td><td>20</td><td>$n = 16$</td><td>1, 2, 4</td><td>1, 2</td></tr><tr><td>5</td><td>20</td><td>$n = 6$</td><td>1, 2</td><td></td></tr><tr><td>6</td><td>20</td><td>$n = 16$</td><td>1, 2</td><td>1, 2, 3, 4, 5</td></tr></tbody></table></div>

<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=328">样例数据下载</a></p>
