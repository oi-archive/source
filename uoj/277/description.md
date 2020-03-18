# 题目描述

<p>定向越野是一项集智力与体力为一体的体育运动，在这项活动中，选手需要从起点出发，在尽可能短的时间内到达指定的地点。</p>
<p>牛牛非常喜爱这项运动，但是他不知道怎么样才能更快到达终点。他听说来参加集训的你智力过人，于是他把定向越野的地图交给了你，希望你帮他解决一些问题。</p>
<p>牛牛给你的地图描述的是一块平地，地图上不仅清楚地标出了起点和终点的坐标，还标有若干个<strong>互不相交</strong>圆形区域，每个区域表示一个圆形的水域。对于不会游泳的牛牛来说，进入水域是根本不可能的。因此，牛牛的行动路线不能从水域中穿过。牛牛想知道这样的路线长度最小可以是多少。</p>

# 输入格式


<p>第一行包含四个实数 $S_x,S_y,T_x,T_y$ ，分别表示起点的$x,y$坐标和终点的$x,y$坐标。</p>
<p>第二行包含一个整数$n$，表示水域的个数。</p>
<p>接下来$n$行，每行$3$个整数 $x_i,y_i,r_i$ 表示一片水域的圆心的$x,y$坐标和半径。</p>
<p>保证起点和终点都不在水域的内部或边界上，起点和终点不重合。</p>

# 输出格式


<p>输出一行，包含一个实数，四舍五入精确到小数点后<strong>恰好$1$位</strong>，表示答案。你的输出必须和标准输出<strong>完全一样</strong>才算正确。</p>
<p>测试数据保证四舍五入后的答案和准确答案的差的绝对值不大于 $4 \times 10^{-2}$。</p>
<p>（如果你不知道什么是浮点误差，这段话可以理解为：对于大多数的算法，你可以正常地使用浮点数类型而不用对它进行特殊的处理）</p>

# 样例一


<h4>input</h4>
<pre>2 1 20 11
2
5 5 4
16 9 4

</pre>

<h4>output</h4>
<pre>23.0

</pre>

<h4>explanation</h4>
<p>这个地图如下图，其中画出的路径即是所求的最短路径。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/277/sample.png" alt="样例" style="width:700px;"/></p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有数据满足，$0 \le n\le 500, -1000 \le x_i,y_i,r_i,S_x,S_y,T_x,T_y \le 1000$ 。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$n$</th><th rowspan="1">半径相同</th><th rowspan="1">网格</th></tr></thead><tbody><tr><td rowspan="1">$1$</td><td rowspan="1">$\leq0$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$2$</td><td rowspan="1">$\leq1$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$3$</td><td rowspan="1">$\leq1$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$4$</td><td rowspan="1">$\leq2$</td><td rowspan="1">√</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$5$</td><td rowspan="1">$\leq2$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$6$</td><td rowspan="1">$\leq3$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$7$</td><td rowspan="1">$\leq4$</td><td rowspan="1">√</td><td rowspan="1">√</td></tr><tr><td rowspan="1">$8$</td><td rowspan="1">$\leq5$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$9$</td><td rowspan="1">$\leq8$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$10$</td><td rowspan="1">$\leq16$</td><td rowspan="1">√</td><td rowspan="1">√</td></tr><tr><td rowspan="1">$11$</td><td rowspan="1">$\leq20$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$12$</td><td rowspan="1">$\leq50$</td><td rowspan="1">√</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$13$</td><td rowspan="1">$\leq100$</td><td rowspan="1">√</td><td rowspan="1">√</td></tr><tr><td rowspan="1">$14$</td><td rowspan="1">$\leq200$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$15$</td><td rowspan="1">$\leq400$</td><td rowspan="1">√</td><td rowspan="1">√</td></tr><tr><td rowspan="1">$16$</td><td rowspan="1">$\leq400$</td><td rowspan="1">√</td><td rowspan="1">√</td></tr><tr><td rowspan="1">$17$</td><td rowspan="1">$\leq500$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$18$</td><td rowspan="1">$\leq500$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$19$</td><td rowspan="1">$\leq500$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr><tr><td rowspan="1">$20$</td><td rowspan="1">$\leq500$</td><td rowspan="1">×</td><td rowspan="1">×</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$5\texttt{s}$</p>
<p><strong>空间限制</strong>：$1\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=277">样例数据下载</a></p>
