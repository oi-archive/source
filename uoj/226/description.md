# 题目描述

<p>各位观众，各位观众，您现在收看的是第 666 届跳蚤奥运会的比赛现场。在刚刚的五子棋比赛中，天才跳高小将“最强跳蚤”靠着“最强跳蚤跳跳跳”和经验丰富的伏特跳蚤国王大战了三天三夜，最后战成 $233:233$ 平。考虑到迟迟不能决出胜者，比赛组委会决定临时更换比赛项目，而被选中的则是在跳蚤大陆流行已久的运动项目——环城马拉松。</p>
<p>首先我来介绍一下比赛场地，微分方城有 $n$ 个路口，编号为 $1, \dots, n$。共有 $m$ 对路口间有无向道路相连，其中第 $i$ 对为 $u_i$ 号路口与 $v_i$ 号路口，且他们之间有 $t_i$ 条<strong>不同的无向道路</strong>。微分方城内<strong>任意两个路口都可以通过道路直接或间接到达</strong>，但由于微分方城的财政问题，有道路相连的路口对数 $m$ 不会超过 $n$。</p>
<p>现在，最强跳蚤和跳蚤国王的马拉松需要绕微分方城一周，即从某个起始点出发经过若干道路，再回到起始点。并且组委会规定，每条道路必须经过恰好一次。</p>
<p>那么问题来了，请观众朋友们数一数，一共有多少种环城马拉松的路线？最早给出答案的观众可以获得大火车一列哦。</p>
<p>路线可以认为是一个从某个点出发，由经过的道路<strong>编号</strong>和<strong>方向</strong>组成的序列。两条路线被认为是<strong>相同的</strong>当且仅当两序列相同，或更换起始边后两序列相同。请求出本质不同的路线的条数。</p>

# 输入格式


<p>第一行两个正整数 $n,m$，意义如前所述。</p>
<p>接下来 $m$ 行，每行三个正整数 $u_i,v_i,t_i$，表示 $u_i$ 到 $v_i$ 有 $t_i$ 条不同的无向道路。保证 $1 \le v_1, u_i \le n$，保证 $v_i \ne u_i$，且一对路口不会被重复描述。</p>

# 输出格式


<p>输出一行一个整数表示答案对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数） 取模后的结果。</p>

# 样例一


<h4>input</h4>
<pre>2 1
1 2 4

</pre>

<h4>output</h4>
<pre>12

</pre>

<h4>explanation</h4>
<p>把 $4$ 条道路编号为 $1, 2, 3, 4$，则路线有：（简洁起见没有标出方向，下面的路线均以 $1$ 号城市为起点）
\begin{equation}
(1,2,3,4);(1,2,4,3);(1,3,2,4);(1,3,4,2);(1,4,2,3);(1,4,3,2);(2,1,3,4);(2,1,4,3);(3,1,2,4);(3,1,4,2);(4,1,2,3);(4,1,3,2)
\end{equation}
其余路线与上述 $12$ 种路线等价。</p>

# 样例二


<h4>input</h4>
<pre>3 2
1 2 4
2 3 2

</pre>

<h4>output</h4>
<pre>48

</pre>


# 样例三


<h4>input</h4>
<pre>3 3
1 2 3
2 3 3
3 1 3

</pre>

<h4>output</h4>
<pre>3168

</pre>


# 样例四


<h4>input</h4>
<pre>6 6
1 2 4
2 3 4
3 1 4
1 4 2
2 5 2
3 6 2

</pre>

<h4>output</h4>
<pre>474218496

</pre>


# 样例五


<p>见样例数据下载</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>限制</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n \leq 6,t_i \leq 4$</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="2">$m=n-1$</td></tr><tr><td>4</td></tr><tr><td>5</td><td>$n=m=3$</td></tr><tr><td>6</td><td rowspan="2">如果去掉重复道路，则道路的连接形成了一个环</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">无</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>在所有数据中，满足 $1 \leq n-1 \leq m \leq n \leq 1000$ 且 $1 \leq t_i \leq 10^4$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=226">样例数据下载</a></p>
