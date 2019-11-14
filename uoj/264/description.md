# 题目描述

<p>本题中，我们将用符号 $\lfloor c \rfloor$ 表示对 $c$ 向下取整，例如：$\lfloor 3.0 \rfloor = \lfloor 3.1 \rfloor = \lfloor 3.9 \rfloor = 3$。</p>
<p>蛐蛐国最近蚯蚓成灾了！隔壁跳蚤国的跳蚤也拿蚯蚓们没办法，蛐蛐国王只好去请神刀手来帮他们消灭蚯蚓。</p>
<p>蛐蛐国里现在共有 $n$ 只蚯蚓（$n$ 为正整数）。每只蚯蚓拥有长度，我们设第 $i$ 只蚯蚓的长度为 $a_i$ ($i=1,2,\dots,n$)，并保证所有的长度都是<strong>非负</strong>整数（即：可能存在长度为 $0$ 的蚯蚓）。</p>
<p>每一秒，神刀手会在所有的蚯蚓中，准确地找到最长的那一只（如有多个则任选一个）将其切成两半。神刀手切开蚯蚓的位置由常数 $p$（是满足 $0 &lt; p &lt; 1$ 的有理数）决定，设这只蚯蚓长度为 $x$，神刀手会将其切成两只长度分别为 $\lfloor px \rfloor$ 和 $x - \lfloor px \rfloor$ 的蚯蚓。特殊地，如果这两个数的其中一个等于 $0$，则这个长度为 $0$ 的蚯蚓也会被保留。此外，除了刚刚产生的两只新蚯蚓，其余蚯蚓的长度都会增加 $q$（是一个非负整常数）。</p>
<p>蛐蛐国王知道这样不是长久之计，因为蚯蚓不仅会越来越多，还会越来越长。蛐蛐国王决定求助于一位有着洪荒之力的神秘人物，但是救兵还需要 $m$ 秒才能到来……（$m$ 为非负整数）</p>
<p>蛐蛐国王希望知道这 $m$ 秒内的战况。具体来说，他希望知道：</p>
<ul><li>$m$ 秒内，每一秒被切断的蚯蚓被切断前的长度（有 $m$ 个数）；</li>
<li>$m$ 秒后，所有蚯蚓的长度（有 $n + m$ 个数）。</li>
</ul><p>蛐蛐国王当然知道怎么做啦！但是他想考考你……</p>

# 输入


<p>从标准输入读入数据。</p>
<p>第一行包含六个整数 $n,m,q,u,v,t$，其中：$n,m,q$ 的意义见【问题描述】；$u,v,t$ 均为正整数；你需要自己计算 $p=u / v$（保证 $0 &lt; u &lt; v$）；$t$ 是输出参数，其含义将会在【输出格式】中解释。</p>
<p>第二行包含 $n$ 个非负整数，为 $a_1, a_2, \dots, a_n$，即初始时 $n$ 只蚯蚓的长度。</p>
<p>同一行中相邻的两个数之间，恰好用一个空格隔开。</p>
<p>保证 $1 \leq n \leq 10^5$，$0 \leq m \leq 7 \times 10^6$，$0 &lt; u &lt; v \leq 10^9$，$0 \leq q \leq 200$，$1 \leq t \leq 71$，$0 \leq a_i \leq 10^8$。</p>

# 输出


<p>输出到标准输出。</p>
<p>第一行输出 $\left \lfloor \frac{m}{t} \right \rfloor$ 个整数，按时间顺序，依次输出第 $t$ 秒，第 $2t$ 秒，第 $3t$ 秒，……被切断蚯蚓（在被切断前）的长度。</p>
<p>第二行输出 $\left \lfloor \frac{n+m}{t} \right \rfloor$ 个整数，输出 $m$ 秒后蚯蚓的长度；需要按从大到小的顺序，依次输出排名第 $t$，第 $2t$，第 $3t$，……的长度。</p>
<p>同一行中相邻的两个数之间，恰好用一个空格隔开。即使某一行没有任何数需要输出，你也应输出一个空行。</p>
<p>请阅读样例来更好地理解这个格式。</p>

# 样例一


<h4>input</h4>
<pre>3 7 1 1 3 1
3 3 2

</pre>

<h4>output</h4>
<pre>3 4 4 4 5 5 6
6 6 6 5 5 4 4 3 2 2

</pre>

<h4>explanation</h4>
<p>在神刀手到来前：$3$ 只蚯蚓的长度为 $3,3,2$。</p>
<p>$1$ 秒后：一只长度为 $3$ 的蚯蚓被切成了两只长度分别为 $1$ 和 $2$ 的蚯蚓，其余蚯蚓的长度增加了 $1$。最终 4 只蚯蚓的长度分别为 $(1,2),4,3$。括号表示这个位置刚刚有一只蚯蚓被切断。</p>
<p>$2$ 秒后：一只长度为 $4$ 的蚯蚓被切成了 $1$ 和 $3$。$5$ 只蚯蚓的长度分别为：$2,3,(1,3),4$。</p>
<p>$3$ 秒后：一只长度为 $4$ 的蚯蚓被切断。$6$ 只蚯蚓的长度分别为：$3,4,2,4,(1,3)$。</p>
<p>$4$ 秒后：一只长度为 $4$ 的蚯蚓被切断。$7$ 只蚯蚓的长度分别为：$4,(1,3),3,5,2,4$。</p>
<p>$5$ 秒后：一只长度为 $5$ 的蚯蚓被切断。$8$ 只蚯蚓的长度分别为：$5,2,4,4,(1,4),3,5$。</p>
<p>$6$ 秒后：一只长度为 $5$ 的蚯蚓被切断。$9$ 只蚯蚓的长度分别为：$(1,4),3,5,5,2,5,4,6$。</p>
<p>$7$ 秒后：一只长度为 $6$ 的蚯蚓被切断。$10$ 只蚯蚓的长度分别为：$2,5,4,6,6,3,6,5,(2,4)$。</p>
<p>所以，$7$ 秒内被切断的蚯蚓的长度依次为 $3,4,4,4,5,5,6$。$7$ 秒后，所有蚯蚓长度从大到小排序为 $6,6,6,5,5,4,4,3,2,2$。</p>

# 样例二


<h4>input</h4>
<pre>3 7 1 1 3 2
3 3 2

</pre>

<h4>output</h4>
<pre>4 4 5
6 5 4 3 2

</pre>

<h4>explanation</h4>
<p>这个数据中只有 $t=2$ 与上个数据不同。只需在每行都改为每两个数输出一个数即可。</p>
<p>虽然第一行最后有一个 $6$ 没有被输出，但是第二行仍然要重新从第二个数再开始输出。</p>

# 样例三


<h4>input</h4>
<pre>3 7 1 1 3 9
3 3 2

</pre>

<h4>output</h4>
<pre>

2

</pre>

<h4>explanation</h4>
<p>这个数据中只有 $t=9$ 与上个数据不同。</p>
<p>注意第一行没有数要输出，但也要输出一个空行。</p>

# 限制与约定


<ul><li>测试点 1 ~ 3 满足$m=0$。</li>
<li>测试点 4 ~ 7 满足$n, m \leq 1,000$。</li>
<li>测试点 8 ~ 14 满足$q=0$，其中测试点 $8 \sim 9$ 还满足$m \leq 10^5$。</li>
<li>测试点 15 ~ 18 满足$m \leq 3 \times 10^5$。</li>
<li>测试点 19 ~ 20 没有特殊的约定，参见原始的数据范围。</li>
<li>测试点 1 ~ 12，15 ~ 16 还满足$v \leq 2$，这意味着 $u,v$ 的唯一可能的取值是$u=1,v=2$，即$p=0.5$。这可能会对解决问题有特殊的帮助。</li>
</ul><p>保证每行输出的整数个数不超过 $10^5$</p>
<p>每个测试点的详细数据范围见下表。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">$t$</th><th rowspan="1">$a_i$</th><th rowspan="1">$v$</th><th rowspan="1">$q$</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$= 1 $</td><td rowspan="3">$= 0 $</td><td rowspan="8">$= 1 $</td><td rowspan="11">$ \le 10^{6} $</td><td rowspan="12">$ \le 2 $</td><td rowspan="5">$= 0 $</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$= 10^{3} $</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$= 10^{5} $</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$= 1 $</td><td rowspan="4">$= 10^{3} $</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$= 10^{3} $</td></tr><tr><td rowspan="1">6</td><td rowspan="1">$= 1 $</td><td rowspan="2">$ \le 200 $</td></tr><tr><td rowspan="1">7</td><td rowspan="1">$= 10^{3} $</td></tr><tr><td rowspan="1">8</td><td rowspan="1">$= 5 \times 10^{4} $</td><td rowspan="1">$= 5 \times 10^{4} $</td><td rowspan="7">$= 0 $</td></tr><tr><td rowspan="1">9</td><td rowspan="6">$= 10^{5} $</td><td rowspan="1">$= 10^{5} $</td><td rowspan="1">$= 2 $</td></tr><tr><td rowspan="1">10</td><td rowspan="1">$= 2 \times 10^{6} $</td><td rowspan="1">$= 21 $</td></tr><tr><td rowspan="1">11</td><td rowspan="1">$= 2.5 \times 10^{6} $</td><td rowspan="1">$= 26 $</td></tr><tr><td rowspan="1">12</td><td rowspan="1">$= 3.5 \times 10^{6} $</td><td rowspan="1">$= 36 $</td><td rowspan="2">$ \le 10^{7} $</td></tr><tr><td rowspan="1">13</td><td rowspan="1">$= 5 \times 10^{6} $</td><td rowspan="1">$= 51 $</td><td rowspan="2">$ \le 10^{9} $</td></tr><tr><td rowspan="1">14</td><td rowspan="1">$= 7 \times 10^{6} $</td><td rowspan="1">$= 71 $</td><td rowspan="7">$ \le 10^{8} $</td></tr><tr><td rowspan="1">15</td><td rowspan="2">$= 5 \times 10^{4} $</td><td rowspan="1">$= 5 \times 10^{4} $</td><td rowspan="1">$= 1 $</td><td rowspan="2">$ \le 2 $</td><td rowspan="6">$ \le 200 $</td></tr><tr><td rowspan="1">16</td><td rowspan="1">$= 1.5 \times 10^{5} $</td><td rowspan="1">$= 2 $</td></tr><tr><td rowspan="1">17</td><td rowspan="4">$= 10^{5} $</td><td rowspan="1">$= 10^{5} $</td><td rowspan="1">$= 3 $</td><td rowspan="4">$ \le 10^{9} $</td></tr><tr><td rowspan="1">18</td><td rowspan="1">$= 3 \times 10^{5} $</td><td rowspan="1">$= 4 $</td></tr><tr><td rowspan="1">19</td><td rowspan="1">$= 3.5 \times 10^{6} $</td><td rowspan="1">$= 36 $</td></tr><tr><td rowspan="1">20</td><td rowspan="1">$= 7 \times 10^{6} $</td><td rowspan="1">$= 71 $</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=264">样例数据下载</a></p>
