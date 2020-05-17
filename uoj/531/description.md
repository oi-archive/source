# 题目描述

<p>蒜斜和镁团在玩一个叫做“你问你猜”的游戏（可怜去哪了？）。规则如下：</p>
<p>镁团手中有$n$个数，且恰好是 $1-n$ 的排列。
每次询问，蒜斜需要给出一个长度不超过 $100$，且每个元素都在 $1-n$ 之间的数列（<strong>不需要是排列</strong>）；之后镁团会告诉蒜斜这两个数列的最长公共子序列长度。
蒜斜需要在<strong>不超过$650$次询问</strong>内猜出镁团手中的排列。</p>
<p>这对于蒜斜来说实在太困难了，因此他找到了玉树临风文质彬彬英俊潇洒神采奕奕温文尔雅风度翩翩的你，你能帮助他吗？</p>

# 任务


<p>你需要编写一个函数 <code>find_permutation</code>，以确定镁团手中的排列是什么。</p>
<ul><li><code>find_permutation(n, res)</code><ul><li><code>n</code>: 镁团手中排列的长度。</li>
<li><code>res</code>：返回数组，你需要把你确定的排列存储到 <code>res</code> 中。</li>
</ul></li>
</ul><p>你可以调用函数 <code>get_lcs</code> 以帮助你确定镁团手中的排列。我们会根据你调用这个函数的<strong>次数</strong>评分。</p>
<ul><li><code>get_lcs(len, A)</code> 接受整数 <code>len</code> 和一个长度为 <code>len</code> 的数组 <code>A</code>，并会返回数组 <code>A</code> 与目标排列的最长公共子序列长度。</li>
</ul><p>在一组测试数据中，<code>find_permutation</code> 只会被调用一次。</p>

# 实现细节


<p>本题只支持 C++。</p>
<p>你只能提交一个源文件实现如上所述的 <code>find_permutation</code> 函数，并且遵循下面的命名和接口。</p>
<h4>C++</h4>
<p>你需要包含头文件 <code>lcs.h</code>。</p>
<pre><code class="sh_cpp">void find_permutation(int n, int res[]);</code></pre>
<p>你需要把答案排列存储在 <code>res[0]</code> 至 <code>res[n-1]</code> 中。</p>
<p>函数 <code>get_lcs</code> 的接口信息如下。</p>
<pre><code class="sh_cpp">int get_lcs(int len, int A[]);</code></pre>
<p>你需要把询问的数组存储在 <code>A[0]</code> 至 <code>A[len-1]</code> 中，数组 <code>A</code> 中的元素必须是区间 $[1,n]$ 中的整数。请保证你的所有询问都满足这个要求，不然的话可能会出现包括但不限于 <code>Wrong Answer</code>, <code>Dangerous Syscalls</code> 的评测错误。</p>
<p>如果有不清楚的地方，见样例及测评库下载，<strong>内附了样例程序</strong>。</p>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ol><li>第 $1$ 行: $n$，表示镁团手中的排列长度。</li>
<li>第 $2$ 行: $n$ 个空格隔开的整数，表示镁团手中的排列。</li>
</ol><p>在 <code>find_permutation</code> 返回后，评测系统将输出你的答案以及 <code>get_lcs</code> 的调用次数。</p>

# 样例输入



# 样例一


<h4>input</h4>
<pre>5
1 5 2 4 3

</pre>

<h4>output</h4>
<pre>1 5 2 4 3
10

</pre>

<h4>explanation</h4>
<p>样例输出的含义为 <code>find_permuation</code> 在 $10$ 次询问之后，确定了镁团手中的排列为 $1\ 5\ 2\ 4\ 3$。</p>

# 限制与约定


<p><code>find_permutation</code> 只能进行不超过 $650$ 次询问。如果超过了这个询问数量，你的程序将无法得分。</p>
<p>本题严禁任何形式的攻击交互库的行为，一旦发现，将取消相关选手的参赛资格。</p>
<p><strong>Small Task</strong>: $n \leq 30$</p>
<p><strong>Large Task</strong>: $n \leq 100$</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=531">样例交互库下载</a></p>
