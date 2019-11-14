# 题目描述

<p>iOS 用户和 Android 用户一定对 App 管理器不会陌生。</p>
<p>“啊啊啊！手机空间又不够了” 买了低端机的奸笑熊欲哭无泪。</p>
<p>奸笑熊常有的文件格式一共有 $n$ 种，分别编号为 $1, \dots, n$。奸笑熊有 $m$ 个 App，分别编号为 $1, \dots, m$。其中 $i$ 号 App 可以把 $a_i$ 号文件格式转换成 $b_i$ 号文件格式，或者把 $b_i$ 号文件格式转换成 $a_i$ 号文件格式。</p>
<p>App 管理器最近推出了一个新功能：卸载一半！于是奸笑熊决定把每个 App 都卸载一半。</p>
<p>对于 $i$ 号 App，你可以决定你卸载哪一半：</p>
<ol><li>把 $a_i$ 号文件格式转换成 $b_i$ 号文件格式。</li>
<li>把 $b_i$ 号文件格式转换成 $a_i$ 号文件格式。</li>
</ol><p>奸笑熊希望，把所有 App 都卸载一半之后并不影响使用。即，对于任意两个文件格式 $i, j$，仍能通过一个或多个 App 把 $i$ 号文件格式直接或间接转换成 $j$ 号文件格式。</p>
<p>现在奸笑熊已经把部分 App 卸载一半了，请你给出一组卸载剩下的 App 的方案满足条件。</p>

# 输入格式


<p>第一行两个整数 $n, m$，表示文件格式的数量和 App 的数量。保证 $n \geq 1, m \geq 0$。</p>
<p>接下来 $m$ 行，每行三个整数 $a_i, b_i, t_i$，表示一个 App。如果 $t_i = 0$ 则表示这个 App 还没被卸载一半，如果 $t_i = 1$ 则表示这个 App 已经被卸载一半，现在只能把 $a_i$ 号格式转换为 $b_i$ 号格式。保证 $1 \leq a_i, b_i \leq n$ 且 $a_i \neq b_i$。</p>

# 输出格式


<p>输出 $m$ 行，每行一个整数表示卸载的是哪一半。</p>
<p>如果这个 App 还没被卸载一半，输出 $0$ 表示保留 “把 $a_i$ 号文件格式转换成 $b_i$ 号文件格式” 的这一半，否则表示保留 “把 $b_i$ 号文件格式转换成 $a_i$ 号文件格式” 的这一半。</p>
<p>如果这个 App 已经被卸载一半，那么直接输出 $0$。</p>
<p>保证至少存在一组方案。</p>

# 样例一


<h4>input</h4>
<pre>4 5
1 2 0
2 3 0
1 3 1
4 1 1
4 3 0

</pre>

<h4>output</h4>
<pre>0
0
0
0
1

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n, m$ 的规模</th><th>特殊限制</th></tr></thead><tbody><tr><td>1</td><td rowspan="3">$n, m \leq 17$</td><td rowspan="3">无</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="7">$n, m \leq 5000$</td><td rowspan="3">所有 $t_i = 0$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">无</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=134">样例数据下载</a></p>
