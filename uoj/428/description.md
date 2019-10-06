# 题目描述

<p>（题目背景）是没有的。</p>
<p>你有一个$01$序列，初始时序列为空。你可以对序列进行两种操作：</p>
<ol><li>在序列末端插入一个$0$。</li>
<li>在序列中删去一个子序列，并在序列末端插入一个$1$。这里对子序列的选取有一定限制，设子序列中包含$x$个$0$，$y$个$1$，则你选取的子序列必须满足：<ul><li>子序列不可为空，即$x+y&gt;0$</li>
<li>当$y&gt;0$时，$x\in A$，这里$A$为给定集合</li>
<li>当$y=0$时，$x\in B$，这里$B$为给定集合</li>
</ul></li>
</ol><p>现在，你需要对序列执行$n$次操作。请你求出在所有不同的操作方案中，最终序列长度为$1$的方案有多少种。两种操作方案被视为不同，当且仅当某一次操作的种类不同，或某个第二类操作中选取的子序列不同（子序列不同指的是位置不同，与值无关）。</p>
<p>答案对$998244353$取模。</p>

# 输入格式


<p>输入第一行包含三个整数$n,|A|,|B|$，表示操作的次数，集合$A$的大小，集合$B$的大小。</p>
<p>输入第二行包含$|A|$个整数$a_1,a_2,\cdots,a_{|A|}$，描述集合$A$的各个元素。</p>
<p>输入第三行包含$|B|$个整数$b_1,b_2,\cdots,b_{|B|}$，描述集合$B$的各个元素。</p>

# 输出格式


<p>输出一个整数，表示答案。</p>

# 样例一


<h4>input</h4>
<pre><code>4 1 1
1
1</code></pre>
<h4>output</h4>
<pre><code>3</code></pre>

# 样例二


<h4>input</h4>
<pre><code>10 10 10
0 1 2 3 4 5 6 7 8 9 
0 1 2 3 4 5 6 7 8 9 </code></pre>
<h4>output</h4>
<pre><code>362880</code></pre>

# 限制与约定


<p>本题使用捆绑测试。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th width="200">子任务</th><th>分值</th><th>限制</th></tr></thead><tbody><tr><td>$1$</td><td>$5$</td><td>$n\leq 10$</td></tr><tr><td>$2$</td><td>$20$</td><td>$n\leq 2000$</td></tr><tr><td>$3$</td><td>$5$</td><td>$|A|=|B|=n$</td></tr><tr><td>$4$</td><td>$30$</td><td>$A=B$</td></tr><tr><td>$5$</td><td>$40$</td><td>无特殊限制</td></tr></tbody></table></div>


<p>对于所有数据，$1\leq n\leq 120000,0\leq a_i,b_i&lt; n$，$a_i$互不相同，$b_i$互不相同。</p>
<p><strong>时间限制：$2\texttt{s}$</strong></p>
<p><strong>内存限制：$512\texttt{MB}$</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=428">样例数据下载</a></p>
