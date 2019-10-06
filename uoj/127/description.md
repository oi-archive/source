# 题目描述

<p>在实现程序自动分析的过程中，常常需要判定一些约束条件是否能被同时满足。</p>
<p>考虑一个约束满足问题的简化版本：假设 $x_1, x_2, x_3, \dots$ 代表程序中出现的变量，给定 $n$ 个形如 $x_i = x_j$ 或 $x_i \neq x_j$ 的变量相等/不等的约束条件，请判定是否可以分别为每一个变量赋予恰当的值，使得上述所有约束条件同时被满足。例如，一个问题中的约束条件为：$x_1 = x_2$，$x_2 = x_3$，$x_3 = x_4$，$x_1 \neq x_4$，这些约束条件显然是不可能同时被满足的，因此这个问题应判定为不可被满足。</p>
<p>现在给出一些约束满足问题，请分别对它们进行判定。</p>

# 输入格式


<p>输入文件的第 $1$ 行包含 $1$ 个正整数 $t$，表示需要判定的问题个数。注意这些问题之间是相互独立的。</p>
<p>对于每个问题，包含若干行：</p>
<p>第 $1$ 行包含 $1$ 个正整数 $n$，表示该问题中需要被满足的约束条件个数。</p>
<p>接下来 $n$ 行，每行包括 $3$ 个整数 $i, j, e$，描述 $1$ 个相等/不等的约束条件，相邻整数之间用单个空格隔开。若 $e = 1$，则该约束条件为 $x_i = x_j$；若 $e = 0$，则该约束条件为 $x_i \neq x_j$。</p>

# 输出格式


<p>输出文件包括 $t$ 行。</p>
<p>输出文件的第 $k$ 行输出一个字符串 “<samp>YES</samp>” 或者 “<samp>NO</samp>”（不包含引号，字母全部大写），“<samp>YES</samp>” 表示输入中的第 $k$ 个问题判定为可以被满足，“<samp>NO</samp>” 表示不可被满足。</p>

# 样例一


<h4>input</h4>
<pre>2
2
1 2 1
1 2 0
2
1 2 1
2 1 1

</pre>

<h4>output</h4>
<pre>NO
YES

</pre>

<h4>explanation</h4>
<p>在第一个问题中，约束条件为：$x_1 = x_2, x_1 \neq x_2$。这两个约束条件互相矛盾，因此不可被同时满足。</p>
<p>在第二个问题中，约束条件为：$x_1 = x_2, x_2 = x_1$。这两个约束条件是等价的，可以被同时满足。</p>

# 样例二


<h4>input</h4>
<pre>2
3
1 2 1
2 3 1
3 1 1
4
1 2 1
2 3 1
3 4 1
1 4 0

</pre>

<h4>output</h4>
<pre>YES
NO

</pre>

<h4>explanation</h4>
<p>在第一个问题中，约束条件有三个：$x_1 = x_2$，$x_2 = x_3$，$x_3 = x_1$。只需赋值使得 $x_1 = x_2 = x_3$，即可同时满足所有的约束条件。</p>
<p>在第二个问题中，约束条件有四个：$x_1 = x_2$，$x_2 = x_3$，$x_3 = x_4$，$x_1 \neq x_4$。由前三个约束条件可以推出 $x_1 = x_2 = x_3 = x_4$，然而最后一个约束条件却要求 $x_1 \neq x_4$，因此不可被满足。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$ 的规模</th><th>$i, j$ 的规模</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td rowspan="2">$1 \leq n \leq 10$</td><td rowspan="7">$1 \leq i,j \leq 10000$</td><td rowspan="10">$1 \leq t \leq 10$，$e \in \{0, 1\}$</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="2">$1 \leq n \leq 100$</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="3">$1 \leq n \leq 100000$</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$1 \leq n \leq 100000$</td><td rowspan="3">$1 \leq i,j \leq 1000000000$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=127">样例数据下载</a></p>
