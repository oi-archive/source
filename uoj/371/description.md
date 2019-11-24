# 题目描述

<p>我，年幼的人赢，总是和我的同桌一起在滑稽树下讨论问题。</p>
<p>我的滑稽树是一棵长在平面上的，有 $n$ 个点的树。点从 $1$ 到 $n$ 标号。这 $n$ 个点满足任意三点互不共线，并且树的边不相交。</p>
<p>现在我都和我的同桌一起在滑稽树上每人各控制一个点。我的点最开始在 $\mathrm{stx}$，我的同桌的点最开始在 $\mathrm{sty}$。我们可以任意沿着树的边移动各自的点。当两个点都在树上的某个叶子的时候游戏就结束了。</p>
<p>现在，我想要最小化任意时刻我们两个所控制的点之间距离的最大值。请问你能帮我解决这个问题吗？注意某个时刻两个点可能都在某一条边上，这时候的距离也要统计入答案。</p>
<p>一句话题意：给定一棵平面上的树，两个点在树上任意移动，最小化从开始到两个点都到达叶子的任意时刻两个点直线距离的最大值。</p>

# 输入格式


<p>第一行三个正整数 $n,\mathrm{stx},\mathrm{sty}$。</p>
<p>接下来 $n$ 行有 $2$ 个整数 $x_i,y_i$，表示第 $i$ 号节点的坐标。</p>
<p>接下来 $n-1$ 行有 $2$ 个整数 $a_i,b_i$，表示树上的一条边。</p>

# 输出格式


<p>输出一行，包含一个实数，表示最小的任意时刻我们两个所控制的点之间距离的最大值。</p>
<p>你的答案与参考答案的绝对误差或相对误差不超过 $10^{−6}$ 时被认为是正确的。</p>

# 样例一


<h4>input</h4>
<pre>4 2 3
0 1
1 1
1 0
0 0
1 2
2 3
3 4

</pre>

<h4>output</h4>
<pre>1.0000000000

</pre>


# 样例二


<h4>input</h4>
<pre>4 2 4
0 0
51 49
100 100
100 0
1 2
2 3
3 4

</pre>

<h4>output</h4>
<pre>69.2964645563

</pre>


# 限制与约定


<p>对于全部数据，$3\le n\le 1000$，$0\le x_i,y_i \le 10^6$。</p>
<div class="table-responsive">
 <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
    <th>分值</th>
    <th>$n$</th>
    <th>特殊性质</th>
   </tr></thead><tbody><tr><td>1</td>
    <td>5</td>
    <td rowspan="2">$\le 10$</td>
    <td>$\mathrm{stx}$ 和 $\mathrm{sty}$ 均为叶子</td>
   </tr><tr><td>2</td>
    <td>25</td>
    <td>无</td>
   </tr><tr><td>3</td>
    <td>25</td>
    <td>$\le 200$</td>
    <td>无</td>
   </tr><tr><td>4</td>
    <td>15</td>
    <td rowspan="2">$\le 1000$</td>
    <td>保证存在最优方案，在任意时刻至少有一端点位于树的某结点上</td>
   </tr><tr><td>5</td>
     <td>30</td>
     <td>无</td>
   </tr></tbody></table></div>


<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=371">样例数据下载</a></p>
