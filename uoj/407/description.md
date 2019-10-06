# 题目描述

<p>在日本的茨城县内共有 $N$ 个城市和 $M$ 条道路。这些城市是根据人口数量的升序排列的，依次编号为 $0$ 到 $N-1$。每条道路连接两个不同的城市，并且可以双向通行。由这些道路，你能从任意一个城市到另外任意一个城市。</p>
<p>你计划了 $Q$ 个行程，这些行程分别编号为 $0$ 至 $Q-1$。第 $i$（$0\le i\le Q-1$）个行程是从城市 $S_i$ 到城市 $E_i$。</p>
<p>你是一个狼人。你有两种形态：<strong>人形</strong>和<strong>狼形</strong>。在每个行程开始的时候，你是人形。在每个行程结束的时候，你必须是狼形。在行程中，你必须要变身（从人形变成狼形）恰好一次，而且只能在某个城市内（包括可能是在 $S_i$ 或 $E_i$ 内）变身。</p>
<p>狼人的生活并不容易。当你是人形时，你必须避开人少的城市，而当你是狼形时，你必须避开人多的 城市。对于每一次行程 $i$（$0\le i\le Q-1$），都有两个阈值 $L_i$ 和$R_i$（$0\le L_i\le R_i\le N-1$），用以表示哪些城市必须要避开。准确地说，当你是人形时，你必须避开城市 $0,1,\cdots,L_i-1$；而当你是狼形时，则必须避开城市 $R_i+1,R_i+2,\cdots,N-1$。这就是说，在行程 $i$ 中，你必须在城市 $L_i,L_i+1,\cdots,R_i$ 中的其中一个城市内变身。</p>
<p>你的任务是，对每一次行程，判定是否有可能在满足上述限制的前提下，由城市 $S_i$ 走到城市 $E_i$。你的路线可以有任意长度。</p>

# 实现细节


<p>你需要实现下面的函数：</p>
<pre><code class="sh_cpp">int[] check_validity(int N, int[] X, int[] Y, int[] S, int[] E, int[] L, int[] R)</code></pre>
<ul><li><code>N</code>：城市的数量</li>
<li><code>X</code> 和 <code>Y</code>：两个长度为 $M$ 的数组。对于每个 $j$（$0\le j\le M-1$），城市 <code>X[j]</code> 都有道路直接连到城市 <code>Y[j]</code>。</li>
<li><code>S</code>, <code>E</code>, <code>L</code>, 及 <code>R</code>：均为长度为 $Q$ 的数组，以表示行程。</li>
</ul><p>注意，$M$ 和 $Q$ 是数组的长度，它们的值可以按照“注意事项”中的相关说明而取得。</p>
<p>对于每个测试样例，函数 <code>check_validity</code> 将被调用恰好一次。这个函数应返回长度为 $Q$ 的整数数组 $A$。如果行程 $i$ 可以在满足前述限制的条件下完成，则 $A_i$（$0\le i\le Q-1$）的值必须为 $1$，否则为 $0$。</p>

# 例子


<p>设 $N=6$，$M=6$，$Q=3$，$X=[5,1,1,3,3,5]$，$Y=[1,2,3,4,0,2]$，$S=[4,4,5]$，$E=[2,2,4]$，$L=[1,2,3]$ 及 $R=[2,2,4]$。</p>
<p>评测程序调用 <code>check_validity(6, [5, 1, 1, 3, 3, 5], [1, 2, 3, 4, 0, 2], [4, 4, 5], [2, 2, 4], [1, 2, 3], [2, 2, 4])</code>。</p>
<p>对于行程 $0$，你可以按照以下方式由城市 $4$ 走到城市 $2$：</p>
<ul><li>从城市 $4$ 出发（你是人形）</li>
<li>前往城市 $3$（你是人形）</li>
<li>再前往城市 $1$（你是人形）</li>
<li>你变身为狼（你现在是狼形）</li>
<li>前往城市 $2$（你是狼形）</li>
</ul><p>而对于行程 $1$ 及 $2$，你不可能完成在指定城市间的行程。</p>
<p>因此，你的程序必须返回 $[1,0,0]$。</p>
<p>在样例数据下载中的文件 <code>ex_werewolf1.in</code> 和 <code>ex_werewolf1.out</code> 对应于本例。这个包中还包含另外一些输入/输出样例文件。</p>

# 限制条件


<ul><li>$2\le N\le 200\ 000$</li>
<li>$N-1\le M\le 400\ 000$</li>
<li>$1\le Q\le 200\ 000$</li>
<li>对于每个 $0\le j\le M-1$</li>
<li>$0\le X_j\le N-1$</li>
<li>$0\le Y_j\le N-1$</li>
<li>$X_j\ne Y_j$</li>
<li>你可以通过道路由任意一个城市去另外任意一个城市。</li>
<li>每一对城市最多只由一条道路直接连起来。换言之，对于所有 $0\le j&lt;k\le M-1$，都有 $(X_j,Y_j)\ne(X_k,Y_k)$ 和 $(Y_j,X_j)\ne(X_k,Y_k)$</li>
<li>对于每个 $0\le i\le Q-1$</li>
<li>$0\le L_i\le S_i\le N-1$</li>
<li>$0\le E_i\le R_i\le N-1$</li>
<li>$S_i\ne E_i$</li>
<li>$L_i\le R_i$</li>
</ul>
# 子任务


<ol><li>（7 分）$N\le 100$，$M\le 200$，$Q\le 100$</li>
<li>（8 分）$N\le 3\ 000$，$M\le 6\ 000$，$Q\le 3\ 000$</li>
<li>（34 分）$M=N-1$ 且每个城市最多与两条路相连（所有城市是以一条直线的形式连起来）</li>
<li>（51 分）没有附加限制</li>
</ol>
# 评测程序示例


<p>评测程序示例将按照以下格式读入输入数据:</p>
<ul><li>第 $1$ 行：$N\ M\ Q$</li>
<li>第 $2+j$ 行（$0\le j\le M-1$）：$X_j\ Y_j$</li>
<li>第 $2+M+i$ 行（$0\le i\le Q-1$）：$S_i\ E_i\ L_i\ R_i$ </li>
</ul><p>评测程序示例将以如下格式把 <code>check_validity</code> 的返回值打印出来:</p>
<ul><li>第 $1+i$ 行（$0\le i\le Q-1$）：$A_i$</li>
</ul>
# 约定及限制


<p>对于所支持的各种编程语言，下面列出了对应的数据类型。对于数据类型的细节等，参见实现示例。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>语言</th>
<th>$\texttt{int}$</th>
<th>$\texttt{int64}$</th>
<th>$\texttt{int[]}$</th>
<th>数组$a$的长度</th>
<th>$\texttt{string}$</th>
</tr></thead><tbody><tr><td>$\texttt{C++}$</td><td>$\texttt{int}$</td><td>$\texttt{long long}$</td><td>$\texttt{std::vector&lt;int&gt;}$</td><td>$\texttt{a.size()}$</td><td>$\texttt{std::string}$</td></tr></tbody></table></div>


<p><strong>时间限制</strong>：$4\texttt{s}$</p>
<p><strong>空间限制</strong>：$537\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=407">样例数据下载</a></p>
