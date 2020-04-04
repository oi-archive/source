# 题目描述

<p>Anthony 是一只生活在 JOI 市的蚂蚁。JOI 市共有被划分为 $N$ 个町，编号为 $0$ 到 $N-1$。Anthony 居住在 $0$ 号町。总共有 $M$ 条路，编号为 $0$ 到 $M-1$。第 $i$ 条路连接编号为 $U_i$ 和 $V_i$ 的町 ($U_i \neq V_i$)，每条路是双向的。保证不存在两条连接两个相同的町的道路，同时每个点可以直接或间接互相到达。</p>
<p>Catherine 是一只猫，也是 Anthony 的好朋友。她打算游览 JOI 市，但是她并不知道关于路的信息，所以经常迷路。于是，Anthony 打算事先在每条道路上都作上标记。标记共有 $A$ 种，编号为 $0$ 到 $A-1$。</p>
<p>Catherine 现在到达了 JOI 市。当她不在 $0$ 号町时，她会做如下事情：</p>
<ul><li>对于每种标记，她会统计当前所在的町连出去的道路中，除了她上一次走来的道路（若存在）之外，这种标记共出现了多少次。</li>
</ul><p>之后她会选择一条路去行动。注意<strong>除了上一次走来路，她仅能通过路上的标记来分辨其余的道路</strong>。她想尽量快地到达 $0$ 号町。更准确地说，若起点至 $0$ 号町最少需要经过 $d$ 条道路，那么她希望在经过不超过 $d+B$ 条边后就能到达 $0$ 号町。</p>
<p>你需要编写程序模拟 Anthony 摆放路标和 Catherine 探索 JOI 城的过程。</p>

# 交互细节


<p>你需要提交两个程序。</p>
<p>第一个程序为<code>Anthony.cpp</code>，它会模拟Anthony的摆放过程。需要包含头文件<code>Anthony.h</code>。</p>
<ul><li><p><code>std::vector&lt;int&gt; Mark(int N, int M, int A, int B, std::vector&lt;int&gt; U, std::vector&lt;int&gt; V)</code></p>
<p>该程序会恰好在开始时调用一次。</p>
<ul><li>数字 $N,M,A,B$ 含义同题面。</li>
<li>U,V存储着所有的边，$\texttt{U[i]}$ 和 $\texttt{V[i]}$ 表示第$i$条路连接的街道 $U_i$ 和 $V_i$。</li>
</ul><p>选手需要返回一个长度为 $M$ 的数组 $x$，第 $i$ 个元素 $x_i$ 代表在第 $i$ 条道路上的路标编号。</p>
<p>若 $x$ 长度不为 $M$，测评结果为 &#34;<samp>Wrong Answer [1]</samp>&#34;。若不满足 $0 \le x_i \le A-1$，测评结果为 &#34;<samp>Wrong Answer [2]</samp>&#34;。</p>
</li>
</ul><p>第二个程序为<code>Catherine.cpp</code>，它会模拟Catherine的探索过程。需要包含头文件<code>Catherine.h</code>。</p>
<ul><li><p><code>void Init(int A, int B)</code></p>
<p>该程序会恰好在开始时调用一次。</p>
<ul><li>数字 $A,B$ 含义同题面。</li>
</ul></li>
<li><p><code>int Move(std::vector&lt;int&gt; y)</code></p>
<p>该程序会在每次Catherine到达一个不是0的街道时调用。</p>
<ul><li>$y$ 是一个长度为$A$的数组，元素 $y_j$ 代表着所有与当前街道相连且不为她上一次走过的路(若存在)的路上标记 $j$ 的出现次数。</li>
<li>你需要返回一个整数 $z$，表示选择走的标记。需要满足 $-1 \le z \le A-1$。若不满足 $-1 \le z \le A-1$，测评结果为 &#34;<samp>Wrong Answer [3]</samp>&#34;。若 $z=-1$，表示Catherine原路返回，此时若Catherine未进行过任何操作，测评结果为 &#34;<samp>Wrong Answer [4]</samp>&#34;。若 $0 \le z \le A-1$，表示 Catherine 选择一条标记为 $z$ 的边经过，此时若 $y_z=0$，测评结果为 &#34;<samp>Wrong Answer [5]</samp>&#34;。</li>
</ul><p>注意如果有多条可以选择的边，grader不一定会随机选择一条合法的出现行动。</p>
<p>如果 Catherine 未能在 $D+b$ 步内到达街道0，测评结果为 &#34;<samp>Wrong Answer [6]</samp>&#34;。</p>
</li>
</ul>
# 注意事项


<p>  选手程序可能会运用若干全局变量和子程序。为了防止多个文件变量重名或子程序重名带来的编译错误，请将所有全局变量和子程序定义在一个没有名字的 namespace 里。</p>
<p>  如果在程序里使用 printf/scanf/cout/cin，会直接导致 Wrong Answer 或者 Runtime Error。</p>
<p>  最终测评时会将 Anthony 和 Catherine 的程序独立编译，因此不能共享全局变量。</p>

# 编译与运行


<p>将<code>grader.cpp</code>, <code>Anthony.cpp</code>,<code>Catherine.cpp</code>,<code>Anthony.h</code>,<code>Catherine.h</code>放在同一文件夹下，在终端内运行如下命令</p>
<pre><code class="sh_sh">g++ -O2 -o grader grader.cpp Anthony.cpp Catherine.cpp</code></pre>
<p>编译成功时会得到一个可执行文件<code>grader</code>。</p>
<p>可执行文件从标准输入种读入以下内容:</p>
<p>第一行五个数字 $N,M,A,B,S$。其中$S$表示起点。</p>
<p>接下来$M$行，每行两个数字 $U_i,V_i$,表示一条道路。</p>
<p>可执行文件回想标准输出流输出以下内容。</p>
<p>若程序运行时产生错误 [1] 至 [5]，则会输出形如 &#34;<samp>Wrong Answer [1]</samp>&#34; 的错误信息。</p>
<p>否则如果未在 $N+B$ 步内到达街道1，输出 &#34;<samp>Wrong Answer; Number of moves &gt; N + B</samp>&#34;. </p>
<p>否则按照 &#34;<samp>Number of moves = 4</samp>&#34; 的格式输出信息。</p>

# 数据范围


<ul><li>子任务1 ($2$分)：$A=4, B=0, M=N-1$。</li>
<li>子任务2 ($2$分)：$A=4, B=0$。</li>
<li>子任务3 ($2$分)：$A=3, B=0, M=N-1$。</li>
<li>子任务4 ($9$分)：$A=3, B=0$。</li>
<li>子任务5 ($5$分)：$A=2, B=2N, M=N-1, 6 \le N \le 500$。</li>
<li>子任务6 ($71$分)：$A=2, B=12, M=N-1$。</li>
<li>子任务7 ($9$分)：$A=2, B=6, M=N-1$。</li>
</ul><p>对于所有测试数据，满足 $2 \le N \le 20000,1 \le M \le 20000,1 \le S &lt; N$。</p>
<p>保证图联通且无重边无自环。</p>
<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$1\texttt{GB}$</p>

# 关于 UOJ 上该题的测评方式


<p>由于传这道题的时候 vfk 想起了自己学过的密码学，于是决定加点密码学玩玩 233</p>
<p>UOJ 测评该题时会用基于 mt19937_64 的流加密算法对输入输出进行加密，并用基于 SHA256 的 HMAC 做数字签名。私钥是随机的，每次测评直接编译进交互库。为了防止交互库被 include 后套出私钥，交互库的文件名也是随机的。</p>
<p>vfk 想知道这种情况下交互库还能不能被 hack？（期待）</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=509">样例及测评库下载</a></p>
