# 题目描述

<p>在咕了无数锅和 ddl 之后，S***pe 终于如愿以偿，变成了一只翱翔在天空中的白鸽。S***pe 很久以前听说过，白鸽的使命，就是以不同的方向飞过天空，带给地上的人们无尽的灵感。可是刚刚被变成白鸽的 S***pe 心理并不平衡，他远远地看见了地面上那个甩锅给他的人 w*x，他决定不给 w*x 提供应该提供的灵感，而且 S***pe相信不给灵感的方法就是绕着 w*x 顺时针转圈，这样的话对于 w*x 来说白鸽就只有往右侧飞行，而不能看到白鸽以不同的方向飞过天空了。</p>
<p>S***pe 觉得自己的行程必须经过若干个关键点，他请你帮他规划路线。</p>
<p>简而言之，现在在二维平面上，有一个给定一张 $n$ 个点 $m$ 条边的无向图作为线路，保证无自环。点从 $1$ 开始编号。</p>
<p>在这张图上的每个节点都在二维平面上有自己的坐标，而一条边对应了连接这两个点的线段，S***pe 的目标是<strong>从 $1$ 号点</strong>开始飞行，每次沿着一条线段到达一个新的点，循环往复最后停<strong>在 $1$ 号点</strong>，且经过<strong>每条线段恰好一次</strong>。同时你需要<strong>最大化</strong>围绕原点<strong>顺时针</strong>旋转的次数。</p>
<p>顺时针旋转的次数：假设 w*x 在 S***pe 飞行的过程中始终保持正面朝向 S***pe，那么在 S***pe 结束飞行之后 w*x 原地右转的圈数就是顺时针旋转的次数（可以为负）。</p>
<p>如果无解输出 $-1$。保证没有两个点重合，没有点和原点重合，且没有两个点所确定的直线经过原点。</p>

# 输入格式


<p>第一行两个正整数 $n, m$ 分别表示这张无向图的点数和边数。</p>
<p>接下来 $n$ 行每行两个整数 $x_i, y_i$ 表示第 $i$ 个点的坐标。</p>
<p>接下来 $m$ 行每行两个整数 $u_i, v_i$ 表示从点 $u_i$ 到点 $v_i$ 之间有一条无向边。</p>

# 输出格式


<p>一行一个整数，如果是 $-1$ 表示无解，否则表示最大的旋转次数。</p>

# 样例一


<h4>input</h4>
<pre>5 10
1 9
6 -8
9 7
-5 -10
10 -6
1 3
3 4
2 3
1 4
5 2
4 5
1 3
3 1
4 1
3 1

</pre>

<h4>output</h4>
<pre>2

</pre>


# explanation


<p>样例中的图如下图所示，<strong>注意图中的重边未被标识。</strong></p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/389/1.jpg" style="width:300px;" alt="样例一解释"/></p>
<p>一种最优的遍历顺序是：</p>
<p>$1 \rightarrow 3 \rightarrow 2 \rightarrow 5 \rightarrow 4 \rightarrow 1 \rightarrow 3 \rightarrow 4 \rightarrow 1 \rightarrow 3 \rightarrow 1$</p>
<p><strong>再次提醒：注意重边。</strong></p>

# 样例二


<h4>input</h4>
<pre>3 5
-764351767 899476675
103147230 -443149366
432530806 578822602
2 3
2 3
1 3
3 1
2 3

</pre>

<h4>output</h4>
<pre>-1

</pre>


# explanation


<p>不存在满足条件的路径。</p>

# 样例三


<p>见样例数据下载。</p>

# 样例四


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有数据，$1 \le n, m \le 2 \times 10^{4}$，$|x_i|, |y_i| \le 10 ^ 9$，$1 \le u_i, v_i \le n, u_i \ne v_i$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>限制</th></tr></thead><tbody><tr><td>1</td><td>$15$</td><td>$n, m \le 10$</td></tr><tr><td>2</td><td>$15$</td><td>$n, m \le 20$</td></tr><tr><td>3</td><td>$20$</td><td>$n, m \le 100$</td></tr><tr><td>4</td><td>$20$</td><td>$n, m \le 5000$</td></tr><tr><td>5</td><td>$30$</td><td>$n, m \le 2 \times 10 ^ 4$</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=389">样例数据下载</a></p>
