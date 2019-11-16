# 题目描述

<p>在 OI 界，有一位无人不知无人不晓，OI 水平前无古人后无来者的胡策，江湖人称一眼秒题胡大爷！</p>
<p>今天胡策在研究无向图的连通性。对于一个无向图定义它的连通值为该图连通块数的阶乘。</p>
<p>为了研究连通值的性质，胡策随手画了一个 $n$ 个结点的简单无向图 $G$，结点分别编号为 $1, \dots, n$，他想统计出 $G$ 的所有生成子图的连通值之和。</p>
<p>胡策当然会做啦！但是他想考考你。你只用输出结果对 $998244353$ （$7 \times 17 \times 2^{23} + 1$，一个质数） 取模后的结果。</p>
<p>简单无向图即无重边无自环的无向图。生成子图即原图中删去若干条边（可以是 $0$ 条）后形成的图。</p>

# 输入格式


<p>第一行两个整数 $n, m$，表示 $G$ 的结点数和边数。保证 $n \geq 1，m \geq 0$。</p>
<p>接下来 $m$ 行，每行两个整数 $v, u$，表示 $v$ 号结点和 $u$ 号结点之间有一条无向边。保证 $1 \leq v, u \leq n$，保证没有重边和自环。</p>

# 输出格式


<p>一行，一个整数表示答案。</p>

# 样例一


<h4>input</h4>
<pre>6 13
1 2
1 3
2 3
1 4
4 2
3 4
5 2
3 5
5 4
6 2
6 3
6 4
6 5

</pre>

<h4>output</h4>
<pre>16974

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td>$\leq 6$</td><td rowspan="6">无</td></tr><tr><td>2</td><td rowspan="2">$\leq 10$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$\leq 17$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$\leq 20$</td><td>$G$ 为完全图</td></tr><tr><td>8</td><td rowspan="3">无</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 来源


<p>中国国家集训队互测2015 - By 吕凯风</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=94">样例数据下载</a></p>
