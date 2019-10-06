# 题目描述

<p><strong>这是一道交互题。</strong>由于数据有加密，如果需要 Hack，请联系 immortalCO。</p>
<p>小M在玩一个即时战略(Real Time Strategy)游戏。不同于大多数同类游戏，这个游戏的地图是树形的。也就是说，地图可以用一个由 $n$ 个结点，$n - 1$ 条边构成的连通图来表示。这些结点被编号为 $1$ ~ $n$。</p>
<p>每个结点有两种可能的状态：“已知的”或“未知的”。游戏开始时，只有 $1$ 号结点是已知的。在游戏的过程中，小M可以尝试探索更多的结点。具体来说，小M每次操作时需要选择一个已知的结点 $x$，和一个不同于 $x$ 的任意结点 $y$（结点 $y$ 可以是未知的）。然后游戏的自动寻路系统会给出 $x$ 到 $y$ 的最短路径上的第二个结点 $z$，也就是从 $x$ 走到 $y$ 的最短路径上与 $x$ 相邻的结点。此时，如果结点 $z$ 是未知的，小M会将它标记为已知的。</p>
<p>这个游戏的目标是：利用至多 $T$ 次探索操作，让所有结点的状态都成为已知的。然而小M还是这个游戏的新手，她希望得到你的帮助。</p>
<p><strong>为了让游戏过程更加容易，小M给你提供了这个游戏的交互库，具体见【任务描述】和【实现细节】。</strong></p>
<p><strong>另外，小M也提供了一些游戏的提示，具体见题目的最后一节【提示】。</strong></p>

# 任务介绍


<p>你需要实现一个函数 <code>play</code>，以帮助小M完成游戏的目标。</p>
<ul><li><code>play(n, T, dataType)</code><ul><li><code>n</code> 为树的结点个数；</li>
<li><code>T</code> 为探索操作的次数限制；</li>
<li><code>dataType</code> 为该测试点的数据类型，具体见【数据规模和约定】。</li>
</ul></li>
</ul><p>在每个测试点中，交互库都会调用恰好一次 <code>play</code> 函数。该函数被调用之前，游戏处于刚开始的状态。</p>
<p>你可以调用函数 <code>explore</code> 来帮助你在游戏中探索更多结点，但是这个函数的调用次数不能超过 $T$ 次。</p>
<ul><li><code>explore(x, y)</code><ul><li><code>x</code> 为一个已知的结点；</li>
<li><code>y</code> 为一个不同于 $x$ 的任意结点（可以不是已知的结点）；</li>
<li>这个函数会返回结点 $x$ 到 $y$ 的最短路径上的第二个结点的编号。</li>
</ul></li>
</ul><p>在函数 <code>play</code> 返回之后，交互库会检查游戏的状态：只有当每个结点都是已知的，才算游戏的目标完成。</p>

# 实现方法


<p>你需要且只能提交一个源文件 rts.cpp/c/pas 实现上述函数，且遵循下面的命名和接口。</p>
<p><strong>对 C/C++ 语言的选手：</strong></p>
<p>源代码中需要包含头文件 rts.h。</p>
<p>你需要实现的函数 <code>play</code>：</p>
<pre><code class="sh_c">void play(int n, int T, int dataType);</code></pre>
<p>函数 <code>explore</code> 的接口信息如下：</p>
<pre><code class="sh_c">int explore(int x, int y);</code></pre>
<p><strong>对 Pascal 语言的选手：</strong></p>
<p>你需要使用单元 graderhelperlib。</p>
<p>你需要实现的函数 <code>play</code>：</p>
<pre><code class="sh_pascal">procedure play(n, T, dataType : longint);</code></pre>
<p>函数 <code>explore</code> 的接口信息如下：</p>
<pre><code class="sh_pascal">function explore(x, y : longint) : longint;</code></pre>

# 如何测试你的程序


<p><strong>对 C/C++ 语言的选手：</strong></p>
<p>你需要在本题目录下使用如下命令编译得到可执行程序：</p>
<p>对于 C 语言：</p>
<p><code>gcc grader.c rts.c -o rts -O2</code></p>
<p>对于 C++ 语言：</p>
<p><code>g++ grader.cpp rts.cpp -o rts -O2</code></p>
<p><strong>对 Pascal 语言的选手：</strong></p>
<p>你需要在本题目录下使用如下命令编译得到可执行程序：</p>
<p><code>fpc grader.pas -o&#34;rts&#34; -O2</code></p>
<p>可执行文件将从<strong>标准输入</strong>读入以下格式的数据：</p>
<p>第一行包含三个整数 $n$, $T$, $\texttt{dataType}$，需要保证 $n$ 在 [$2$, $3 \times 10^5$] 之间，$T$ 在 [$1$, $5 \times 10^6$] 之间，$\texttt{dataType}$ 在 [$1$, $3$] 之间。</p>
<p>接下来 $n - 1$ 行，每行两个整数 $u$, $v$，需要保证 $1 \le u, v \le n$ 且 $u \ne v$，表示一条 $u$ 和 $v$ 之间的边。</p>
<p>你的输入需要保证这 $n - 1$ 条边构成一棵树。</p>
<p>读入完成之后，交互库将调用 <code>play</code> 函数。如果此时你调用 <code>explore</code> 的次数超过 $T$ 次，则交互库会输出详细的错误信息，并退出。</p>
<p>接下来交互库会判断游戏目标是否完成。如果完成，则会输出 &#34;Correct&#34;，否则会输出相应的错误信息。</p>
<p>如果传入 <code>explore</code> 函数的参数非法（$x,y$ 不在 $1$ 到 $n$ 的范围内，或 $x$ 不是已知结点，或 $x$ 等于 $y$），那么交互库会输出详细的错误信息，并退出。</p>
<p>如果要使用自己的输入文件进行测试，请保证输入文件符合以上格式要求，否则不保证程序能正确运行。</p>

# 如何使用样例源代码


<p>本题目录下，有针对每种语言的样例源代码 rts_sample.cpp/c/pas。选择你所需的语言，将其复制为 rts.cpp/c/pas，按照上文中提到的方式进行编译，即能通过编译得到可执行程序。 </p>
<p>对于非正式选手，你只能选择一种语言进行作答，即你本题的试题目录下不能同时存在多个语言的 rts.cpp/c/pas，否则系统将任选一份源代码进行评测并作为最终结果。</p>
<p>接下来你需要修改这个文件的实现，以达到题目的要求。</p>

# 样例一


<h4>input</h4>
<pre>4 100 1
1 3
3 4
3 2
</pre>


<h4>output</h4>
<pre>Correct
</pre>

<h4>explanation</h4>
<p>这是使用试题目录的 grader 和正确的源程序得到的输出文件。</p>
<p>对于此样例，一种可能的 <code>explore</code> 函数的调用顺序为：</p>
<ul><li><code>explore(1, 2)</code>，返回 3</li>
<li><code>explore(3, 2)</code>，返回 2</li>
<li><code>explore(2, 4)</code>，返回 3</li>
<li><code>explore(3, 4)</code>，返回 4</li>
</ul>
# 样例二


<p>见<a href="/download.php?type=problem&amp;id=349">下载目录</a>下的 <em>ex_2.in</em> 与 <em>ex_2.ans</em>。</p>
<p>该组样例的数据范围同第 5 个测试点。</p>

# 样例三


<p>见<a href="/download.php?type=problem&amp;id=349">下载目录</a>下的 <em>ex_3.in</em> 与 <em>ex_3.ans</em>。</p>
<p>该组样例的数据范围同第 8 个测试点。</p>

# 评分方式


<p>最终评测时只会收取 rts.cpp/c/pas，修改选手目录中的其他文件对评测无效。</p>
<p>题目首先会受到和非交互式程序题相同的限制。例如编译错误会导致整道题目得 0 分，运行时错误、超过时间限制、超过空间限制等会导致相应测试点得 0 分等。 你只能访问自己定义的和交互库给出的变量及其对应的内存空间，尝试访问其他空间将可能导致编译错误或运行错误。 </p>
<p>若程序正常结束，则会开始检验正确性。只有当游戏目标完成时，该测试点得满分，其他情况该测试点得 0 分。</p>
<p>题目中所给的时间、空间限制为你的代码和交互库加起来可以使用的时间和空间。我们保证，对于任何合法的数据及在限制范围内的调用，任何语言任何版本的交互库（包括下发给选手的和最终评测使用的），运行所用的时间不会超过 1s，运行所用的空间不会超过 64MB，也就是说，选手实际可用的时间至少为 2s，实际可用的空间至少为 448MB。</p>

# 提示


<p>这里是小M给你的一些贴心的提示：</p>
<ul><li>图（无向图）由结点和边构成，边是结点的无序对，用来描述结点之间的相互关系</li>
<li>路径是一个结点的非空序列，使得序列中相邻两个结点之间都有边相连</li>
<li>两个结点是连通的，当且仅当存在一条以其中一个结点开始、另一个结点结束的路径</li>
<li>一个图是连通的，当且仅当这个图上的每对结点都是连通的</li>
<li>一棵 $n$ 个结点的树，是一个由 $n$ 个结点，$n - 1$ 条边构成的连通图</li>
<li>两个结点的最短路径，是指连接两个结点的所有可能的路径中，序列长度最小的</li>
<li>在一棵树中，连接任意两个结点的最短路径，都是唯一的</li>
<li>通过访问输入输出文件、攻击评测系统或攻击评测库等方式得分属于作弊行为，所得分数无效。</li>
</ul>
# 限制与约定


<p>一共有 20 个测试点，每个测试点 5 分。</p>
<p>对于所有测试点，以及对于所有样例，$2 \le n \le 3 \times 10^5, 1 \le T \le 5 \times 10^6, 1 \le \texttt{dataType} \le 3$。
不同 $\texttt{dataType}$ 对应的数据类型如下：</p>
<ul><li>对于 $\texttt{dataType} = 1$ 的测试点，没有特殊限制</li>
<li>对于 $\texttt{dataType} = 2$ 的测试点，游戏的地图是一棵以结点 $1$ 为根的完全二叉树，
即，存在一个 $1$ ~ $n$ 的排列 $a$，满足 $a_1 = 1$，且结点 $a_i ~ (1 &lt; i \le n)$ 与结点 $a_{\lfloor i/2 \rfloor}$ 之间有一条边相连</li>
<li>对于 $\texttt{dataType} = 3$ 的测试点，游戏的地图是一条链，
即，存在一个 $1$ ~ $n$ 的排列 $a$，满足结点 $a_i ~ (1 &lt; i \le n)$ 与结点 $a_{i-1}$ 之间有一条边相连</li>
</ul><p>对于每个测试点，$n, T, \texttt{dataType}$ 的取值如下表：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n$</th><th rowspan="1">$T$</th><th rowspan="1">$\texttt{dataType}$</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">2</td><td rowspan="1">10000</td><td rowspan="4">1</td></tr><tr><td rowspan="1">2</td><td rowspan="1">3</td><td rowspan="1">10000</td></tr><tr><td rowspan="1">3</td><td rowspan="1">10</td><td rowspan="1">10000</td></tr><tr><td rowspan="1">4</td><td rowspan="1">100</td><td rowspan="1">10000</td></tr><tr><td rowspan="1">5</td><td rowspan="1">1000</td><td rowspan="1">10000</td><td rowspan="3">2</td></tr><tr><td rowspan="1">6</td><td rowspan="1">20000</td><td rowspan="1">300000</td></tr><tr><td rowspan="1">7</td><td rowspan="1">250000</td><td rowspan="1">5000000</td></tr><tr><td rowspan="1">8</td><td rowspan="1">1000</td><td rowspan="1">20000</td><td rowspan="6">3</td></tr><tr><td rowspan="1">9</td><td rowspan="1">5000</td><td rowspan="1">15500</td></tr><tr><td rowspan="1">10</td><td rowspan="1">30000</td><td rowspan="1">63000</td></tr><tr><td rowspan="1">11</td><td rowspan="1">150000</td><td rowspan="1">165000</td></tr><tr><td rowspan="1">12</td><td rowspan="1">250000</td><td rowspan="1">250100</td></tr><tr><td rowspan="1">13</td><td rowspan="1">300000</td><td rowspan="1">300020</td></tr><tr><td rowspan="1">14</td><td rowspan="1">1000</td><td rowspan="1">50000</td><td rowspan="7">1</td></tr><tr><td rowspan="1">15</td><td rowspan="1">5000</td><td rowspan="1">200000</td></tr><tr><td rowspan="1">16</td><td rowspan="1">30000</td><td rowspan="1">900000</td></tr><tr><td rowspan="1">17</td><td rowspan="1">150000</td><td rowspan="1">3750000</td></tr><tr><td rowspan="1">18</td><td rowspan="1">200000</td><td rowspan="1">4400000</td></tr><tr><td rowspan="1">19</td><td rowspan="1">250000</td><td rowspan="1">5000000</td></tr><tr><td rowspan="1">20</td><td rowspan="1">300000</td><td rowspan="1">5000000</td></tr></tbody></table></div>


# 下载


<p><a href="/download.php?type=problem&amp;id=349">样例和交互库下载</a></p>
<p><strong>时间限制：</strong><del>2s</del> $3\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>
