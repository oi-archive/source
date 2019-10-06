# 题目描述

<p>为了得到书法大家的真传，小E同学下定决心去拜访住在魔法森林中的隐士。魔法森林可以被看成一个包含个N节点M条边的无向图，节点标号为 $1 \dots n$，边标号为$1 \dots m$。初始时小E同学在 $1$ 号节点，隐士则住在 $n$ 号节点。小E需要通过这一片魔法森林，才能够拜访到隐士。</p>
<p>魔法森林中居住了一些妖怪。每当有人经过一条边的时候，这条边上的妖怪就会对其发起攻击。幸运的是，在 $1$ 号节点住着两种守护精灵：A型守护精灵与B型守护精灵。小E可以借助它们的力量，达到自己的目的。</p>
<p>只要小E带上足够多的守护精灵，妖怪们就不会发起攻击了。具体来说，无向图中的每一条边 $e_i$ 包含两个权值 $a_i$ 与 $b_i$。若身上携带的A型守护精灵个数<strong>不少于 $a_i$</strong>，且B型守护精灵个数<strong>不少于 $b_i$</strong>，这条边上的妖怪就不会对通过这条边的人发起攻击。<strong>当且仅当通过这片魔法森林的过程中没有任意一条边的妖怪向小E发起攻击，他才能成功找到隐士。</strong></p>
<p>由于携带守护精灵是一件非常麻烦的事，小E想要知道，要能够成功拜访到隐士，最少需要携带守护精灵的总个数。<strong>守护精灵的总个数</strong>为A型守护精灵的个数与B型守护精灵的个数之和。</p>

# 输入格式


<p>第1行包含两个整数 $n,m$，表示无向图共有 $n$ 个节点，$m$ 条边。</p>
<p>接下来 $m$ 行，第 $i + 1$ 行包含4个正整数 $x_i, y_i, a_i, b_i$，描述第 $i$ 条无向边。其中 $x_i$ 与 $y_i$ 为该边两个端点的标号，$a_i$ 与 $b_i$的含义如题所述。</p>
<p>注意数据中可能包含重边与自环。</p>

# 输出格式


<p>输出一行一个整数：如果小E可以成功拜访到隐士，输出小E最少需要携带的<strong>守护精灵的总个数</strong>；如果无论如何小E都无法拜访到隐士，输出“$\texttt{-1}$”（不含引号）。</p>

# 样例一


<h4>input</h4>
<pre>4 5
1 2 19 1
2 3 8 12
2 4 12 15
1 3 17 8
3 4 1 17

</pre>

<h4>output</h4>
<pre>32

</pre>

<h4>explanation</h4>
<p>如果小E走路径1→2→4，需要携带 $19+15=34$ 个守护精灵；</p>
<p>如果小E走路径1→3→4，需要携带 $17+17=34$ 个守护精灵；</p>
<p>如果小E走路径1→2→3→4，需要携带 $19+17=36$ 个守护精灵；</p>
<p>如果小E走路径1→3→2→4，需要携带 $17+15=32$ 个守护精灵。</p>
<p>综上所述，小E最少需要携带 $32$ 个守护精灵。</p>

# 样例二


<h4>input</h4>
<pre>3 1
1 2 1 1

</pre>

<h4>output</h4>
<pre>-1

</pre>

<h4>explanation</h4>
<p>小E无法从1号节点到达3号节点，故输出-1。</p>

# 样例三


<p>见样例数据下载</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>$a_i, b_i$</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="3">$2 \leq n \leq 5$</td><td rowspan="3">$0 \leq m \leq 10$</td><td rowspan="3">$1 \leq a_i, b_i \leq 10$</td>
</tr><tr><td>2</td>
</tr><tr><td>3</td>
</tr><tr><td>4</td><td rowspan="3">$2 \leq n \leq 500$</td><td rowspan="3">$0 \leq m \leq 3000$</td><td rowspan="7">$1 \leq a_i, b_i \leq 50000$</td>
</tr><tr><td>5</td>
</tr><tr><td>6</td>
</tr><tr><td>7</td><td rowspan="4">$2 \leq n \leq 5000$</td><td rowspan="4">$0 \leq m \leq 10000$</td>
</tr><tr><td>8</td>
</tr><tr><td>9</td>
</tr><tr><td>10</td>
</tr><tr><td>11</td><td rowspan="10">$2 \leq n \leq 50000$</td><td rowspan="10">$0 \leq m \leq 100000$</td><td rowspan="4">$1 \leq a_i \leq 30$<br/>$1 \leq b_i \leq 50000$</td>
</tr><tr><td>12</td>
</tr><tr><td>13</td>
</tr><tr><td>14</td>
</tr><tr><td>15</td><td rowspan="6">$1 \leq a_i, b_i \leq 50000$</td>
</tr><tr><td>16</td>
</tr><tr><td>17</td>
</tr><tr><td>18</td>
</tr><tr><td>19</td>
</tr><tr><td>20</td>
</tr></tbody></table></div>

<p><strong>时间限制</strong>：$3\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=3">样例数据下载</a></p>
