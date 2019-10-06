# 题目描述

<p>寒冬又一次肆虐了北国大地</p>
<p>无情的北风穿透了人们御寒的衣物</p>
<p>可怜虫们在冬夜中发出无助的哀嚎</p>
<p>“冻死宝宝了！”</p>
<p>这时</p>
<p>远处的天边出现了一位火焰之神</p>
<p>“我将赐予你们温暖和希望！”</p>
<p>只见他的身体中喷射出火焰之力</p>
<p>通过坚固的钢铁，传遍了千家万户</p>
<p>这时，只听见人们欢呼</p>
<p>“暖气来啦！”</p>

# 任务描述


<p>虽然小R住的宿舍楼早已来了暖气，但是由于某些原因，宿舍楼中的某些窗户仍然开着（例如厕所的窗户），这就使得宿舍楼中有一些路上的温度还是很低。</p>
<p>小R的宿舍楼中有$n$个地点和一些路，一条路连接了两个地点，小R可以通过这条路从其中任意一个地点到达另外一个地点。但在刚开始，小R还不熟悉宿舍楼中的任何一条路，所以他会慢慢地发现这些路，他在发现一条路时还会知道这条路的温度和长度。每条路的温度都是互不相同的。</p>
<p>小R需要在宿舍楼中活动，每次他都需要从一个地点到达另一个地点。小R希望每次活动时经过一条最温暖的路径，最温暖的路径的定义为，将路径上各条路的温度从小到大排序后字典序最大。即温度最低的路温度尽量高，在满足该条件的情况下，温度第二低的路温度尽量高，以此类推。小R不会经过重复的路。由于每条路的温度互不相同，因此只存在一条最温暖的路径。</p>
<p>对于小R的每次活动，你需要求出小R需要走过的路径总长度。如果小R通过当前发现的路不能完成这次活动，则输出 $-1$。</p>
<p><strong>注意本题中的字典序与传统意义上的字典序定义有所不同，对于两个序列$a,b(a \neq b)$，若$a$是$b$的前缀则$a$的字典序较大，同时可以推出空串的字典序最大。</strong></p>

# 输入格式


<p>第一行两个正整数 $n,m$。表示小R的宿舍楼中有 $n$ 个地点，共发生了 $m$ 个事件。</p>
<p>接下来 $m$ 行，每行描述一个事件，事件分为三类。</p>
<ol><li><p>$\texttt{find id u v t l}$ 表示小R发现了一条连接$u$和$v$之间的路，编号为$id$。相同$id$的边只会出现一次。</p>
</li>
<li><p>$\texttt{move u v}$ 表示小R要从$u$到达$v$，你需要计算出最温暖的路径的长度 ，若不能从$u$到达$v$，则输出$-1$。</p>
</li>
<li><p>$\texttt{change id l}$ 表示从$u$到$v$这条边的长度变为了$l$（保证在当前时间点这条边存在）。 </p>
</li>
</ol>
# 输出格式


<p>对于每个询问，输出一行整数，表示最温暖的路径长度。</p>

# 样例一


<h4>input</h4>
<pre>8 19
find 0 0 2 7 2
find 1 2 4 4 4
find 2 4 6 10 1
find 3 6 7 8 6
move 2 7
move 1 6
find 4 2 5 3 4
move 0 5
change 0 12
find 5 4 5 5 10
find 6 2 3 6 9
move 3 5
find 7 0 1 12 1
move 1 6
find 8 1 7 11 100
move 1 6
move 3 7
move 5 6
move 2 2

</pre>

<h4>output</h4>
<pre>11
-1
6
23
18
106
122
11
0

</pre>


# 样例二


<h4>input</h4>
<pre>15 45
find 0 1 0 8 5987
find 1 2 0 14 5455
find 2 3 0 27 8830
find 3 4 3 42 7688
find 4 5 0 25 1756
find 5 6 5 35 1550
find 6 7 4 43 9440
move 3 9
change 2 9113
move 10 13
move 3 3
move 11 10
find 7 8 7 6 7347
find 8 9 8 26 8935
move 8 4
change 3 4466
find 9 10 9 28 8560
move 6 5
find 10 11 10 31 6205
change 9 9228
find 11 12 10 23 948
find 12 13 12 45 5945
move 0 9
move 2 5
change 2 6118
find 13 14 13 12 6906
move 4 1
change 2 504
find 14 4 2 22 9796
move 10 7
move 1 14
move 13 3
find 15 12 9 39 8985
find 16 9 8 17 3710
change 1 5370
find 17 1 0 36 4669
find 18 7 6 37 8087
move 9 0
find 19 14 9 33 8234
find 20 0 4 24 5209
change 1 4883
find 21 6 3 9 2461
find 22 5 2 19 4291
change 1 7219
change 6 4846

</pre>

<h4>output</h4>
<pre>-1
-1
0
-1
16787
1550
39301
7211
16571
25510
59706
46309
30692

</pre>


# 样例三


<p>见样例数据下载</p>

# 限制与约定


<p>对于find操作：$(0\le id\lt m, 0\le u,v \lt n, u\ne v,0\le t\le 1000000000, 0 \le l \le 10000)$；</p>
<p>对于move操作：$(0\le u,v \lt n)$；</p>
<p>对于change操作：$(0 \le l \le 10000)$。</p>
<p>对于100%的数据，$1\le n\le 100000, 1\le m \le 300000$ 。</p>
<p>本题共有20个数据点，每个数据点5分。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">$其它$</th></tr></thead><tbody><tr><td rowspan="1">$1-2$</td><td rowspan="1">$\leq20$</td><td rowspan="1">$\leq50$</td><td rowspan="2">无特殊约定</td></tr><tr><td rowspan="1">$3-5$</td><td rowspan="1">$\leq1000$</td><td rowspan="1">$\leq3000$</td></tr><tr><td rowspan="1">$6-10$</td><td rowspan="3">$\leq100000$</td><td rowspan="3">$\leq300000$</td><td rowspan="1">所有的find事件都在move事件之前，且没有change事件</td></tr><tr><td rowspan="1">$11-14$</td><td rowspan="1">所有的find事件都在move事件之前</td></tr><tr><td rowspan="1">$15-20$</td><td rowspan="1">无特殊约定</td></tr></tbody></table></div>


<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=274">样例数据下载</a></p>
