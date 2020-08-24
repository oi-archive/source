# 题目描述

<p>坐落在 Bzeroth 大陆上的精灵王国击退地灾军团的入侵后，经过十余年的休养生息， 重新成为了一片欣欣向荣的乐土，吸引着八方游客。小 W 是一位游历过世界各地的著名美食家，现在也慕名来到了精灵王国。 </p>
<p>精灵王国共有 $n$ 座城市，城市从 $1$ 到 $n$ 编号，其中城市 $i$ 的美食能为小 W 提供 $c_i$ 的愉悦值。精灵王国的城市通过 $m$ 条<strong>单向道路</strong>连接，道路从 $1$ 到 $m$ 编号，其中道路 $i$ 的起点为城市 $u_i$ ，终点为城市 $v_i$，沿它通行需要花费 $w_i$ 天。也就是说，若小 W 在第 $d$ 天从城市 $u_i$ 沿道路 $i$ 通行，那么他会在第 $d + w_i$ 天到达城市 $v_i$。 </p>
<p>小 W 计划在精灵王国进行一场为期 $T$ 天的旅行，更具体地：他会在第 0 天从城市 1 出发，经过 $T$ 天的旅行，最终在<strong>恰好第 $T$ 天</strong>回到城市 1 结束旅行。由于小 W 是一位 美食家，每当他到达一座城市时（包括第 $0$ 天和第 $T$ 天的城市 1），他都会品尝该城市 的美食并获得其所提供的愉悦值，若小 W 多次到达同一座城市，他将<strong>获得多次愉悦值</strong>。 注意旅行途中小 W <strong>不能在任何城市停留</strong>，即当他到达一座城市且还未结束旅行时，他当天必须立即从该城市出发前往其他城市。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/558/delicacy.png" style="width:250px;" alt="示意图"/></p>
<p>对于上图，小 W 一种为期 11 天的可行旅游方案为 $1 \rightarrow 2 \rightarrow 1 \rightarrow 2 \rightarrow 3 \rightarrow 1$： </p>
<ul><li>第 0 天，小 W 从城市 1 开始旅行，获得愉悦值 1 并向城市 2 出发。 </li>
<li>第 1 天，小 W 到达城市 2，获得愉悦值 3 并向城市 1 出发。 </li>
<li>第 4 天，小 W 到达城市 1，获得愉悦值 1 并向城市 2 出发。 </li>
<li>第 5 天，小 W 到达城市 2，获得愉悦值 3 并向城市 3 出发。 </li>
<li>第 7 天，小 W 到达城市 3，获得愉悦值 4 并向城市 1 出发。 </li>
<li>第 11 天，小 W 到达城市 1，获得愉悦值 1 并结束旅行。 </li>
<li>小 W 在该旅行中获得的愉悦值之和为 13。 </li>
</ul><p>此外，精灵王国会在<strong>不同</strong>的时间举办 $k$ 次美食节。具体来说，第 $i$ 次美食节将于第 $t_i$ 天在城市 $x_i$ 举办，若小 W 第 $t_i$ 天时恰好在城市 $x_i$，那么他在品尝城市 xi 的美食时会<strong>额外</strong>得到 $y_i$ 的愉悦值。现在小 W 想请作为精灵王国接待使者的你帮他算出，他在旅 行中能获得的愉悦值之和的<strong>最大值</strong>。</p>

# 输入格式


<p>第一行四个整数 $n,m,T,K$，依次表示城市数、道路条数、旅行天数与美食节次数。</p>
<p>第二行 $n$ 个整数 $c_i$，表示每座城市的美食所能提供的愉悦值。</p>
<p>接下来 $m$ 行每行三个整数 $u_i,v_i,w_i$，依次表示每条道路的起点、终点与通行天数。</p>
<p>最后 $k$ 行每行三个整数 $t_i,x_i,y_i$，依次表示每次美食节的举办时间、举办城市与提供的额外愉悦值。</p>
<p>本题中数据保证：</p>
<ul><li>对所有 $i$，有 $u_i \neq v_i$。但数据中可能存在路线重复的单向道路，即可能存在 $1 \le i &lt; j \le m$，使得 $u_i = u_j,v_i = v_j$。</li>
<li>对每座城市都满足：至少存在一条以该城市为起点的单向道路。</li>
<li>每次美食节的举办时间 $t_i$ 互不相同。</li>
</ul>
# 输出格式


<p>仅一行一个整数，表示小 W 通过旅行能获得的愉悦值之和的最大值。</p>
<p>若小 W 无法在第 $T$ 天回到城市 $1$，则输出 <samp>-1</samp>。</p>

# 样例一


<h4>input</h4>
<pre>3 4 11 0
1 3 4
1 2 1
2 1 3
2 3 2
3 1 4
</pre>

<h4>output</h4>
<pre>13
</pre>

<h4>explanation</h4>
<p>该样例为题目描述中的例子，最优旅行方案见题目描述。</p>

# 样例二


<h4>input</h4>
<pre>4 8 16 3
3 1 2 4
1 2 1
1 3 1
1 3 2
3 4 3
2 3 2
3 2 1
4 2 1
4 1 5
3 3 5
1 2 5
5 4 20
</pre>

<h4>output</h4>
<pre>39
</pre>

<h4>explanation</h4>
<p>最优方案为 $1 \rightarrow 3 \rightarrow 4 \rightarrow 2 \rightarrow 3 \rightarrow 4 \rightarrow 1$。</p>
<ul><li>第 $0$ 天，小 W 从城市 $1$ 开始旅行，获得愉悦值 $3$ 并沿道路 $3$ 通行。</li>
<li>第 $2$ 天，小 W 到达城市 $3$，获得愉悦值 $2$ 并沿道路 $4$ 通行。</li>
<li>第 $5$ 天，小 W 到达城市 $4$，由于美食节获得愉悦值 $20+4$ 并沿道路 $7$ 通行。</li>
<li>第 $6$ 天，小 W 到达城市 $2$，获得愉悦值 $1$ 并沿道路 $5$ 通行。</li>
<li>第 $8$ 天，小 W 到达城市 $3$，获得愉悦值 $2$ 并沿道路 $4$ 通行。</li>
<li>第 $11$ 天，小 W 到达城市 $4$，获得愉悦值 $4$ 并沿道路 $8$ 通行。</li>
<li>第 $16$ 天，小 W 到达城市 $1$，获得愉悦值 $3$ 并结束旅行。</li>
<li>小 W 获得的愉悦值之和为 $39$。</li>
</ul>
# 样例三


<p>见样例数据下载。</p>
<p>该样例额外满足 $k=0$。</p>

# 数据范围


<p>对于所有测试点：</p>
<p>$1 \le n \le 50,n \le m \le 501,0 \le k \le 200,1 \le t_i \le T \le 10^9$.</p>
<p>$1 \le w_i \le 5,1 \le c_i \le 52501,1 \le u_i,v_i,x_i \le n,1 \le y_i \le 10^9$.</p>
<p>每个测试点的具体限制见下表：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m$</th><th>$T$</th><th>特殊性质</th></tr></thead><tbody><tr><td>$1 \sim 4$</td><td>$\le 5$</td><td rowspan="6">$\le 50$</td><td>$\le 5$</td><td rowspan="2">无</td></tr><tr><td>$5 \sim 8$</td><td rowspan="6">$\le 50$</td><td>$\le 52501$</td></tr><tr><td>$9 \sim 10$</td><td rowspan="5">$\le 10^9$</td><td>A</td></tr><tr><td>$11 \sim 13$</td><td>$k=0$</td></tr><tr><td>$14 \sim 15$</td><td>$k \le 10$</td></tr><tr><td>$16 \sim 17$</td><td rowspan="2">无</td></tr><tr><td>$18 \sim 20$</td><td>$\le 501$</td></tr></tbody></table></div>

<p>特殊限制A：$n = m$ 且 $u_i=i,v_i=(i \bmod n)+1$。</p>
<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=558">样例数据下载</a></p>
