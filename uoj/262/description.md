# 题目描述

<p>对于刚上大学的牛牛来说，他面临的第一个问题是如何根据实际情况申请合适的课程。</p>
<p>在可以选择的课程中，有 $2n$ 节课程安排在 $n$ 个时间段上。在第 $i$（$1 \leq i \leq n$）个时间段上，两节内容相同的课程同时在不同的地点进行，其中，牛牛预先被安排在教室 $c_i$ 上课，而另一节课程在教室 $d_i$ 进行。</p>
<p>在不提交任何申请的情况下，学生们需要按时间段的顺序依次完成所有的 $n$ 节安排好的课程。如果学生想更换第 $i$ 节课程的教室，则需要提出申请。若申请通过，学生就可以在第 $i$ 个时间段去教室 $d_i$ 上课，否则仍然在教室 $c_i$ 上课。</p>
<p>由于更换教室的需求太多，申请不一定能获得通过。通过计算，牛牛发现申请更换第 $i$ 节课程的教室时，申请被通过的概率是一个已知的实数 $k_i$，并且对于不同课程的申请，被通过的概率是互相独立的。</p>
<p>学校规定，所有的申请只能在学期开始前一次性提交，并且每个人只能选择<strong>至多</strong> $m$ 节课程进行申请。这意味着牛牛必须一次性决定是否申请更换每节课的教室，而不能根据某些课程的申请结果来决定其他课程是否申请；牛牛可以申请自己最希望更换教室的 $m$ 门课程，也可以<strong>不用完</strong>这 $m$ 个申请的机会，甚至可以一门课程都不申请。</p>
<p>因为不同的课程可能会被安排在不同的教室进行，所以牛牛需要利用课间时间从一间教室赶到另一间教室。</p>
<p>牛牛所在的大学有 $v$ 个教室，有 $e$ 条道路。每条道路连接两间教室，并且是可以<strong>双向通行</strong>的。由于道路的长度和拥堵程度不同，通过不同的道路耗费的体力可能会有所不同。
当第 $i$（$1 \leq i \leq n-1$）节课结束后，牛牛就会从这节课的教室出发，选择一条耗费体力最少的<strong>路径</strong>前往下一节课的教室。</p>
<p>现在牛牛想知道，申请哪几门课程可以使他因在教室间移动耗费的体力值的总和的<strong>期望值</strong>最小，请你帮他求出这个最小值。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行四个整数 $n,m,v,e$。$n$ 表示这个学期内的时间段的数量；$m$ 表示牛牛最多可以申请更换多少节课程的教室；$v$ 表示牛牛学校里教室的数量；$e$表示牛牛的学校里道路的数量。</p>
<p>第二行 $n$ 个正整数，第 $i$（$1 \leq i \leq n$）个正整数表示 $c_i$，即第 $i$ 个时间段牛牛被安排上课的教室；保证 $1 \le c_i \le v$。</p>
<p>第三行 $n$ 个正整数，第 $i$（$1 \leq i \leq n$）个正整数表示 $d_i$，即第 $i$ 个时间段另一间上同样课程的教室；保证 $1 \le d_i \le v$。</p>
<p>第四行 $n$ 个实数，第 $i$（$1 \leq i \leq n$）个实数表示 $k_i$，即牛牛申请在第 $i$ 个时间段更换教室获得通过的概率。保证 $0 \le  k_i \le 1$。</p>
<p>接下来 $e$ 行，每行三个正整数 $a_j, b_j, w_j$，表示有一条双向道路连接教室 $a_j, b_j$，通过这条道路需要耗费的体力值是 $w_j$；保证 $1 \le a_j, b_j \le v$， $1 \le w_j \le 100$。</p>
<p>保证 $1 \leq n \leq 2000$，$0 \leq m \leq 2000$，$1 \leq v \leq 300$，$0 \leq e \leq 90000$。</p>
<p>保证通过学校里的道路，从任何一间教室出发，都能到达其他所有的教室。</p>
<p>保证输入的实数最多包含 $3$ 位小数。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出一行，包含一个实数，四舍五入精确到小数点后<strong>恰好$2$位</strong>，表示答案。你的输出必须和标准输出<strong>完全一样</strong>才算正确。</p>
<p>测试数据保证四舍五入后的答案和准确答案的差的绝对值不大于 $4 \times 10^{-3}$。
（如果你不知道什么是浮点误差，这段话可以理解为：对于大多数的算法，你可以正常地使用浮点数类型而不用对它进行特殊的处理）</p>

# 样例一


<h4>input</h4>
<pre>3 2 3 3
2 1 2
1 2 1
0.8 0.2 0.5
1 2 5
1 3 3
2 3 1

</pre>


<h4>output</h4>
<pre>2.80

</pre>

<h4>explanation</h4>
<p>所有可行的申请方案和期望收益如下表：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">申请更换教室的时间段</th><th rowspan="1">申请通过的时间段</th><th rowspan="1">出现的概率</th><th rowspan="1">耗费的体力值</th><th rowspan="1">耗费的体力值的期望</th></tr></thead><tbody><tr><td rowspan="1">无</td><td rowspan="1">无</td><td rowspan="1">1.0</td><td rowspan="1">8</td><td rowspan="1">8.0</td></tr><tr><td rowspan="2">1</td><td rowspan="1">1</td><td rowspan="1">0.8</td><td rowspan="1">4</td><td rowspan="2">4.8</td></tr><tr><td rowspan="1">无</td><td rowspan="1">0.2</td><td rowspan="1">8</td></tr><tr><td rowspan="2">2</td><td rowspan="1">2</td><td rowspan="1">0.2</td><td rowspan="1">0</td><td rowspan="2">6.4</td></tr><tr><td rowspan="1">无</td><td rowspan="1">0.8</td><td rowspan="1">8</td></tr><tr><td rowspan="2">3</td><td rowspan="1">3</td><td rowspan="1">0.5</td><td rowspan="1">4</td><td rowspan="2">6.0</td></tr><tr><td rowspan="1">无</td><td rowspan="1">0.5</td><td rowspan="1">8</td></tr><tr><td rowspan="4">1、2</td><td rowspan="1">1、2</td><td rowspan="1">0.16</td><td rowspan="1">4</td><td rowspan="4">4.48</td></tr><tr><td rowspan="1">1</td><td rowspan="1">0.64</td><td rowspan="1">4</td></tr><tr><td rowspan="1">2</td><td rowspan="1">0.04</td><td rowspan="1">0</td></tr><tr><td rowspan="1">无</td><td rowspan="1">0.16</td><td rowspan="1">8</td></tr><tr><td rowspan="4">1、3</td><td rowspan="1">1、3</td><td rowspan="1">0.4</td><td rowspan="1">0</td><td rowspan="4">2.8</td></tr><tr><td rowspan="1">1</td><td rowspan="1">0.4</td><td rowspan="1">4</td></tr><tr><td rowspan="1">3</td><td rowspan="1">0.1</td><td rowspan="1">4</td></tr><tr><td rowspan="1">无</td><td rowspan="1">0.1</td><td rowspan="1">8</td></tr><tr><td rowspan="4">2、3</td><td rowspan="1">2、3</td><td rowspan="1">0.1</td><td rowspan="1">4</td><td rowspan="4">5.2</td></tr><tr><td rowspan="1">2</td><td rowspan="1">0.1</td><td rowspan="1">0</td></tr><tr><td rowspan="1">3</td><td rowspan="1">0.4</td><td rowspan="1">4</td></tr><tr><td rowspan="1">无</td><td rowspan="1">0.4</td><td rowspan="1">8</td></tr></tbody></table></div>


# 样例二


<h4>input</h4>
<p>见下载。</p>
<h4>output</h4>
<p>见下载。</p>
<h4>explanation</h4>
<ol><li>道路中可能会有<strong>多条</strong>双向道路连接相同的两间教室。也有可能有道路两端连接的是<strong>同一间</strong>教室。</li>
<li>请注意区分 $n,m,v,e$ 的意义，$n$ <strong>不是</strong>教室的数量，$m$ <strong>不是</strong>道路的数量。</li>
</ol>
# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">$v$</th><th rowspan="1">特殊性质1</th><th rowspan="1">特殊性质2</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$\leq1$</td><td rowspan="1">$\leq1$</td><td rowspan="1">$\leq300$</td><td rowspan="4">×</td><td rowspan="4">×</td></tr><tr><td rowspan="1">2</td><td rowspan="3">$\leq2$</td><td rowspan="1">$\leq0$</td><td rowspan="1">$\leq20$</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$\leq1$</td><td rowspan="1">$\leq100$</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$\leq2$</td><td rowspan="1">$\leq300$</td></tr><tr><td rowspan="1">5</td><td rowspan="3">$\leq3$</td><td rowspan="1">$\leq0$</td><td rowspan="1">$\leq20$</td><td rowspan="2">√</td><td rowspan="1">√</td></tr><tr><td rowspan="1">6</td><td rowspan="1">$\leq1$</td><td rowspan="1">$\leq100$</td><td rowspan="2">×</td></tr><tr><td rowspan="1">7</td><td rowspan="1">$\leq2$</td><td rowspan="2">$\leq300$</td><td rowspan="1">×</td></tr><tr><td rowspan="1">8</td><td rowspan="4">$\leq10$</td><td rowspan="1">$\leq0$</td><td rowspan="2">√</td><td rowspan="1">√</td></tr><tr><td rowspan="1">9</td><td rowspan="1">$\leq1$</td><td rowspan="1">$\leq20$</td><td rowspan="2">×</td></tr><tr><td rowspan="1">10</td><td rowspan="1">$\leq2$</td><td rowspan="1">$\leq100$</td><td rowspan="2">×</td></tr><tr><td rowspan="1">11</td><td rowspan="1">$\leq10$</td><td rowspan="1">$\leq300$</td><td rowspan="1">√</td></tr><tr><td rowspan="1">12</td><td rowspan="4">$\leq20$</td><td rowspan="1">$\leq0$</td><td rowspan="1">$\leq20$</td><td rowspan="1">√</td><td rowspan="3">×</td></tr><tr><td rowspan="1">13</td><td rowspan="1">$\leq1$</td><td rowspan="1">$\leq100$</td><td rowspan="1">×</td></tr><tr><td rowspan="1">14</td><td rowspan="1">$\leq2$</td><td rowspan="2">$\leq300$</td><td rowspan="1">√</td></tr><tr><td rowspan="1">15</td><td rowspan="1">$\leq20$</td><td rowspan="3">×</td><td rowspan="1">√</td></tr><tr><td rowspan="1">16</td><td rowspan="4">$\leq300$</td><td rowspan="1">$\leq0$</td><td rowspan="1">$\leq20$</td><td rowspan="2">×</td></tr><tr><td rowspan="1">17</td><td rowspan="1">$\leq1$</td><td rowspan="1">$\leq100$</td></tr><tr><td rowspan="1">18</td><td rowspan="1">$\leq2$</td><td rowspan="2">$\leq300$</td><td rowspan="1">√</td><td rowspan="2">√</td></tr><tr><td rowspan="1">19</td><td rowspan="1">$\leq300$</td><td rowspan="7">×</td></tr><tr><td rowspan="1">20</td><td rowspan="6">$\leq2000$</td><td rowspan="1">$\leq0$</td><td rowspan="2">$\leq20$</td><td rowspan="6">×</td></tr><tr><td rowspan="1">21</td><td rowspan="1">$\leq1$</td></tr><tr><td rowspan="1">22</td><td rowspan="1">$\leq2$</td><td rowspan="2">$\leq100$</td></tr><tr><td rowspan="1">23</td><td rowspan="3">$\leq2000$</td></tr><tr><td rowspan="1">24</td><td rowspan="2">$\leq300$</td></tr><tr><td rowspan="1">25</td></tr></tbody></table></div>

<p>特殊性质1：图上任意两点 $a_i, b_i$ （$a_i \neq b_i$）间，存在一条耗费体力最少的路径只包含一条道路。</p>
<p>特殊性质2：对于所有的 $1 \leq i \leq n, k_i = 1$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=262">样例数据下载</a></p>
