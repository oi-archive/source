# 题目描述

<p>红包是一个热爱数学的男孩子。今天是万圣节，红包正在家里捣鼓一个长度为 $n$ 数列。</p>
<p>这时候一群熊孩子们敲开了红包家的门，他们高呼着“不用给糖，只要捣蛋”的口号把红包的数列打乱了。这让红包很难过，于是他打算恢复这个数列。</p>
<p>但是因为这个数列实在是太长了，所以他已经不记得这个数列原来是什么样的了。于是他采用了一个折中的方法：把数列恢复成他最喜欢的样子。</p>
<p>对于一个数列 $A_1, A_2, \dots, A_n$ 和一个数列 $B_1, B_2, \dots, B_m$，若存在一组 $p_1, p_2, \dots, p_m$ 满足 $1 \leq p_1 &lt; p_2 &lt; \dots &lt; p_m \leq n$ 且对于任意的 $1 \leq i \leq m$ 有 $B_i = A_{p_i}$，则称 $B$ 是 $A$ 的子序列。若 $B$ 对于任意 $1 &lt; i &lt; m$ 还满足 $B_i - B_{i - 1} = B_{i + 1} - B_i$ 则称 $B$ 是 $A$ 的等差子序列。</p>
<p>红包不喜欢等差数列，于是一个数列的等差子序列数量越少，他越喜欢。</p>
<p>现在他把被打乱后的数列 $A$ 交给了你，你需要将 $A$ 中元素重新排列得到使得等差子序列数量最少，两个等差子序列不同当且仅当 $m$ 不同或者存在 $k$ 使得 $p_k$ 不同。</p>

# 输入格式


<p>第一行是一个正整数 $n$，表示数列的长度。</p>
<p>第二行是 $n$ 个正整数，表示 $A_1, A_2, \dots, A_n$。</p>

# 输出格式


<p>仅一行，输出 $n$ 个整数 $p_1, p_2, \dots, p_n$。其中第 $i$ 个数 $p_i$ 表示重新排列后的数列中第 $i$ 个元素在原数列 $A$ 中是第 $p_i$ 个元素。</p>
<p>如果存在多种满足条件的方案，输出任意一个就行。</p>

# 样例一


<h4>input</h4>
<pre>6
1 3 3 3 4 5

</pre>

<h4>output</h4>
<pre>2 1 6 4 3 5

</pre>

<h4>explanation</h4>
<p>你恢复的数列是：$\{3, 1, 5, 3, 3, 4\}$，它的等差子序列是所有长度小于等于 $2$ 的子序列和 $\{3, 3, 3\}$。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$ 的规模</th><th>其他约定</th></tr></thead><tbody><tr><td>1</td><td rowspan="2">$n \leq 10$</td><td rowspan="2"></td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="8">$n \leq 500$</td><td rowspan="2">$A_i \leq 10$</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="2">$A$ 是一个 $1$ 到 $n$ 的排列</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4"></td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有数据，都有 $A_i \leq 10^9$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=143">样例数据下载</a></p>
