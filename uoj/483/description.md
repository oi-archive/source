# 题目描述

<p><strong>这是一道交互题。</strong></p>
<p>时隔半年，I 君的商店终于开不下去了，他决定转让商店，做一名探险家去探索未知的广阔世界。</p>
<p>根据古书记载，他在一个大荒漠的腹地找到了未知文明创造的地下宫殿，宫殿由 $N$ 个大型洞穴和 $M$ 条连接这些洞穴的双向通路构成。I 君能借助古书分辨所处的洞穴，但书中并没有记录 $M$ 条通路的连接结构，因此他难以搜寻传说中藏在宫殿里的无尽财宝。</p>
<p>不过现在 I 君发现了一个神秘机关，通过它可以获知宫殿的信息，I 君决定利用这个机关来得到宫殿的连接结构，请你来协助他。</p>

# 题目描述


<p>地下宫殿可以抽象成一张 $N$ 个点、$M$ 条边的<strong>无向简单图</strong>（简单图满足任意两点之间至多存在一条直接相连的边），洞穴从 $0 \sim n − 1$ 编号。目前你<strong>并不知道</strong>边有哪些。</p>
<p>每个洞穴都拥有一个光源，光源有开启、关闭两种状态，只有当光源处于开启状态时它所在的洞穴才会被照亮。初始时所有的光源都处于<strong>关闭</strong>状态，而光源的状态只能用 I 君发现的神秘机关改变。更具体的，使用神秘机关可以进行如下四种操作：</p>
<ol><li>向机关给定一个编号 $x$，机关将会<strong>改变</strong> $x$ 号洞穴，以及<strong>与 $x$ 号洞穴有通路直接相连的洞穴</strong>的光源状态。即原来开启的光源将会关闭；原来关闭的光源将会开启。</li>
<li>向机关给定一个编号 $x$，机关将会显示<strong>当前</strong> $x$ 号洞穴光源的状态。</li>
<li>向机关给定两个编号 $x, y$，表示你确定有一条连接 $x$ 号洞穴与 $y$ 号洞穴的通路，并让机关记录。</li>
<li>向机关给定一个编号 $x$，机关将会判断与 $x$ 号洞穴相连的通路是否<strong>都已被记录</strong>。</li>
</ol><p>机关在完成上一次操作后才能进行下一次操作。机关不能随意使用，因此每种操作的使用次数都有限制，分别为 $L_m, L_q, M, L_c$。你的任务是，编写一个程序，帮助 I 君决定如何合理利用神秘机关，从而正确地找到这 $M$ 条通路。</p>

# 实现细节


<p>你不需要，也不应该实现主函数，<strong>你只需要</strong>实现函数 $\texttt{explore(N, M)}$，这里的 $\texttt{N}$ 和 $\texttt{M}$ 分别表示洞穴和通路的个数。你可以通过调用</p>
<p>如下四个函数来和交互库进行交互：</p>
<ol><li>$\texttt{modify(x)}$<ul><li>这个函数可以令机关执行操作 $1$，给定的编号为 $x$。</li>
<li>你需要保证 $0 \le x &lt; N$，这个函数没有返回值。</li>
</ul></li>
<li>$\texttt{query(x)}$<ul><li>这个函数可以令机关执行操作 $2$，给定的编号为 $x$。</li>
<li>你需要保证 $0 \le x &lt; N$，这个函数返回 $0$ 或 $1$，表示目前 $x$ 号洞穴的光源为关闭（$0$ 表示）或开启（$1$ 表示）状态。</li>
</ul></li>
<li>$\texttt{report(x, y)}$<ul><li>这个函数可以令机关执行操作 $3$，给定的编号为 $x, y$。</li>
<li>你需要保证 $0 \le x, y &lt; N$ 且 $x \neq y$，这个函数没有返回值。</li>
</ul></li>
<li>$\texttt{check(x)}$<ul><li>这个函数可以令机关执行操作 $4$，给定的编号为 $x$。</li>
<li>你需要保证 $0 \le x &lt; N$，这个函数返回 $0$ 或 $1$，其中返回 $1$ 当且仅当与 $x$ 号洞穴相连的所有通路都已通过操作 $3$ 被记录。</li>
</ul></li>
</ol><p>评测时，交互库会<strong>恰好</strong>调用 $\texttt{explore}$ 一次。</p>
<p><strong>本题保证所使用的图在交互开始之前已经完全确定，不会根据和你的程序的交互过程动态构造，因此题目中的交互操作都是确定性的，你不需要关心这些操作在交互库中的具体实现。</strong></p>
<p><strong>数据保证在调用次数限制下，交互库运行所需的时间不超过 1s；交互库使用的内存大小固定，且不超过 128MB。</strong></p>

# 实现方法


<p>附加文件中已经提供了一个 <code>template_explore.cpp/c/pas</code>，请将这个文件拷贝一份，重命名为 <code>explore.cpp/c/pas</code>，然后在其基础上答题。</p>
<ol><li>对 C++ / C 语言选手<ul><li>请确保你的程序开头有 <code>#include &#34;explore.h&#34;</code>。</li>
<li>你需要实现的函数 $\texttt{explore}$ 的接口信息如下：<ul><li>$\texttt{void explore(int N, int M);}$</li>
</ul></li>
<li>你可以调用的交互函数的接口如下：<ul><li>$\texttt{void modify(int x);}$</li>
<li>$\texttt{int query(int x);}$</li>
<li>$\texttt{void report(int x, int y);}$</li>
<li>$\texttt{int check(int x);}$</li>
</ul></li>
</ul></li>
<li>对 Pascal 语言选手<ul><li>注意：<strong>Pascal 的代码中实现接口的语法较为复杂，请选手直接在下发的 <code>template_explore.pas</code> 的基础上进行答题，而不是自己从头实现代码。</strong></li>
<li>你需要实现的函数 $\texttt{explore}$ 的接口信息如下：<ul><li>$\texttt{procedure _explore(N, M : longint);}$</li>
<li>注意：<strong>这里的函数名称是</strong> $\texttt{_explore}$ <strong>而非</strong> $\texttt{explore}$，<strong>如果使用</strong> $\texttt{explore}$ <strong>将导致编译失败。</strong></li>
</ul></li>
<li>你可以调用的交互函数的接口如下：<ul><li>$\texttt{procedure modify(x : longint);}$</li>
<li>$\texttt{function query(x : longint) : longint;}$</li>
<li>$\texttt{procedure report(x : longint; y : longint);}$</li>
<li>$\texttt{function check(x : longint) : longint;}$</li>
</ul></li>
</ul></li>
</ol>
# 测试程序方式


<p><strong>试题目录下的 <code>grader.cpp/c</code> 以及 <code>graderhelperlib.pas</code> 是我们提供的交互库参考实现，最终测试时所用的交互库实现与该参考实现有所不同，因此选手的解法不应该依赖交互库实现。</strong></p>
<ol><li>对 C/C++ 语言的选手：<ul><li>你需要在本题目录下使用如下命令编译得到可执行程序：<ul><li>对于 C 语言：<code>gcc grader.c explore.c -o explore -O2 -lm</code></li>
<li>对于 C++ 语言：<code>g++ grader.cpp explore.cpp -o explore -O2 -lm</code></li>
</ul></li>
</ul></li>
<li>对 Pascal 语言选手：<ul><li>你需要在本题目录下使用如下命令编译得到可执行程序：<ul><li><code>fpc grader.pas -o&#34;explore&#34; -O2</code></li>
</ul></li>
</ul></li>
<li>对于编译得到的可执行程序：<ul><li>可执行文件将从<strong>标准输入</strong>读入以下格式的数据：<ul><li>第一行包含三个整数 $L_m, L_q, L_c$，第二行包含两个整数 $N, M$，意义如题面描述。</li>
<li>接下来 $M$ 行，每行两个整数 $x, y$，描述一条连接 $x$ 号洞穴与 $y$ 号洞穴的通路。</li>
</ul></li>
<li>读入完成之后，交互库将调用恰好一次函数 $\texttt{explore}$，用输入的数据测试你的函数。你的函数正确返回后，交互库会判断你的计算是否正确，若正确则会输出 <code>Correct</code> 和交互函数调用次数相关信息，否则会输出相应的错误信息。</li>
</ul></li>
</ol><p>假设可执行文件读入的数据为：</p>
<pre><code class="sh_plain">100 200 300
3 2
0 1
1 2</code></pre>
<p>数据第一行的三个整数分别表示三种操作的调用次数限制，即 $\texttt{modify(x)}$ 调用次数不能超过 $100$，$\texttt{query(x)}$ 调用次数不能超过 $200$，$\texttt{check(x)}$ 调用次数不能超过 $300$。</p>
<p>数据第二行的两个整数分别表示洞穴数和通路条数，即 $N = 3 , M = 2$。</p>
<p>$\texttt{report(x, y)}$ 调用次数不能超过 $M$，该例子中即不超过 $2$ 次。</p>
<p>下面是一个正确的交互过程：</p>
<div class="table-responsive"><table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>选手程序</th><th>交互库</th><th>说明</th></tr></thead><tbody><tr><td></td><td>调用$\texttt{explore(3, 2)}$</td><td>开始测试</td></tr><tr><td>调用$\texttt{modify(1)}$</td><td></td><td>对$0$号洞穴做操作$1$</td></tr><tr><td>调用$\texttt{query(2)}$</td><td>返回$0$</td><td>目前$2$号洞穴的光源状态是关闭</td></tr><tr><td>调用$\texttt{report(0, 1)}$</td><td></td><td>发现了通路$(0, 1)$并记录</td></tr><tr><td>调用$\texttt{check(0)}$</td><td>返回$1$</td><td>与$0$号洞穴相关的通路都已被记录</td></tr><tr><td>调用$\texttt{report(2, 1)}$</td><td></td><td>发现了通路$(2, 1)$并记录</td></tr><tr><td>运行结束并返回</td><td>向屏幕打印`Correct`</td><td>交互结束，结果正确</td></tr></tbody></table></div>


# 评分方式


<p>最终评测<strong>只会</strong>收取 <code>explore.cpp/c/pas</code>，修改选手目录下其他文件对评测<strong>无效</strong>。</p>
<p><strong>本题首先会受到和传统题相同的限制</strong>。例如编译错误会导致整道题目得 $0$ 分，运行时错误、超过时间限制、超过空间限制等会导致相应测试点得 $0$ 分等。你只能访问自己定义的和交互库给出的变量及其对应的内存空间，尝试访问其他空间将可能导致编译错误或运行错误。</p>
<p>在上述条件基础上，在一个测试点中，你得到满分，当且仅当：</p>
<ol><li>你的每次函数调用均合法，且调用 $\texttt{modify}$、$\texttt{query}$ 和 $\texttt{check}$ 的次数分别不超过 $L_m, L_q, L_c$。</li>
<li>由于 $\texttt{report}$ 的调用次数限制为 $M$，你的每次调用都必须记录一条新的且存在的边；即每次调用 $\texttt{report(x, y)}$ 时，应满足：有一条连接 $x$ 号洞穴和 $y$ 号洞穴的通路，且在这次调用之前从未调用过 $\texttt{report(x, y)}$ 或 $\texttt{report(y, x)}$。</li>
<li>你实现的函数 $\texttt{explore}$ 正常返回。</li>
<li>在 $\texttt{explore}$ 函数返回时，你已经通过调用 $\texttt{report}$ 记录了全部 $M$ 条通路。</li>
</ol>
# 限制与约定


<p>本题共 $25$ 个测试点，每个测试点 $4$ 分。每个测试点的数据规模和相关限制见下表。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$N=$</th><th>$M=$</th><th>$L_m=$</th><th>$L_q=$</th><th>$L_c=$</th><th>特殊性质</th>
</tr></thead><tbody><tr><td>$1$</td><td>$3$</td><td>$2$</td><td>$100$</td><td>$100$</td><td>$100$</td><td rowspan="5">无</td></tr><tr><td>$2$</td><td>$100$</td><td rowspan="4">$10N$</td><td>$200$</td><td>$10^4$</td><td rowspan="4">$2M$</td></tr><tr><td>$3$</td><td>$200$</td><td>$200$</td><td>$4\times 10^4$</td></tr><tr><td>$4$</td><td>$300$</td><td>$299$</td><td>$9\times 10^4$</td></tr><tr><td>$5$</td><td>$500$</td><td>$499$</td><td>$1.5\times 10^5$</td></tr><tr><td>$6$</td><td>$59998$</td><td rowspan="4">$N/2$</td><td>$17N$</td><td>$17N$</td><td rowspan="6">$0$</td><td rowspan="4">A</td></tr><tr><td>$7$</td><td>$99998$</td><td>$18N$</td><td>$18N$</td></tr><tr><td>$8$</td><td>$199998$</td><td>$19N$</td><td>$19N$</td></tr><tr><td>$9$</td><td>$199998$</td><td>$19N$</td><td>$19N$</td></tr><tr><td>$10$</td><td>$99997$</td><td rowspan="8">$N-1$</td><td>$18N$</td><td>$18N$</td><td rowspan="2">B</td></tr><tr><td>$11$</td><td>$199997$</td><td>$19N$</td><td>$19N$</td></tr><tr><td>$12$</td><td>$99996$</td><td rowspan="14">$10^7$</td><td rowspan="6">$10^7$</td><td rowspan="14">$2M$</td><td rowspan="3">C</td></tr><tr><td>$13$</td><td>$199996$</td></tr><tr><td>$14$</td><td>$199996$</td></tr><tr><td>$15$</td><td>$99995$</td><td rowspan="3">D</td></tr><tr><td>$16$</td><td>$99995$</td></tr><tr><td>$17$</td><td>$199995$</td></tr><tr><td>$18$</td><td rowspan="3">$1004$</td><td>$2000$</td><td rowspan="3">$5\times 10^4$</td><td rowspan="8">无</td></tr><tr><td>$19$</td><td>$3000$</td></tr><tr><td>$20$</td><td>$3000$</td></tr><tr><td>$21$</td><td>$5\times 10^4$</td><td>$2N$</td><td rowspan="5">$10^7$</td></tr><tr><td>$22$</td><td>$10^5$</td><td>$2N$</td></tr><tr><td>$23$</td><td>$1.5\times 10^5$</td><td>$2\times 10^5$</td></tr><tr><td>$24$</td><td>$2\times 10^5$</td><td>$2.5\times 10^5$</td></tr><tr><td>$25$</td><td>$2\times 10^5$</td><td>$3\times 10^5$</td></tr></tbody></table></div>

<p>再次提醒，<strong>题目保证测试所使用的图在交互开始之前已经完全确定，而不会根据和你的程序的交互动态构造</strong>。</p>
<p>表中特殊性质栏中变量的含义如下：</p>
<ul><li>A：保证每个点的度数恰好为 $1$。</li>
<li>B：保证对于每个 $x &gt; 0$，存在恰好一个 $y &lt; x$ 的 $y$ 使得 $x$ 号洞穴与 $y$ 号洞穴有通路直接相连。</li>
<li>C：存在 $0 \sim N − 1$ 的一个排列 $p_0, p_1, \ldots , p_{N−1}$，使得对任意 $1 \le i &lt; N$，存在一条连接洞穴编号分别为 $p_{i−1}$ 与 $p_i$ 的通路。</li>
<li>D：保证图连通。</li>
</ul><p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 提示


<p>你的程序可以通过判断传入的 $N$ 的个位来区分上述不同的数据类型。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=483">样例数据下载</a></p>
