# 题目描述

<p>P 博士将他的计算任务抽象为对一个整数的操作。</p>
<p>具体来说，有一个整数 $x$ ，一开始为0。</p>
<p>接下来有 $n$ 个操作，每个操作都是以下两种类型中的一种：</p>
<ul><li><code>1</code> $a$ $b$ ：将 $x$ 加上整数 $a \cdot 2 ^ b$，其中 $a$ 为一个整数，$b$ 为一个非负整数</li>
<li><code>2</code> $k$ ：询问 $x$ 在用二进制表示时，位权为 $2 ^ k$ 的位的值（即这一位上的 $1$ 代表 $2 ^ k$ ）</li>
</ul><p>保证在任何时候，$x \ge 0$。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入的第一行包含四个正整数 $n, t_1, t_2, t_3$，$n$ 的含义见题目描述，$t_1, t_2, t_3$ 的具体含义见子任务。</p>
<p>接下来 $n$ 行，每行给出一个操作，具体格式和含义见题目描述。</p>
<p>同一行输入的相邻两个元素之间，用恰好一个空格隔开。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>对于每个询问操作，输出一行，表示该询问的答案（0或1）。
对于加法操作，没有任何输出。</p>

# 样例一


<h4>input</h4>
<pre>10 3 1 2
1 100 0
1 2333 0
1 -233 0
2 5
2 7
2 15
1 5 15
2 15
1 -1 12
2 15

</pre>



<h4>output</h4>
<pre>0
1
0
1
0

</pre>


<h4>explanation</h4>
<p>样例中有 $10$ 个操作：
第 $1$ 个为将 $x$ 加上 $100 \times 2^0$ ，操作后， $x= 100$ ；</p>
<p>第 $2$ 个为将 $x$ 加上 $2333 \times 2^0$ ，操作后， $x= 2433$ ；</p>
<p>第 $3$ 个为将 $x$ 加上 $-233 \times 2^0$ ，操作后， $x= 2200$ ；</p>
<p>第 $4$ 个为询问 $x$ 位权为 $2^5$ 的位上的值， $x$ 在二进制下为 $100010011000$ ，答案为 $0$ ；</p>
<p>第 $5$ 个为询问 $x$ 位权为 $2^7$ 的位上的值， $x$ 在二进制下为 $100010011000$ ，答案为 $1$ ；</p>
<p>第 $6$ 个为询问 $x$ 位权为 $2^{15}$ 的位上的值， $x$ 在二进制下为 $100010011000$ ，答案为 $0$ ；</p>
<p>第 $7$ 个为将 $x$ 加上 $5 \times 2^{15} = 163840$ ，操作后， $x= 166040$ ；</p>
<p>第 $8$ 个为询问 $x$ 位权为 $2^{15}$ 的位上的值， $x$ 在二进制下为 $101000100010011000$ ，答案为 $1$ ；</p>
<p>第 $9$ 个为将 $x$ 加上 $-1 \times 2^{12} = -4096$ ，操作后， $x= 161944$ ；</p>
<p>第 $10$ 个为询问 $x$ 位权为 $2^{15}$ 的位上的值， $x$ 在二进制下为 $100111100010011000$ ，答案为 $0$ 。</p>

# 样例二


<p>见下载文件中的 <em>ex_integer2.in</em> 与 <em>ex_integer2.ans</em>。</p>
<p>该组样例的数据范围同第7个测试点。</p>

# 样例三


<p>见下载文件中的 <em>ex_integer3.in</em> 与 <em>ex_integer3.ans</em>。</p>
<p>该组样例的数据范围同第13个测试点。</p>

# 样例四


<p>见下载文件中的 <em>ex_integer4.in</em> 与 <em>ex_integer4.ans</em>。</p>
<p>该组样例的数据范围同第14个测试点。</p>

# 限制与约定


<p>在所有测试点中，$1 \le t_1 \le 3, 1 \le t_2 \le 4, 1 \le t_3 \le 2$。
不同的 $t_1, t_2, t_3$ 对应的特殊限制如下：</p>
<ul><li>对于 $t_1 = 1$ 的测试点，满足 $a = 1$</li>
<li>对于 $t_1 = 2$ 的测试点，满足 $|a| = 1$</li>
<li>对于 $t_1 = 3$ 的测试点，满足 $|a| \le 10 ^ 9$</li>
<li>对于 $t_2 = 1$ 的测试点，满足 $0 \le b,k \le 30$</li>
<li>对于 $t_2 = 2$ 的测试点，满足 $0 \le b,k \le 100$</li>
<li>对于 $t_2 = 3$ 的测试点，满足 $0 \le b,k \le n$</li>
<li>对于 $t_2 = 4$ 的测试点，满足 $0 \le b,k \le 30 n$</li>
<li>对于 $t_3 = 1$ 的测试点，保证所有询问操作都在所有修改操作之后</li>
<li>对于 $t_3 = 2$ 的测试点，不保证询问操作和修改操作的先后顺序</li>
</ul><p>本题共25个测试点，每个测试点4分。各个测试点的数据范围如下：</p>
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n \le$</th><th rowspan="1">$t_1$</th><th rowspan="1">$t_2$</th><th rowspan="1">$t_3$</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$10$</td><td rowspan="3">3</td><td rowspan="1">1</td><td rowspan="4">2</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$100$</td><td rowspan="2">2</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$2000$</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$4000$</td><td rowspan="1">1</td><td rowspan="3">3</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$6000$</td><td rowspan="1">3</td><td rowspan="1">1</td></tr><tr><td rowspan="1">6</td><td rowspan="1">$8000$</td><td rowspan="1">2</td><td rowspan="4">2</td></tr><tr><td rowspan="1">7</td><td rowspan="1">$9000$</td><td rowspan="5">3</td><td rowspan="1">4</td></tr><tr><td rowspan="1">8</td><td rowspan="1">$10000$</td><td rowspan="1">3</td></tr><tr><td rowspan="1">9</td><td rowspan="1">$30000$</td><td rowspan="2">4</td></tr><tr><td rowspan="1">10</td><td rowspan="1">$50000$</td><td rowspan="1">1</td></tr><tr><td rowspan="1">11</td><td rowspan="1">$60000$</td><td rowspan="1">3</td><td rowspan="12">2</td></tr><tr><td rowspan="1">12</td><td rowspan="1">$65000$</td><td rowspan="1">2</td><td rowspan="5">4</td></tr><tr><td rowspan="1">13</td><td rowspan="1">$70000$</td><td rowspan="2">3</td></tr><tr><td rowspan="1">14</td><td rowspan="1">$200000$</td></tr><tr><td rowspan="1">15</td><td rowspan="1">$300000$</td><td rowspan="1">2</td></tr><tr><td rowspan="1">16</td><td rowspan="1">$400000$</td><td rowspan="4">3</td></tr><tr><td rowspan="1">17</td><td rowspan="1">$500000$</td><td rowspan="1">3</td></tr><tr><td rowspan="1">18</td><td rowspan="1">$600000$</td><td rowspan="4">4</td></tr><tr><td rowspan="1">19</td><td rowspan="1">$700000$</td></tr><tr><td rowspan="1">20</td><td rowspan="1">$800000$</td><td rowspan="1">1</td></tr><tr><td rowspan="1">21</td><td rowspan="1">$900000$</td><td rowspan="1">2</td></tr><tr><td rowspan="1">22</td><td rowspan="1">$930000$</td><td rowspan="4">3</td><td rowspan="1">3</td></tr><tr><td rowspan="1">23</td><td rowspan="1">$960000$</td><td rowspan="1">4</td><td rowspan="1">1</td></tr><tr><td rowspan="1">24</td><td rowspan="1">$990000$</td><td rowspan="1">3</td><td rowspan="2">2</td></tr><tr><td rowspan="1">25</td><td rowspan="1">$1000000$</td><td rowspan="1">4</td></tr></tbody></table><p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=314">样例数据下载</a></p>
