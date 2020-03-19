# 题目描述

<p>小N是蔬菜仓库的管理员，负责设计蔬菜的销售方案。</p>
<p>在蔬菜仓库中，共存放有 $n$ 种蔬菜，小N需要根据不同蔬菜的特性，综合考虑各方面因素，设计合理的销售方案，以获得最多的收益。</p>
<p>在计算销售蔬菜的收益时，每销售一个单位第 $i$ 种蔬菜，就可以获得 $a_i$ 的收益。</p>
<p>特别地，由于政策鼓励商家进行多样化销售，第一次销售第 $i$ 种蔬菜时，还会额外得到 $s_i$ 的额外收益。</p>
<p>在经营开始时，第 $i$ 种蔬菜的库存为 $c_i$ 个单位。</p>
<p>然而，蔬菜的保鲜时间非常有限，一旦变质就不能进行销售，不过聪明的小N已经计算出了每个单位蔬菜变质的时间：对于第 $i$ 种蔬菜，存在保鲜值 $x_i$，每天结束时会有 $x_i$ 个单位的蔬菜变质，直到所有蔬菜都变质。（注意：每一单位蔬菜的变质时间是固定的，不随销售发生变化）</p>
<p>形式化地：对于所有的满足条件 $d \times x_i \le c_i$ 的正整数 $d$ ，有 $x_i$ 个单位的蔬菜将在第 $d$ 天结束时变质。</p>
<p>特别地，若 $(d-1)\times x_i \le c_i &lt; d\times x_i$ ，则有 $c_i - (d-1)\times x_i$ 单位的蔬菜将在第 $d$ 天结束时变质。</p>
<p>注意，当 $x_i = 0$ 时，意味着这种蔬菜不会变质。</p>
<p>同时，每天销售的蔬菜<strong>总量</strong>也是有限的，最多不能超过 $m$ 个单位。</p>
<p>现在，小N有 $k$ 个问题，想请你帮忙算一算。每个问题的形式都是：对于已知的 $p_j$，如果需要销售 $p_j$ 天，最多能获得多少收益？</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行包含三个正整数 $n,m,k$，分别表示蔬菜的种类数目、每天能售出蔬菜总量上限、小N提出的问题的个数。</p>
<p>接下来 $n$ 行，每行输入四个非负整数，描述一种蔬菜的特点，依次为 $a_i,s_i,c_i,x_i$，意义如上文所述。</p>
<p>接下来 $k$ 行，每行输入一个非负整数 $p_j$ ，意义如上文所述。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出 $k$ 行，每行包含一个整数，第 $i$ 行的数表示第 $i$ 个问题的答案。</p>

# 样例一


<h4>input</h4>
<pre>2 3 2
3 3 3 3
2 5 8 3
1
3

</pre>



<h4>output</h4>
<pre>16
27

</pre>

<h4>explanation</h4>
<p>共有两种蔬菜：</p>
<p>销售第 $1$ 种蔬菜时，每销售一单位可以获得的收益为 $3$ ，第一次销售这种蔬菜时，额外可以获得的收益为 $3$。这种蔬菜共有 $3$ 个单位，均会在第一天结束时变质。</p>
<p>销售第 $2$ 种蔬菜时，每销售一单位可以获得的收益为 $2$ ，第一次销售这种蔬菜时，额外可以获得的收益为 $5$。这种蔬菜共有 $8$ 个单位，其中，有 $3$ 单位在第一天结束时变质， $3$ 单位在第二天结束时变质， $2$ 单位在第三天结束时变质。</p>
<p>在只销售 $1$ 天时，应当销售 $2$ 单位的第一种蔬菜和 $1$ 单位的第二种蔬菜。</p>
<p>在这种情况下：销售第一种蔬菜的收益为 $2\times 3 + 3$ ；销售第二种蔬菜的收益为 $1\times 2 +5$ ；总共获得的收益为 $(2\times 3 + 3)+(1\times 2 +5) = 16$ 。</p>
<p>在只销售 $3$ 天时，第一天应当销售 $3$ 单位的第一种蔬菜，第二天应当销售 $3$ 单位的第二种蔬菜（此时选择在第二天结束时会变质的 $3$ 个单位出售），第三天销售 $2$ 单位的第二种蔬菜。</p>
<p>在这种情况下：销售第一种蔬菜的收益为 $3\times 3 + 3$ ；销售第二种蔬菜的收益为 $(3+2)\times 2 +5$；总共获得的收益为 $(3\times 3 + 3)+[(3+2)\times 2 + 5] = 27$。</p>

# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
 <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">$p_j$</th><th rowspan="1">特性1</th><th rowspan="1">特性2</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$\le 2$</td><td rowspan="6">$\le 10$</td><td rowspan="3">$\le 10^3$</td><td rowspan="11">无</td><td rowspan="11">无</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$\le 3$</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$\le 4$</td></tr><tr><td rowspan="1">4</td><td rowspan="3">$\le 10^3$</td><td rowspan="1">$\le 2$</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$\le 3$</td></tr><tr><td rowspan="1">6</td><td rowspan="2">$\le 4$</td></tr><tr><td rowspan="1">7</td><td rowspan="1">$\le 4$</td><td rowspan="1">$\le 1$</td></tr><tr><td rowspan="1">8</td><td rowspan="1">$\le 6$</td><td rowspan="1">$\le 2$</td><td rowspan="1">$\le 6$</td></tr><tr><td rowspan="1">9</td><td rowspan="1">$\le 8$</td><td rowspan="1">$\le 1$</td><td rowspan="1">$\le 8$</td></tr><tr><td rowspan="1">10</td><td rowspan="1">$\le 10$</td><td rowspan="1">$\le 2$</td><td rowspan="1">$\le 10$</td></tr><tr><td rowspan="1">11</td><td rowspan="1">$\le 20$</td><td rowspan="1">$\le 3$</td><td rowspan="1">$\le 20$</td></tr><tr><td rowspan="1">12</td><td rowspan="4">$\le 10^2$</td><td rowspan="14">$\le 10$</td><td rowspan="4">$\le 10^2$</td><td rowspan="1">有</td><td rowspan="1">无</td></tr><tr><td rowspan="1">13</td><td rowspan="3">无</td><td rowspan="1">有</td></tr><tr><td rowspan="1">14</td><td rowspan="2">无</td></tr><tr><td rowspan="1">15</td></tr><tr><td rowspan="1">16</td><td rowspan="5">$\le 10^3$</td><td rowspan="5">$\le 10^3$</td><td rowspan="2">有</td><td rowspan="1">有</td></tr><tr><td rowspan="1">17</td><td rowspan="1">无</td></tr><tr><td rowspan="1">18</td><td rowspan="3">无</td><td rowspan="1">有</td></tr><tr><td rowspan="1">19</td><td rowspan="2">无</td></tr><tr><td rowspan="1">20</td></tr><tr><td rowspan="1">21</td><td rowspan="5">$\le 10^5$</td><td rowspan="5">$\le 10^5$</td><td rowspan="2">有</td><td rowspan="1">有</td></tr><tr><td rowspan="1">22</td><td rowspan="1">无</td></tr><tr><td rowspan="1">23</td><td rowspan="3">无</td><td rowspan="1">有</td></tr><tr><td rowspan="1">24</td><td rowspan="2">无</td></tr><tr><td rowspan="1">25</td></tr></tbody></table></div>

<p>特性 1：所有的 $s_i$ 均为 $0$。</p>
<p>特性 2：所有的 $x_i$ 均为 $0$。</p>
<p>对于所有的测试数据，均保证 $k$ 组询问中的 $p_j$ 互不相同。</p>
<p>对于所有的测试数据，均保证 $0 &lt; a_i , c_i \le 10^9$ , $0 \le s_i , x_i \le 10^9$ 。</p>
<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=318">样例数据下载</a></p>
