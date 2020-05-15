# 题目描述

<p>因为正式赛有一道交互题，所以在这儿，先让大家熟悉一下交互题的做题方式。</p>

# 任务


<p>你需要编写一个函数 <code>find_pos</code>，来找到一个隐藏的单调不降的有序数组中，小于等于某一个数字的数有多少个。</p>
<ul><li><code>find_pos(n, x)</code><ul><li><code>n</code>: 有序数组的长度。</li>
<li><code>x</code>: 你的目标是计算小于等于 <code>x</code> 的数的个数。</li>
</ul></li>
</ul><p>你可以调用函数 <code>query</code> 以帮助你确定答案。我们会根据你调用这个函数的<strong>次数</strong>评分。</p>
<ul><li><code>query(i)</code> 接受一个 $[1,n]$ 中的整数，并返回有序数组中第 $i$ 个数的值。</li>
</ul><p>在一组测试数据中，<code>find_pos</code> 只会被调用一次。</p>

# 实现细节


<p>本题只支持 C++。</p>
<p>你只能提交一个源文件实现如上所述的 <code>find_pos</code> 函数，并且遵循下面的命名和接口。</p>
<h4>C/C++</h4>
<p>你需要包含头文件 <code>find.h</code>。</p>
<pre><code class="sh_cpp">int find_pos(int n, int x);</code></pre>
<p>你需要把答案以返回值的形式返回。</p>
<p>函数 <code>query</code> 的接口信息如下。</p>
<pre><code class="sh_cpp">int query(int i);</code></pre>
<p>注意 $i$ 的值必须在 $[1,n]$ 中。该函数的返回值是有序数组中第 $i$ 个数，即第 $i$ 小的数。</p>
<p>如果有不清楚的地方，见样例及测评库下载，<strong>内附了样例程序</strong>。</p>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ol><li>第 $1$ 行: $n, x$，表示有序数组长度以及询问的数字 $x$。</li>
<li>第 $2$ 行: $n$ 个空格隔开的整数，表示输入的有序数组。</li>
</ol><p>在 <code>find_pos</code> 返回后，评测系统将输出你的答案以及 <code>query</code> 的调用次数。</p>

# 样例输入



# 样例一


<h4>input</h4>
<pre>5 3
1 2 3 3 4

</pre>

<h4>output</h4>
<pre>4 5

</pre>

<h4>explanation</h4>
<p>样例输出的含义为 <code>find_pos</code> 在 $5$ 次询问之后，返回了答案 $4$。</p>

# 限制与约定


<p><code>find_pos</code> 只能进行不超过 $20$ 次询问。如果超过了这个询问数量，你的程序将无法得分，</p>
<p>输入保证有序数组中的所有元素以及 $x$ 都是 $[1, 10^9]$ 中的整数。</p>
<p><strong>Small Task</strong>: $n \leq 20$</p>
<p><strong>Large Task</strong>: $n \leq 10^5$</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=517">样例交互库下载</a></p>
