# 题目描述

<p>小O是一个热爱短代码的选手。在缩代码方面，他是一位身经百战的老手。世界各地的OJ上，很多题的最短解答排行榜都有他的身影。这令他感到十分愉悦。</p>
<p>最近，他突然发现，很多时候自己的程序明明看起来比别人的更短，实际代码量却更长。这令他感到很费解。经过一番研究，原来是因为他每一行的缩进都全是由空格组成的，大量的空格让代码量随之增大。</p>
<p>现在设小O有一份 $n$ 行的代码，第 $i$ 行有 $a_i$ 个空格作为缩进。</p>
<p>为解决这一问题，小O要给自己文本编辑器设定一个正整数的默认TAB宽度 $x$，然后对于每一行，编辑器从头至尾不断把连续 $x$ 个空格替换成一个TAB，直到剩余空格数不足 $x$ 个。</p>
<p>最终缩进所占代码量为空格数与TAB数的和。请你帮小O选择一个合适的 $x$，使得缩进所占代码量最小。</p>

# 输入格式


<p>第一行一个正整数 $n$，表示代码行数。</p>
<p>接下来 $n$ 行，第 $i$ 行一个正整数 $a_i$，为初始时第 $i$ 行缩进的空格个数。</p>

# 输出格式


<p>一行一个整数，表示缩进所占代码量最小是多少。</p>
<p>C/C++ 输入输出 long long 时请用 <code>%lld</code>。C++ 可以直接使用 cin/cout 输入输出。</p>

# 样例一


<h4>input</h4>
<pre>3
5
8
8

</pre>

<h4>output</h4>
<pre>6

</pre>

<h4>explanation</h4>
<p>令默认TAB宽度为4即可。</p>

# 样例二


<h4>input</h4>
<pre>10
2
3
5
7
11
13
17
19
23
29

</pre>

<h4>output</h4>
<pre>45

</pre>


# 样例三


<p>见样例数据下载</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
<th>$a_i$的大小</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n \leq 10^3$</td><td rowspan="2">$a_i \leq 2000$</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="2">$n \leq 10^5$</td><td rowspan="2">$a_i \leq 2000$</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="3">$n \leq 10^5$</td><td rowspan="3">$a_i \leq 10^5$</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$n \leq 10^6$</td><td rowspan="3">$a_i \leq 10^6$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=21">样例数据下载</a></p>
