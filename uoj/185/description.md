# 题目描述

<p>小Y是一个心灵手巧的女孩子，她喜欢手工制作一些小饰品。她有 $n$ 颗小星星，用 $m$ 条彩色的细线串了起来，每条细线连着两颗小星星。有一天她发现，她的饰品被破坏了，很多细线都被拆掉了。这个饰品只剩下了 $n-1$ 条细线，但通过这些细线，这颗小星星还是被串在一起，也就是这些小星星通过这些细线形成了树。</p>
<p>小Y找到了这个饰品的设计图纸，她想知道现在饰品中的小星星对应着原来图纸上的哪些小星星。如果现在饰品中两颗小星星有细线相连，那么要求对应的小星星原来的图纸上也有细线相连。</p>
<p>小Y想知道有多少种可能的对应方式。只有你告诉了她正确的答案，她才会把小饰品做为礼物送给你呢。</p>

# 输入格式


<p>第一行包含个 $2$ 正整数 $n,m$ ，表示原来的饰品中小星星的个数和细线的条数。</p>
<p>接下来 $m$ 行，每行包含 $2$ 个正整数 $u,v$，表示原来的饰品中小星星 $u$ 和 $v$ 通过细线连了起来。这里的小星星从 $1$ 开始标号。保证 $u \neq v$，且每对小星星之间最多只有一条细线相连。</p>
<p>接下来行 $n-1$，每行包含个 $2$ 正整数 $u,v$，表示现在的饰品中小星星 $u$ 和 $v$ 通过细线连了起来。保证这些小星星通过细线可以串在一起。</p>

# 输出格式


<p>输出共 $1$ 行，包含一个整数表示可能的对应方式的数量。如果不存在可行的对应方式则输出 $0$。</p>

# 样例一


<h4>input</h4>
<pre>4 3
1 2
1 3
1 4
4 1
4 2
4 3

</pre>

<h4>output</h4>
<pre>6

</pre>

<h4>explanation</h4>
<p>现在的饰品中第 $4$ 颗小星星与原来的第 $1$ 颗对应，现在的第 $1,2,3$ 颗小星星可以与原来的第 $2,3,4$ 颗小星星对应，所以有 $6$ 种对应方式。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>各测试点满足以下约定：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点</th>
<th>$n$</th>
<th>$m$</th>
<th>约定</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$=10$</td><td rowspan="10">$\leq \frac {n(n-1)} {2}$</td><td rowspan="2">无</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="2">$=17$</td><td rowspan="2">保证新的饰品中每颗小星星与至多两颗小星星相连</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="2">$=14$</td><td rowspan="2">无</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="2">$=16$</td><td rowspan="1">保证答案不超过 $10^5$</td></tr><tr><td>8</td><td rowspan="3">无</td></tr><tr><td>9</td><td rowspan="2">$=17$</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=185">样例数据下载</a></p>
