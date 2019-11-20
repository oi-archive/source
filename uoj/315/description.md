# 题目描述

<p>蚯蚓幼儿园有 $n$ 只蚯蚓。幼儿园园长神刀手为了管理方便，时常让这些蚯蚓们列队表演。</p>
<p>所有蚯蚓用从 $1$ 到 $n$ 的连续正整数编号。每只蚯蚓的长度可以用一个正整数表示，根据入园要求，所有蚯蚓的长度都不超过 $6$。神刀手希望这些蚯蚓排成若干个队伍，初始时，每只蚯蚓各自排成一个仅有一只蚯蚓的队伍，该蚯蚓既在队首，也在队尾。</p>
<p>神刀手将会依次进行 $m$ 次操作，每个操作都是以下三种操作中的一种：</p>
<ol><li>给出 $i$ 和 $j$，令 $i$ 号蚯蚓与 $j$ 号蚯蚓所在的两个队伍合并为一个队伍，具体来说，令 $j$ 号蚯蚓紧挨在 $i$ 号蚯蚓之后，其余蚯蚓保持队伍的前后关系不变。</li>
<li>给出 $i$，令 $i$ 号蚯蚓与紧挨其后的一只蚯蚓分离为两个队伍，具体来说，在分离之后，$i$ 号蚯蚓在其中一个队伍的队尾，原本紧挨其后的那一只蚯蚓在另一个队伍的队首，其余蚯蚓保持队伍的前后关系不变。</li>
<li>给出一个正整数 $k$ 和一个长度至少为 $k$ 的数字串 $s$，对于 $s$ 的每个长度为 $k$ 的连续子串 $t$（这样的子串共有 $|s|-k+1$ 个，其中 $|s|$ 为 $s$ 的长度），定义函数 $f(t)$，询问所有这些 $f(t)$ 的<strong>乘积</strong>对 $998244353$ 取模后的结果。其中 $f(t)$ 的定义如下：</li>
</ol><p>对于当前的蚯蚓队伍，定义某个蚯蚓的<strong>向后 $k$ 数字串</strong>为：从该蚯蚓出发，沿队伍的向后方向，寻找最近的 $k$ 只蚯蚓（包括其自身），将这些蚯蚓的长度视作字符连接而成的数字串；如果这样找到的蚯蚓不足 $k$ 只，则其没有<strong>向后 $k$ 数字串</strong>。例如蚯蚓的队伍为 $10$ 号蚯蚓在队首，其后是 $22$ 号蚯蚓，其后是 $3$ 号蚯蚓（为队尾），这些蚯蚓的长度分别为 $4$、$5$、$6$，则 $10$ 号蚯蚓的<strong>向后 $3$ 数字串</strong>为 <samp>456</samp>， $22$ 号蚯蚓没有<strong>向后 $3$ 数字串</strong>，但其<strong>向后 $2$ 数字串</strong>为 <samp>56</samp>，其<strong>向后 $1$ 数字串</strong>为 <samp>5</samp>。</p>
<p>而 $f(t)$ 表示所有蚯蚓中，<strong>向后 $k$ 数字串</strong>恰好为 $t$ 的蚯蚓只数。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入文件的第一行有两个正整数 $n,m$，分别表示蚯蚓的只数与操作次数。</p>
<p>第二行包含 $n$ 个不超过 $6$ 的正整数，依次表示编号为 $1,2,\dots,n$ 的蚯蚓的长度。</p>
<p>接下来 $m$ 行，每行表示一个操作。每个操作的格式可以为：</p>
<ul><li><code>1 i j</code>（$1 \leq i, j \leq n$）表示：令 $i$ 号与 $j$ 号蚯蚓<strong>所在</strong>的两个队伍合并为一个队伍，新队伍中， $j$ 号蚯蚓紧挨在 $i$ 号蚯蚓之后。保证在此操作之前， $i$ 号蚯蚓在某个队伍的队尾， $j$ 号蚯蚓在某个队伍的队首，且两只蚯蚓不在同一个队伍中。</li>
<li><code>2 i</code>（$1 \leq i \leq n$）表示：令 $i$ 号蚯蚓与紧挨其后一个蚯蚓分离为两个队伍。保证在此操作之前， $i$ 号蚯蚓不是某个队伍的队尾。</li>
<li><code>3 s k</code>（$k$ 为正整数，$s$ 为一个长度至少为 $k$ 的数字串）表示：询问 $s$ 的每个长度为 $k$ 的子串 $t$ 的 $f(t)$ 的乘积，对 $998244353$ 取模的结果。 $f(t)$ 的定义见题目描述。</li>
</ul><p>同一行输入的相邻两个元素之间，用恰好一个空格隔开。</p>
<p>输入文件可能较大，请不要使用过于缓慢的读入方式。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>依次对于每个形如 <code>3 s k</code> 的操作，输出一行，仅包含一个整数，表示询问的结果。</p>

# 样例一


<h4>input</h4>
<pre>5 9
3 1 3 5 3
3 333135 2
3 333135 1
1 1 3
1 2 5
1 3 2
1 5 4
3 333135 2
3 333135 1
3 333135 3

</pre>



<h4>output</h4>
<pre>0
81
1
81
0

</pre>


<h4>explanation</h4>
<p>第一次询问：由于每个队伍均只有一只蚯蚓，所以没有任何蚯蚓有<strong>向后 $2$ 数字串</strong>，答案为 $f(\mathtt{33}) \times f(\mathtt{33}) \times f(\mathtt{31}) \times f(\mathtt{13}) \times f(\mathtt{35}) = 0 \times 0 \times 0 \times 0 \times 0 = 0$ 。</p>
<p>第二次询问：每个队伍仍只有一只蚯蚓，每只蚯蚓的<strong>向后 $1$ 数字串</strong>就是将自己的长度视为字符的数字串，即：得到的 $5$ 个<strong>向后 $1$ 数字串</strong>为 <samp>1</samp>、<samp>3</samp>、<samp>3</samp>、<samp>3</samp>、<samp>5</samp>（不分先后顺序，下同），答案为 $f(\mathtt{3}) \times f(\mathtt{3}) \times f(\mathtt{3}) \times f(\mathtt{1}) \times f(\mathtt{3}) \times f(\mathtt{5}) = 3 \times 3 \times 3 \times 1 \times 3 \times 1 = 81$ 。</p>
<p>接下来进行了若干次队伍的合并操作，使得所有蚯蚓合并成了一个队伍，这个队伍从前到后的蚯蚓依次为： $1$ 号蚯蚓（长度为 $3$ ）、$3$ 号蚯蚓（长度为 $3$ ）、$2$ 号蚯蚓（长度为 $1$ ）、$5$ 号蚯蚓（长度为 $3$ ）、$4$ 号蚯蚓（长度为 $5$ ）。</p>
<p>第三次询问： $4$ 号蚯蚓没有<strong>向后 $2$ 数字串</strong>，而其他蚯蚓都有。得到的 $4$ 个<strong>向后 $2$ 数字串</strong>为 <samp>13</samp>、<samp>31</samp>、<samp>33</samp>、<samp>35</samp>，答案为 $f(\mathtt{33}) \times f(\mathtt{33}) \times f(\mathtt{31}) \times f(\mathtt{13}) \times f(\mathtt{35}) = 1 \times 1 \times 1 \times 1 \times 1 = 1$。</p>
<p>第四次询问：虽然队伍的排列方式改变了，但是每只蚯蚓的<strong>向后 $1$ 数字串</strong>没有发生改变，所以答案同第二次询问。</p>
<p>第五次询问： $4$ 号蚯蚓、$5$ 号蚯蚓没有<strong>向后 $3$ 数字串</strong>，而其他蚯蚓都有。得到的 $3$ 个<strong>向后 $3$ 数字串</strong>为 <samp>135</samp>、<samp>331</samp>、<samp>313</samp>，答案为 $f(\mathtt{333}) \times f(\mathtt{331}) \times f(\mathtt{313}) \times f(\mathtt{135}) = 0 \times 1 \times 1 \times 1 = 0$。</p>

# 样例二


<h4>input</h4>
<pre>2 10
6 6
3 666666 1
1 1 2
3 666666 2
3 666666 4
3 666666666666666666666666666666 1
2 1
1 2 1
3 666666 2
3 666666 4
3 666666666666666666666666666666 1

</pre>



<h4>output</h4>
<pre>64
1
0
75497471
1
0
75497471

</pre>


<h4>explanation</h4>
<p>对于第四次、第七次询问，输入的 $s$ 为 30 个字符 <samp>6</samp>，所有 $f(t)$ 的乘积是 $2^{30} = 1073741824$，输出的结果是这个数对于 $998244353$ 取模的结果。</p>

# 样例三


<p>见样例数据下载。</p>
<p>该组样例的数据范围同第 5 个测试点。</p>

# 样例四


<p>见样例数据下载。</p>
<p>该组样例的数据范围同第 10 个测试点。</p>

# 样例五


<p>见样例数据下载。</p>
<p>该组样例的数据范围同第 15 个测试点。</p>

# 样例六


<p>见样例数据下载。</p>
<p>该组样例的数据范围同第 20 个测试点。</p>

# 限制与约定


<p>保证 $n \leq 2 \times 10^{5}$，$m \leq 5 \times 10^{5}$，$k \leq 50$ 。</p>
<p>设 $\sum |s|$ 为某个输入文件中所有询问的 $s$ 的长度总和，则 $\sum |s| \leq 10^{7}$  。</p>
<p>设 $c$ 为某个输入文件中形如 <code>2 i</code> 的操作的次数，则 $c \leq 10^{3}$ 。</p>
<p>每个测试点的详细信息见下表：</p>
<div class="table-responsive">
 <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">$k$</th><th rowspan="1">$\sum |s|$</th><th rowspan="1">$c$</th><th rowspan="1">全为 <samp>1</samp></th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$=1$</td><td rowspan="1">$\leq 10^{3}$</td><td rowspan="1">$=1$</td><td rowspan="5">$\leq 10^{3}$</td><td rowspan="2">$=0$</td><td rowspan="6">No</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$\leq 20$</td><td rowspan="1">$\leq 40$</td><td rowspan="1">$\leq 10$</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$\leq 150$</td><td rowspan="1">$\leq 2,000$</td><td rowspan="3">$\leq 50$</td><td rowspan="1">$\leq 10^{3}$</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$\leq 500$</td><td rowspan="1">$\leq 600$</td><td rowspan="1">$=0$</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$\leq 10^{3}$</td><td rowspan="1">$\leq 2,000$</td><td rowspan="2">$\leq 10^{3}$</td></tr><tr><td rowspan="1">6</td><td rowspan="6">$\leq 5 \times 10^{4}$</td><td rowspan="4">$\leq 6 \times 10^{4}$</td><td rowspan="1">$\leq 5$</td><td rowspan="4">$\leq 5 \times 10^{4}$</td></tr><tr><td rowspan="1">7</td><td rowspan="5">$\leq 50$</td><td rowspan="2">$=0$</td><td rowspan="1">Yes</td></tr><tr><td rowspan="1">8</td><td rowspan="5">No</td></tr><tr><td rowspan="1">9</td><td rowspan="1">$\leq 10^{3}$</td></tr><tr><td rowspan="1">10</td><td rowspan="2">$\leq 8 \times 10^{4}$</td><td rowspan="2">$\leq 2.5 \times 10^{6}$</td><td rowspan="1">$=0$</td></tr><tr><td rowspan="1">11</td><td rowspan="2">$\leq 10^{3}$</td></tr><tr><td rowspan="1">12</td><td rowspan="6">$\leq 10^{5}$</td><td rowspan="4">$\leq 1.1 \times 10^{5}$</td><td rowspan="1">$\leq 6$</td><td rowspan="4">$\leq 10^{5}$</td></tr><tr><td rowspan="1">13</td><td rowspan="5">$\leq 50$</td><td rowspan="2">$=0$</td><td rowspan="1">Yes</td></tr><tr><td rowspan="1">14</td><td rowspan="7">No</td></tr><tr><td rowspan="1">15</td><td rowspan="1">$\leq 10^{3}$</td></tr><tr><td rowspan="1">16</td><td rowspan="2">$\leq 1.5 \times 10^{5}$</td><td rowspan="2">$\leq 5 \times 10^{6}$</td><td rowspan="1">$=0$</td></tr><tr><td rowspan="1">17</td><td rowspan="1">$\leq 10^{3}$</td></tr><tr><td rowspan="1">18</td><td rowspan="8">$\leq 2 \times 10^{5}$</td><td rowspan="2">$\leq 5 \times 10^{5}$</td><td rowspan="2">$=1$</td><td rowspan="2">$\leq 10^{7}$</td><td rowspan="1">$=0$</td></tr><tr><td rowspan="1">19</td><td rowspan="2">$\leq 10^{3}$</td></tr><tr><td rowspan="1">20</td><td rowspan="4">$\leq 2.5 \times 10^{5}$</td><td rowspan="1">$\leq 7$</td><td rowspan="4">$\leq 2 \times 10^{5}$</td></tr><tr><td rowspan="1">21</td><td rowspan="5">$\leq 50$</td><td rowspan="2">$=0$</td><td rowspan="1">Yes</td></tr><tr><td rowspan="1">22</td><td rowspan="4">No</td></tr><tr><td rowspan="1">23</td><td rowspan="1">$\leq 10^{3}$</td></tr><tr><td rowspan="1">24</td><td rowspan="2">$\leq 3 \times 10^{5}$</td><td rowspan="2">$\leq 10^{7}$</td><td rowspan="1">$=0$</td></tr><tr><td rowspan="1">25</td><td rowspan="1">$\leq 10^{3}$</td></tr></tbody></table></div>

<p>如果一个测试点的 “全为 <samp>1</samp>” 的一列为 “Yes”，表示该测试点的所有蚯蚓的长度均为 $1$，并且所有询问串 $s$ 的每一位也均为 <samp>1</samp>。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$1\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=315">样例数据下载</a></p>
