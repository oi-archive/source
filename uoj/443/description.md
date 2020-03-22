# 题目描述

<p>这是一道<strong>交互题</strong> 。</p>

# 题目描述


<blockquote>
<p>「你有一万个理由和你们队的画风不太一样</p>
<p>「最简单的理由：你太菜了</p>
<p>「哈哈哈哈哈哈哈」</p>
</blockquote>
<p> $\mathfrak{rehtien}$ 和 $\mathfrak{airrats}$ 也在玩猜数游戏。</p>
<p>规则是这样的： $\mathfrak{rehtien}$ 先想一个数 $x$ ，然后 $\mathfrak{airrats}$ 进行猜测，如果猜对了， $\mathfrak{rehtien}$ 就会帮她出题。</p>
<p>但很快， $\mathfrak{airrats}$ 就意识到了问题：「你都不让我二分，我怎么猜？」因此 $\mathfrak{airrats}$ 规定 $|x|=1$ ，这样她就有 $\frac{1}{2}$ 的概率猜中了。</p>
<p>因此当下一轮游戏结束后， $\mathfrak{rehtien}$ 告诉她， $x\in \mathbb{C}$ ，而他想的数是 $i$ 时， $\mathfrak{airrats}$ 非常生气。她觉得有必要使用一些玄妙的方法。</p>

# 任务介绍


<p>具体地， $\mathfrak{airrats}$ 有一个长为 $2^n$ 的数组，初始 $a_0=1$ ，其余为 0 。</p>
<p>她要实现一个函数 <code>SOL(t)</code> ，其中 $t$ 为子任务编号。函数返回一个复数，表示 $x$ 。</p>
<p>她可以调用如下函数：</p>
<p> <code>INI(n)</code> 其中 $1\le n\le 16$ 。该函数<strong>须在调用下文的函数前调用恰一次</strong> ，表示初始化一个长为 $2^n$ 的数组。</p>
<p> <code>CU(d,k)</code> 其中 $0\le d\lt n,-2^{16}\lt k \lt 2^{16}$ 。调用该函数后，对于所有二进制第 $d$ 位为 1 的 $i$ ，令 $a&#39;_i = x^ka_i $ 。随后 $a_i$ 更新为 $a&#39;_i$ 。</p>
<p> <code>CR(d1,d2,A)</code> 其中 $0\le d_1,d_2 \lt n$ ，$A$ 是一个 $2\times 2$ 的复数矩阵，<strong>满足 $AA^*=I$ </strong>，其中 $I$ 为单位矩阵， $A^*$ 为 $A$ 的共轭转置。调用该函数后，对于所有二进制第 $d_1,d_2$ 位均为 1 的 $i$ ，令 </p>
<p>$$ \begin{equation} \left\{  \begin{array}{lr}  a&#39;_{i-2^{d_2}} = A_{0,0}a_{i-2^{d_2}}+A_{1,0}a_{i}  \\ a&#39;_{i}=A_{0,1}a_{i-2^{d_2}}+A_{1,1}a_{i}  \end{array} \right.\end{equation} $$   </p>
<p>随后 $a_{i-2^{d_2}}$ 更新为 $a&#39;_{i-2^{d_2}}$ ， $a_{i}$ 更新为 $a&#39;_{i}$  。</p>
<p> <code>ACR(A)</code> 其中 $A$ 指向一个 $2^n\times 2^n$ 的复数矩阵，满足 $AA^*=I$ 。调用该函数后，令 $a&#39;_i=\sum_{j=0}^{2^n-1} A_{i,j}a_j$ ，随后 $a_i$ 更新为 $a&#39;_i$ 。  如果需要调用该函数，请注意时空复杂度。</p>
<p> <code>QR()</code>会随机返回一个 $[0,2^n)$ 间的整数，返回 $i$ 的概率为 $\frac{|a_i|^2}{\sum_{j} |a_j|^2}$ 。</p>

# 实现细节


<p>源代码需要包含头文件 <code>unnamable.h</code> 。</p>
<p>涉及到的函数接口如下：</p>
<pre><code class="sh_cpp">complex&lt;double&gt; SOL(int t);
void INI(int n);
void CU(int d,int k);
void CR(int d1,int d2,complex&lt;double&gt; A[2][2]);
void ACR(complex&lt;double&gt; **A);
int QR();</code></pre>
<p>详见样例程序 <code>sample.cpp</code> 。关于上述函数的具体实现，详见 <code>grader.cpp</code> 。</p>
<p>下发的 grader 将从 <code>input.txt</code> 中读入三个整数 $ans,seed,typ$ ，分别为本组数据的答案、随机种子和子任务编号，其中 $ans$ 表示 $x=\omega_{65536}^{ans}$ 。运行结束后，运行结果与错误信息将会被输出至 <code>result.txt</code> 。</p>

# 限制与约定


<p>在每组数据中， <code>SOL()</code> 将会被调用一次。令 $res$ 为 <code>SOL()</code> 的返回值， 当 $|res-x|\le 10^{-5}$ 时视为正确。</p>
<p>对于所有数据，<code>CU,CR,QR,ACR</code> 的总调用次数不能超过 300 。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th><th>分值</th><th>限制</th><th>性质</th></tr></thead><tbody><tr><td>1</td><td>9</td><td><code>QR</code> 调用次数不超过 1 次</td><td>$x\in \{ -1,1\}$</td></tr><tr><td>2</td><td>17</td><td>无</td><td>$x\in \{\omega_{8}^k \} $</td></tr><tr><td>3</td><td>36</td><td><code>QR</code> 调用次数不超过 1 次</td><td>$x\in \{\omega_{512}^k \}$</td></tr><tr><td>4</td><td>38</td><td><code>QR</code> 调用次数不超过 1 次</td><td>$x\in \{\omega_{65536}^k \}$</td></tr></tbody></table><p> </p>
</div>

<p>其中 $\omega_n $ 表示 $n$ 次单位根，$k$ 为整数。</p>
<p>满足 $AA^∗=I$ 的矩阵被称为<a href="//en.wikipedia.org/wiki/Unitary_matrix">酉矩阵</a>。</p>
<p><strong>时间限制</strong>：$\texttt{2s}$</p>
<p><strong>空间限制</strong>：$\texttt{256MB}$</p>
<p>选手程序与交互库共享本题的时空限制，但由于 <code>ACR</code> 操作的存在，我们不能保证交互库的运行时间。最终评测使用的交互库（只保证）各函数的实现方式与下发的 grader 相同，请自行计算实际运行时间与内存。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=443">交互库下载</a></p>
