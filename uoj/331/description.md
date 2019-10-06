# 题目描述

<p>策策同学特别喜欢逛公园。 公园可以看成一张 $N$ 个点 $M$ 条边构成的有向图，且没有自环和重边。其中 $1$ 号点是公园的入口， $N$ 号点是公园的出口，每条边有一个非负权值，代表策策经过这条边所要花的时间。</p>
<p>策策每天都会去逛公园，他总是从 $1$ 号点进去，从 $N$ 号点出来。</p>
<p>策策喜欢新鲜的事物，他不希望有两天逛公园的路线完全一样，同时策策还是一个特别热爱学习的好孩子，他不希望每天在逛公园这件事上花费太多的时间。如果 $1$ 号点到 $N$ 号点的最短路长为 $d$，那么策策只会喜欢长度不超过 $d+K$ 的路线。</p>
<p>策策同学想知道总共有多少条满足条件的路线，你能帮帮他吗？</p>
<p>为避免输出过大，答案对 $P$ 取模。</p>
<p>如果有无穷多条合法的路线，请输出 $-1$ 。</p>

# 输入格式


<p>第一行包含一个整数 $T$, 代表数据组数。</p>
<p>接下来 $T$ 组数据，对于每组数据：</p>
<p>第一行包含四个整数 $N,M,K,P$， 每两个整数之间用一个空格隔开。</p>
<p>接下来 $M$ 行，每行三个整数 $a_i,b_i,c_i$，代表编号为 $a_i,b_i$ 的点之间有一条权值为 $c_i$ 的有向边，每两个整数之间用一个空格隔开。</p>

# 输出格式


<p>输出文件包含 $T$ 行，每行一个整数代表答案。</p>

# 样例一


<h4>input</h4>
<pre>2
5 7 2 10
1 2 1
2 4 0
4 5 2
2 3 2
3 4 1
3 5 2
1 5 3
2 2 0 10
1 2 0
2 1 0

</pre>



<h4>output</h4>
<pre>3
-1

</pre>

<h4>explanation</h4>
<p>对于第一组数据，最短路为 $3$。</p>
<p>$1 - 5$ , $1 - 2 - 4 - 5$ , $1 - 2 - 3 - 5$ 为 $3$ 条合法路径。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>对于不同的测试点，我们约定各种参数的规模<strong>不会超过</strong>如下</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th> 测试点编号</th><th> $T$ </th><th> $N$ </th><th> $M$ </th><th> $K$ </th><th> 是否有0边 </th></tr></thead><tbody><tr><td> 1</td><td> 5 </td><td> 5 </td><td> 10 </td><td>0 </td><td> 否</td></tr><tr><td> 2</td><td> 5 </td><td> 1000 </td><td> 2000 </td><td> 0</td><td> 否</td></tr><tr><td> 3</td><td> 5 </td><td> 1000 </td><td> 2000 </td><td> 50</td><td>否 </td></tr><tr><td> 4</td><td> 5 </td><td> 1000 </td><td> 2000 </td><td> 50</td><td> 否</td></tr><tr><td> 5</td><td> 5 </td><td> 1000 </td><td> 2000 </td><td> 50</td><td> 否</td></tr><tr><td> 6</td><td> 5 </td><td> 1000 </td><td> 2000 </td><td> 50</td><td> 是</td></tr><tr><td> 7</td><td> 5 </td><td> 100000 </td><td> 200000</td><td>0 </td><td> 否</td></tr><tr><td> 8</td><td> 3 </td><td> 100000 </td><td> 200000</td><td> 50</td><td> 否</td></tr><tr><td> 9</td><td> 3 </td><td> 100000 </td><td> 200000</td><td> 50</td><td> 是</td></tr><tr><td> 10</td><td> 3 </td><td> 100000 </td><td> 200000</td><td> 50</td><td> 是</td></tr></tbody></table></div>

<p>对于 100% 的数据，$1 \le P \le 10^9$，$1 \le a_i, b_i \le N$, $0 \le c_i \le 1000$。</p>
<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=331">样例数据下载</a></p>
