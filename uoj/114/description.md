# 题目描述

<p>由于电信技术的发展，信息的交换变得十分方便。</p>
<p>现在有 $n$ 个人，依次编号为 $1, \dots, n$。初始时第 $i$ 个人手机里存储着编号为 $i$ 的气泡熊表情。由于对自己的表情并不十分满意，他们计划进行一次大交换。</p>
<p>这 $n$ 个人中有一些朋友关系，可以抽象为一个简单无向图 $G$。简单无向图即无重边无自环的无向图。</p>
<p>每个人有三种状态：不满，激动，满意。初始时均为不满。</p>
<p>有一个神秘人，操纵他们按如下方式行动：</p>
<pre><code class="sh_php">function dfs(v):
    v 变为激动状态
    for u = 1, ..., n:
        if v 和 u 是朋友 and u 处于不满状态:
            交换 v 和 u 的手机中的气泡熊表情
            dfs(u)
    v 变为满意状态

for v = 1, ..., n:
    if v 处于不满状态:
        dfs(v)</code></pre>
<p>一万万年后，一位考古学家调查了最终每个手机中存储的气泡熊表情的编号，想要复原出朋友关系图 $G$。然而这几乎是不可能的，所以他想知道有多少种可能的 $G$。</p>

# 输入格式


<p>第一行一个正整数 $n$。</p>
<p>第二行包含 $n$ 个整数 $a_1, \dots, a_n$，表示最终第 $i$ 个人的手机上存储的气泡熊表情编号。保证 $a_1, \dots, a_n$ 是一个 $1$ 到 $n$ 的排列。</p>

# 输出格式


<p>一行，一个整数表示 $G$ 的数量，你只用输出答案对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）取模后的结果。</p>

# 样例一


<h4>input</h4>
<pre>3
2 3 1

</pre>

<h4>output</h4>
<pre>2

</pre>

<h4>explanation</h4>
<p>共以下两种：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/114/sample.png" alt="样例解释图"/></p>

# 样例二


<h4>input</h4>
<pre>9
7 2 9 1 3 8 6 5 4

</pre>

<h4>output</h4>
<pre>3528

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
</tr></thead><tbody><tr><td>1</td><td>$n \leq 6$</td></tr><tr><td>2</td><td rowspan="2">$n \leq 9$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="4">$n \leq 50$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$n \leq 500$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=114">样例数据下载</a></p>
