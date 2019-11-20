# 题目描述

<p>新年到新年到！计算鸡村全村上下家家户户开始贴起了春联。</p>
<p>比起贴春联，计算鸡更喜欢制作春联，除了每家每户制作自己的春联之外，还可以两家一起，一家写上联，一家写下联，凑成一整幅春联。</p>
<p>计算鸡村共有 $n$ 户村民，现在每两户计算鸡都合作制作了一副春联，加上每家每户自己的，一共有 $\frac{n(n+1)}{2}$ 副春联。</p>
<p>计算鸡对春联的长度有这特殊的癖好，他们希望这 $\frac{n(n+1)}{2}$ 副春联长度各不相同，于是计算鸡村长找来一根长度为 $\frac{n(n+1)}{2}$ 的木条，想要把它做成一把尺，使得它能量出不超过 $\frac{n(n+1)}{2}$ 的所有正整数长度。</p>
<p>计算鸡们很懒，他们连划刻度都觉得累，于是他们决定在木条上划出恰好 $n-1$ 个刻度，并使它满足计算鸡村长的条件。</p>
<p>可是有的时候他们想啊想啊，想破鸡蛋都想不出来如何安排刻度，于是他们怀疑根本就不存在安排刻度的方法，想让你帮忙验证。</p>
<p>你只需要对于给定的 $n$，告诉计算鸡们是否存在合法的雕刻刻度的方法。</p>
<p>一个长度 $d$ 能被木条量出当且仅当存在两个不同的刻度之间，刻度与两个端点之间，或木棍两个端点的距离恰好为 $d$。</p>
<p>更加数学的描述：假如你安排的刻度到木棍左端的距离由近至远分别为 $s_1, s_2, \dots, s_{n-1}$，令 $s_0=0,s_n=\frac{n(n+1)}{2}$，则长度 $d$ 能被量出当且仅当存在 $0 \leq i,j \leq n$ 使得 $\lvert s_i-s_j \rvert =d$。</p>

# 输入格式


<p>多组数据，第一行为数据组数 $T\le10$，以下 $T$ 行为 $T$ 个正整数 $n$。</p>

# 输出格式


<p>输出共 $T$ 行, 每行为一个整数, 表示能否给出满足要求的刻度。 能则输出 $1$，不能则输出 $-1$。</p>

# 样例一


<h4>input</h4>
<pre>2
1
100

</pre>

<h4>output</h4>
<pre>1
-1

</pre>


# 限制与约定


<p>对于全部数据满足$1 \leq T \leq 10$，$1 \leq n \leq 2500$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
</tr></thead><tbody><tr><td>1</td><td>$\le5$</td></tr><tr><td>2</td><td>$\le8$</td></tr><tr><td>3</td><td rowspan="2">$\le20$</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="2">$\le100$ 且为质数</td></tr><tr><td>6</td></tr><tr><td>7</td><td>$=2017$</td></tr><tr><td>8</td><td>$=2048$</td></tr><tr><td>9</td><td rowspan="2">$\le2500$</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=282">样例数据下载</a></p>
