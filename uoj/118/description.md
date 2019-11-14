# 题目描述

<p>高中，高中，短暂的三年。NOI是高中结业考试，而高考在每年暑假举行。</p>
<p>高二暑假，这是你最后一次参加高考的机会。你已经为了高考停课很久了，OI的知识很久没管了。你并没有能力用一年时间补起别人三年的OI课程。这是你的最后一战，如果你失败了，可能就不能工地搬砖只能去清华了。</p>
<p>这天你背上行囊赴京赶考。此时全国交通主要靠瞬间传送装置。全国交通网络可以抽象为一张 $n$ 行 $m$ 列的网格图。行依次编号为 $1, \dots, n$，列依次编号为 $1, \dots, m$。</p>
<p>有 $n + m$ 个为 $0$ 或 $1$ 的整数 $a_1, \dots, a_n, b_1, \dots, b_m$。对于 $1 \leq i \leq n$，$1 \leq j \leq m$，如果 $a_i = b_j$ 那么网格图上第 $i$ 行第 $j$ 列上标着 $0$ 否则标着 $1$。</p>
<p>你的家在第 $x_s$ 行第 $y_s$ 列，高考考场在第 $x_e$ 行第 $y_e$ 列。现在你想从家出发到高考考场去。每次你可以：</p>
<ol><li>向上移动一行。（如果你在第一行那么移动后会到最后一行去）</li>
<li>向下移动一行。（如果你在最后一行那么移动后会到第一行去）</li>
<li>向左移动一列。（如果你在第一列那么移动后会到最后一列去）</li>
<li>向右移动一列。（如果你在最后一列那么移动后会到第一列去）</li>
</ol><p>对于每次移动，如果移动前的格子上标的数跟移动后的格子上标的数不同，那么就要耗费 $1$ 分钟时间等待瞬移装置调整配置，否则不耗时间。</p>
<p>现在你想知道你从家出发到高考考场最少需要花多长时间。</p>

# 输入格式


<p>第一行两个正整数 $n, m$，表示网格图为 $n$ 行 $m$ 列。</p>
<p>第二行 $n$ 个整数，分别表示 $a_1, \dots, a_n$。保证 $a_1, \dots, a_n \in \{0, 1\}$。</p>
<p>第三行 $m$ 个整数，分别表示 $b_1, \dots, b_m$。保证 $b_1, \dots, b_m \in \{0, 1\}$。</p>
<p>接下来一个正整数 $q$。</p>
<p>接下来 $q$ 行，每行四个整数 $x_s, y_s, x_e, y_e$。表示询问如果你的家在第 $x_s$ 行第 $y_s$ 列，高考考场在第 $x_e$ 行第 $y_e$ 列时的最少花费时间。</p>

# 输出格式


<p>共 $q$ 行，每行一个整数表示最少花费多少分钟。</p>

# 样例一


<h4>input</h4>
<pre>1 2
1
0 1
2
1 2 1 2
1 1 1 2

</pre>

<h4>output</h4>
<pre>0
1

</pre>


# 样例二


<h4>input</h4>
<pre>10 10
1 1 0 1 1 1 0 1 0 1
0 0 1 0 1 1 0 0 1 0
4
7 6 4 8
8 2 1 4
8 5 7 4
3 1 9 5

</pre>

<h4>output</h4>
<pre>2
4
2
5

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n, m$的规模</th>
<th>$q$的规模</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="3">$n, m \leq 100$</td><td rowspan="3">$q \leq 10$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="2">$n \leq 10^5, m = 1$</td><td rowspan="2">$q \leq 10^5$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">$n, m \leq 10^5$</td><td rowspan="5">$q \leq 10^5$</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=118">样例数据下载</a></p>
