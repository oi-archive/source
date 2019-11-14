# 题目描述

<p>小H最近在研究随机算法。随机算法往往需要通过调用随机数生成函数（例如Pascal中的random和C/C++中的rand）来获得随机性。事实上，随机数生成函数也并不是真正的“随机”，其一般都是利用某个算法计算得来的。</p>
<p>比如，下面这个二次多项式递推算法就是一个常用算法：</p>
<p>算法选定非负整数$x_0,a,b,c,d$作为随机种子，并采用如下递推公式进行计算。</p>
<p>对于任意$i\ge 1,x_i= \left(ax_{i-1}^2+bx_{i-1}+c \right) \bmod d$。</p>
<p>这样可以得到一个任意长度的非负整数<strong>数列</strong>$\{x_i\}_{i\ge 1}$，一般来说，我们认为这个<strong>数列</strong>是随机的。</p>
<p>利用随机序列$\{x_i\}_{i\ge 1}$，我们还可以采用如下算法来产生一个$1$到$K$的<strong>随机排列</strong>$\{T_i\}_{i=1}^K$：</p>
<ol><li>初始设$T$为$1$到$K$的递增序列；</li>
<li>对$T$进行$K$次交换，第$i$次交换，交换$T_i$和$T_{(x_i \bmod i)+1}$ 的值。</li>
</ol><p>此外，小H在这$K$次交换的基础上，又<strong>额外</strong>进行了$Q$次交换操作，对于第$i$次额外交换，小H会选定两个下标$u_i$和$v_i$，并交换$T_{u_i}$和$T_{v_i}$的值。</p>
<p>为了检验这个随机排列生成算法的实用性，小H设计了如下问题：</p>
<p>小H有一个$N$行$M$列的棋盘，她首先按照上述过程，通过$N \times M+Q$次交换操作，生成了一个 $1 \sim N \times M$的随机排列$\{T_i\}_{i=1}^{N\times M}$然后将这$N\times M$个数逐行逐列依次填入这个棋盘：也就是第 $i$ 行第 $j$ 列的格子上所填入的数应为$T_{(i-1)\times M+j}$。</p>
<p>接着小H希望从棋盘的左上角，也就是第一行第一列的格子出发，<strong>每次向右走或者向下走</strong>，在不走出棋盘的前提下，走到棋盘的右下角，也就是第$N$行第$M$列的格子。</p>
<p>小H把所经过格子上的数字都记录了下来，<strong>并从小到大排序</strong>，这样，对于任何一条合法的移动路径，小H都可以得到一个长度为$N+M-1$的升序序列，我们称之为<strong>路径序列</strong>。</p>
<p>小H想知道，她可能得到的<strong>字典序最小</strong>的<strong>路径序列</strong>应该是怎样的呢？</p>

# 输入格式


<p>输入文件的第1行包含5个整数，依次为$x_0,a,b,c,d$ ，描述小H采用的随机数生成算法所需的随机种子。</p>
<p>第2行包含三个整数 $N,M,Q$ ，表示小H希望生成一个$1$到$N\times M$的排列来填入她$N$行$M$列的棋盘，并且小H在初始的$N \times M$次交换操作后，又进行了$Q$次额外的交换操作。</p>
<p>接下来$Q$行，第$i$行包含两个整数$u_i,v_i$，表示第$i$次额外交换操作将交换 $T_{u_i}$和$T_{v_i}$的值</p>

# 输出格式


<p>输出一行，包含 $N+M-1$ 个由空格隔开的正整数，表示可以得到的字典序最小的路径序列。</p>

# 样例一


<h4>input</h4>
<pre>1 3 5 1 71
3 4 3
1 7
9 9
4 9

</pre>

<h4>output</h4>
<pre>1 2 6 8 9 12

</pre>


# explanation


<p>根据输入的随机种子，小H所得到的前$12$个随机数$x_i$为：</p>
<pre>9 5 30 11 64 42 36 22 1 9 5 30
</pre>

<p>根据这$12$个随机数，小H在进行初始的$12$次交换操作后得到的排列为：</p>
<pre>6 9 1 4 5 11 12 2 7 10 3 8
</pre>

<p>在进行额外的$3$次交换操作之后，小H得到的最终的随机排列为：</p>
<pre>12 9 1 7 5 11 6 2 4 10 3 8
</pre>

<p>这个随机排列可以得到下面的棋盘：</p>
<div class="row">
<div class="col-sm-offset-4 col-sm-4">
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><tbody><tr><td style="width:40px;">12</td><td style="width:40px;">9</td><td style="width:40px;">1</td><td style="width:40px;">7</td></tr><tr><td>5</td><td>11</td><td>6</td><td>2</td></tr><tr><td>4</td><td>10</td><td>3</td><td>8</td></tr></tbody></table></div>
</div>
</div>

<p>最优路径依次经过的数字为</p>
<p>$12\rightarrow 9\rightarrow 1\rightarrow 6\rightarrow 2\rightarrow8$</p>

# 样例二


<h4>input</h4>
<pre>654321 209 111 23 70000001
10 10 0

</pre>

<h4>output</h4>
<pre>1 3 7 10 14 15 16 21 23 30 44 52 55 70 72 88 94 95 97

</pre>


# 样例三


<h4>input</h4>
<pre>123456 137 701 101 10000007
20 20 0

</pre>

<h4>output</h4>
<pre>1 10 12 14 16 26 32 38 44 46 61 81 84 101 126 128 135 140 152 156 201 206 237 242 243 253 259 269 278 279 291 298 338 345 347 352 354 383 395

</pre>


# 样例四


<p>见样例数据下载</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$N,M$的规模</th><th>$Q$的规模</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td>$2 \leq N, M \leq 8$</td><td rowspan="3">$Q = 0$</td><td rowspan="10">$0 \leq a \leq 300$<br/>$0 \leq b, c \leq 10^8$<br/>$0 \leq x_0 &lt; d \leq 10^8$<br/>$1 \leq u_i, v_i \leq N \times M$</td></tr><tr><td>2</td><td rowspan="2">$2 \leq N, M \leq 200$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$2 \leq N, M \leq 2000$</td><td rowspan="7">$0 \leq Q \leq 50000$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$2 \leq N, M \leq 5000$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$5\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>
<p>本题的空间限制是$256\texttt{MB}$，请务必保证提交的代码运行时所使用的总内存空间不超过此限制。</p>
<p>一个32位整数（例如C/C++中的int和Pascal中的Longint）为$4$字节，因而如果在程序中声明一个长度为$1024 \times 1024$的32位整型变量的数组，将会占用$4\texttt{MB}$的内存空间。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=6">样例数据下载</a></p>
