# 题目描述

<p>猪小侠最近学习了字符串相关理论，现在他遇到了这样一个题：
维护一个动态字符串 $s[1\ldots n]$，字符串的字符集是所有 $|x| \le 10^9$ 的整数。要求支持两个操作：</p>
<ol><li>输入 $l, r, d$，对于所有 $l \le i \le r$，将 $s[i]$ 修改为 $s[i] + d$，<strong>注意 $d$ 可能是负数</strong>。</li>
<li>输入 $l, r$，输出子串 $s[l\ldots r]$ 的<strong>字典序最小的后缀</strong>的起点位置。即，如果最小后缀是 $s[p\ldots r], (l \le p \le r)$，请输出 $p$。</li>
</ol>
# 输入格式


<p>第一行两个非负整数 $n, q$。</p>
<p>接下来一行包含 $n$ 个整数，表示初始时的字符串。</p>
<p>接下来 $q$ 行，每行为 $1~l~r~d$ 或 $2~l~r$，分别表示两种操作。</p>

# 输出格式


<p>对于所有的查询操作按顺序输出答案。</p>

# 样例一


<h4>input</h4>
<pre>5 5
3 2 1 4 3
2 1 5
1 2 4 2
2 1 5
1 2 5 1
2 1 5

</pre>

<h4>output</h4>
<pre>3
5
1

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>其他约定</th>
</tr></thead><tbody><tr><td>1</td><td>$\le 300$</td><td>$\le 300$</td><td rowspan="3">无</td></tr><tr><td>2</td><td rowspan="2">$\le 2 \times 10^4$</td><td rowspan="2">$\le 10^4$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="7">$\le 2 \times 10^5$</td><td rowspan="7">$\le 3 \times 10^4$</td><td rowspan="2">只有第二类操作</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="2">数据随机生成</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">无</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于 100% 的数据，$1 \le l \le r \le n, |d| \le 10^3, |s_i| \le 10^8$。</p>
<p>注意，6 和 7 两个测试数据在随机生成时，$s_i$ 在 $[0, 1]$ 中随机，$d$ 在 $\pm 1$ 中随机。操作种类和操作区间都是等概率随机的。</p>
<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=296">样例数据下载</a></p>
