# 题目描述

<p>为了出题，出题人 03 喜欢在校园里闲逛。</p>
<p>校园可以看成抽象成是一张 $n$ 个点 $m$ 条边的有向图，第 $i$ 条边从 $a_i$ 连向 $b_i$，边权为 $c_i$。</p>
<p>出题人 03 总共会闲逛 $Q$ 天，在第 $i$ 天，他会从 $x_i$ 出发，到达 $y_i$，同时希望自己走过的路径边权和恰好为 $v_i$。</p>
<p>出题人 03 很好奇，每一天他可以有多少种不同的路径呢? 由于答案很大，你只需要回答答案对 $998244353$ 取模的结果。</p>
<p>同一条路径可以多次经过同一条边。两条路径相同当且仅当两条路径上的边数相同且边的编号依次相等。</p>

# 输入格式


<p>第一行四个整数 $n,m,Q,\max_v$。</p>
<p>接下来 $m$ 行，每行三个正整数表示 $a_i,b_i,c_i$。</p>
<p>接下来 $Q$ 行，每行三个正整数表示 $x_i,y_i,v_i$。</p>

# 输出格式


<p>$Q$ 行，第 $i$ 行一个整数表示第 $i$ 次询问的答案对 $998244353$ 取模的结果。</p>

# 样例一


<h4>input</h4>
<pre>3 10 5 10
1 2 1
2 3 3
3 1 7
2 3 5
1 1 4
3 1 2
2 1 1
3 2 3
1 2 2
1 3 4
1 3 6
1 3 7
1 3 8
1 3 9
1 3 10

</pre>

<h4>output</h4>
<pre>3
4
6
8
19

</pre>

<h4>explanation</h4>
<p>在第一天中，存在如下三条闲逛路径：（$\#i$ 表示输入数据中第 $i$ 条边）</p>
<p>$1\ \xrightarrow{\#1}\ 2\ \xrightarrow{\#4}\ 3$</p>
<p>$1\ \xrightarrow{\#1}\ 2\ \xrightarrow{\#7}\ 1 \xrightarrow{\#1}\ 2\ \xrightarrow{\#2}\ 3$</p>
<p>$1\ \xrightarrow{\#1}\ 2\ \xrightarrow{\#7}\ 1\ \xrightarrow{\#10}\ 3$</p>
<p>注意一条路径可以重复经过一个点，也可以重复经过一条边。</p>

# 样例二


<p>见附加文件。</p>
<p>该测试点$n=3$，其余范围同测试点$1$。</p>

# 数据范围


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n=$</th><th>特殊性质</th></tr></thead><tbody><tr><td>$1$</td><td>$8$</td><td>$m \le 2000, \max_v \le 200$</td></tr><tr><td>$2$</td><td>$1$</td><td rowspan="3">无</td></tr><tr><td>$3$</td><td>$2$</td></tr><tr><td>$4$</td><td>$3$</td></tr><tr><td>$5$</td><td rowspan="2">$5$</td><td>$x_i=1$</td></tr><tr><td>$6$</td><td rowspan="3">无</td></tr><tr><td>$7$</td><td>$6$</td></tr><tr><td>$8$</td><td>$7$</td></tr><tr><td>$9$</td><td rowspan="2">$8$</td><td>$x_i=1$</td></tr><tr><td>$10$</td><td>无</td></tr></tbody></table></div>

<p>对于所有测试点，满足 $1 \le n \le 8,0 \le m \le 300000,1 \le \max_v \le 65000,0 \le Q \le 10000$。</p>
<p>对于所有测试点，满足 $1 \le a_i,b_i,x_i,y_i \le n,1 \le c_i,v_i \le \max_v$。</p>
<p><strong>请注意选手程序自身常数因子对程序运行时间带来的影响</strong></p>
<p><strong>时间限制</strong>：$4\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=551">样例数据下载</a></p>
