# 题目描述

<p>今天晚上有程序设计课的DDL，但是蒜斜的程设作业还一个空格都没有打过 —— 因为他的魔塔还没有通关……于是蒜斜打算向他的好朋友镁团求助。</p>
<p>镁团很愿意帮忙，所以他将自己的两个程序 <code>small.cpp</code> 和 <code>large.cpp</code> 用以下方式加密后发给了蒜斜：</p>
<ol><li>读入原程序中的所有字符，包括空格与换行。这样就得到了一个字符串 $s$。</li>
<li>把 $s$ 中的每一个字符都替换成它的 ASCII 码，这样就得到了一个数字序列 $A$。</li>
<li>随机生成一个 $0 \sim 255$ 的排列 $p$，并把所有的 $A_i$ 替换成 $p[A_i]$，这样就得到了数字数列 $B$。</li>
<li>把 $B$ 输出到密文文件中。</li>
</ol><p>现在给出这两个程序的加密结果 <code>small.encode</code>, <code>large.encode</code>。你需要帮助蒜斜还原出这两个程序原本的功能，以帮助他完成作业。</p>
<p>为了帮助你解密，蒜斜还额外提供了作业里的样例输入输出 <code>small.in</code>, <code>small.out</code>, <code>large.in</code>, <code>large.out</code>：</p>
<ol><li>已知 <code>small.cpp</code> 在输入 <code>small.in</code> 的时候会输出 <code>small.out</code>。</li>
<li>已知 <code>large.cpp</code> 在输入 <code>large.in</code> 的时候会输出 <code>large.out</code>。</li>
</ol>
# 提交方式


<p>你提交的程序需要把 <code>small.cpp</code> 与 <code>large.cpp</code> 合并到一起：输入的第一行包含一个整数 $t \in \{1,2\}$，当 $t=1$ 的时候，你的程序需要执行 <code>small.cpp</code> 的功能；当 $t=2$ 的时候，你的程序需要执行 <code>large.cpp</code> 的功能。</p>

# 样例输入一


<h4>input</h4>
<pre>1
10
1 10 7 6 2 8 9 3 5 4

</pre>

<h4>output</h4>
<pre>221

</pre>


# 样例输入二


<p>见样例数据下载。</p>

# 限制与约定


<p><strong>Small Task</strong>: $t = 1$。</p>
<p><strong>Large Task</strong>: $t = 2$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=524">加密后的程序以及运行样例下载</a></p>
