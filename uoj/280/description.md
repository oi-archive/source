# 题目描述

<p>最终吉米多出题斯基没有找到优质的题目，于是高产的吉米多出题斯基决定自己出一道。</p>
<p>首先，吉米多出题斯基脑洞了一道难度为 $h_1$ 的题目，然而吉米多出题斯基觉得太水了，于是把这题稍微改了改变成了一道难度为 $h_2$ 的。然而吉米多出题斯基还是觉得太水了，又稍微改了改变成了难度为 $h_3$ 的。如此进行下去吉米多出题斯基脑洞出了 $n$ 个版本的题目，难度分别为 $h_1, \dots, h_n$。</p>
<p>由于吉米多出题斯基在脑洞的时候只是随便改了改题目条件，所以每次改题并不一定会变难。但神奇的是，每次产生一个新版本的题目后，吉米多出题斯基手上所有版本的题目难度的中位数不会降低。</p>
<p>很快吉米多出题斯基出好了题，造好了 UOI，选手们纷纷阵亡。多年后吉米多出题斯基再看到自己曾经出的这道题时感叹道：“都是回忆啊……”</p>
<p>可是吉米多出题斯基突然发现自己只记得脑洞过程产生的 $n$ 个版本难度是 $a_1, \dots, a_n$，却不记得每个 $a_i$ 对应的是第几个版本了。</p>
<p>吉米多出题斯基日理万机没有时间再细想了，于是他找到了你 —— 风璃殇做不出题耶维奇，请你帮助吉米多出题斯基把 $a_1, \dots, a_n$ 排列顺序，给出一组满足条件且字典序最大的 $h_1, \dots, h_n$ 吧！</p>
<p>对于一个数列 $v_1, \dots, v_m$，若 $m$ 为奇数则定义中位数为从小到大第 $\lceil m / 2 \rceil$ 的数；若 $m$ 为偶数则定义中位数为从小到大第 $m/2$ 和第 $m/2+1$ 的数的平均值。</p>

# 输入格式


<p>第一行一个正整数 $n$。</p>
<p>接下来一行 $n$ 个整数 $a_1, \dots, a_n$。</p>

# 输出格式


<p>一行，$n$ 个整数表示你找到的字典序最大的 $h_1, \dots, h_n$。</p>
<p>如果无解，输出卖萌表情 &#34;<samp>QwQ</samp>&#34;。</p>

# 样例一


<h4>input</h4>
<pre>5
1 2 3 4 5

</pre>

<h4>output</h4>
<pre>1 3 2 5 4

</pre>

<h4>explanation</h4>
<p>中位数依次为：$\{1, 2, 2, 2.5, 3\}$。</p>

# 样例二


<h4>input</h4>
<pre>8
1 2 2 3 3 3 4 4

</pre>

<h4>output</h4>
<pre>3 3 4 3 4 2 2 1

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$n$</th>
<th>其他约定</th>
</tr></thead><tbody><tr><td>1</td><td>10</td><td>$1 \leq n \leq 10$</td><td>无</td></tr><tr><td>2</td><td>10</td><td>$1 \leq n \leq 100$</td><td>无</td></tr><tr><td>3</td><td>20</td><td>$1 \leq n \leq 2000$</td><td>无</td></tr><tr><td>4</td><td>30</td><td>$1 \leq n \leq 10^5$</td><td>$a_i$ 互不相同</td></tr><tr><td>5</td><td>30</td><td>$1 \leq n \leq 10^5$</td><td>无</td></tr></tbody></table></div>

<p>对于所有数据，满足 $1 \le a_i \le 10^9$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=280">样例数据下载</a></p>
