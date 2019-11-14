# 题目描述

<p>在你的帮助下，SingleDog们终于进入了计算中心内部，他们惊讶的发现，计算中心的核心——AlphaGo的三台主机所在的地方，居然是一个多维空间！</p>
<p>简单点说，核心是 $n \leq 5$ 维空间里一个点集，位于一个 $n$ 维长方体的方框内部。方框内部由所有满足 $l_i\le x_i \le r_i$ 的点 $(x_1,x_2,\cdots,x_n)$ 构成，而核心则由所有位于方框内部且满足 $x_i - x_j \ge a_{i,j}$ 的点$(x_1, x_2 \cdots,x_n)$ 构成，其中 $l_i,r_i,a_{i,j}$ 均为给定的整数。</p>
<p>现在SingleDog们想知道的就是这个核心的“体积”占方框的体积的比例。</p>
<p>为了方便理解题意，一个<strong>等价</strong>的题目描述是：</p>
<p>设 $x_1,x_2,\cdots,x_n$ 是 $n$ 个实数变量，其中第 $i$ 个变量 $x_i$ 在区间 $[l_i,r_i]$ 内均匀随机生成，所有 $l_i$ 和 $r_i$ 均为给定的整数且 $l_i\le r_i$（约定 $l_i=r_i$ 时，$[l_i,r_i]$ 表示单元素集合 $\{l_i\}$）。</p>
<p>给定 $n\times n$ 的整数矩阵，矩阵的每个元素代表一个约束，其中第 $i$ 行第 $j$ 列的元素 $a_{i,j}$ 代表约束
$$x_i-x_j\ge a_{i,j}$$</p>
<p>求这 $n\times n$ 个约束同时被满足的概率。</p>

# 输入格式


<p>第一行包含一个正整数 $n$，表示实数变量个数。</p>
<p>接下来 $n$ 行，第 $i$ 行两个整数 $l_i,r_i$，描述第 $i$ 个区间。</p>
<p>接下来 $n$ 行，每行 $n$ 个整数，给出整数矩阵 $a_{i,j}$。</p>

# 输出格式


<p>输出一行，包含一个实数，表示所求的概率。</p>
<p>你的答案与参考答案的绝对误差不超过 $10^{-7}$ 时被认为是正确的。</p>

# 样例一


<h4>input</h4>
<pre>1
0 10
-10

</pre>

<h4>output</h4>
<pre>1.000000000000

</pre>

<h4>explanation</h4>
<p>无论变量 $x_1$ 的值是多少，约束 $x_1-x_1\ge-10$ 恒成立，故满足约束的概率为 $1$。</p>

# 样例二


<h4>input</h4>
<pre>2
5 5
3 7
0 1
-3 0

</pre>

<h4>output</h4>
<pre>0.2500000000

</pre>

<h4>explanation</h4>
<p>$x_1=5$，$3\le x_2\le 7$。仅当 $3\le x_2\le 4$ 时才能同时满足所有约束，故满足所有约束的概率为 ${1\over 4}=0.25$。</p>

# 样例三


<h4>input</h4>
<pre>2
4 5
3 6
-10 2
-10 -10

</pre>

<h4>output</h4>
<pre>0.0000000000

</pre>

<h4>explanation</h4>
<p>满足 $4\le x_1\le 5$，$3\le x_2\le 6$ 的 $x_1,x_2$ 有无穷多个，但只有一组值 $x_1=5,x_2=3$ 是满足约束的，故满足约束的概率为 $0$。</p>

# 样例四


<h4>input</h4>
<pre>2
3 10
0 8
-1 1
-7 0

</pre>

<h4>output</h4>
<pre>0.5982142857

</pre>

<h4>explanation</h4>
<p>满足约束的概率为 ${67\over 112}$。你输出的答案应当在 $[{67\over 112}-10^{-7},{67\over 112}+10^{-7}]$ 范围内。</p>

# 样例五


<h4>input</h4>
<pre>3
0 10
2 10
2 9
0 -9 -10
4 0 -3
1 -4 0

</pre>

<h4>output</h4>
<pre>0.1491071429

</pre>


# 样例六


<h4>input</h4>
<pre>4
0 5
0 9
4 10
0 5
0 -8 -9 -5
1 0 -4 3
1 -6 0 3
-4 -10 -10 0

</pre>

<h4>output</h4>
<pre>0.2622839506

</pre>


# 样例七


<h4>input</h4>
<pre>5
0 10
0 10
4 4
0 9
0 7
-10 -9 -10 -10 -10
-10 -10 2 -10 -10
-10 -10 -10 1 -10
-10 -10 -10 -10 -5
-10 -10 -10 -10 -10

</pre>

<h4>output</h4>
<pre>0.1191269841

</pre>


# 样例八


<h4>input</h4>
<pre>5
0 2
1 8
7 10
2 7
6 10
0 -10 -10 -9 -10
-10 0 -7 -4 -8
3 3 0 1 -6
3 -6 -5 0 -5
-2 3 -9 1 0

</pre>

<h4>output</h4>
<pre>0.1713095238

</pre>


# 限制与约定


<p>由于一些原因，本题使用捆绑测试。每个子任务有若干个测试点，分为 8 个子任务，你只有通过一个子任务的所有测试点才能得到这个子任务的分数。</p>
<div class="table-responsive">
 <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
    <th>分值</th>
    <th>$n$</th>
    <th>其它限制</th>
   </tr></thead><tbody><tr><td>1</td>
    <td>5</td>
    <td>$=1$</td>
    <td>无</td>
   </tr><tr><td>2</td>
    <td>10</td>
    <td rowspan="3">$=2$</td>
    <td>$l_1=r_1$</td>
   </tr><tr><td>3</td>
    <td>20</td>
    <td>若 $j\ne i+1$，则 $a_{i,j}=-10$</td>
   </tr><tr><td>4</td>
    <td>15</td>
    <td rowspan="3">无</td>
   </tr><tr><td>5</td>
    <td>10</td>
    <td>$=3$</td>
   </tr><tr><td>6</td>
    <td>10</td>
    <td>$=4$</td>
   </tr><tr><td>7</td>
    <td>20</td>
    <td rowspan="2">$=5$</td>
    <td>若 $j\ne i+1$，则 $a_{i,j}=-10$</td>
   </tr><tr><td>8</td>
    <td>10</td>
    <td>无</td>
   </tr></tbody></table></div>

<p>对于所有数据，$1\le n\le 5$，$0\le l_i\le r_i\le 10$，$-10\le a_{i,j}\le 10$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=352">样例数据下载</a></p>
