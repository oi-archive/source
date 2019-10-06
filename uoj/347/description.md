# 题目描述

<p>11328 年，C 国的科学家们研发了一种高速传送通道，可以在很短的时间内把居民从通道的一端送往另一端，这些通道都是<strong>双向</strong>的。</p>
<p>美中不足的是，这种传送通道需要进行大量的维护和检修。经过规划，C 国总统决定在 M 城中新建这种通道，在 M 城中，建立了 $n$ 个传送站和 $3\times (n-1)$ 条传送通道，这些传送通道被分为 3 组，每一组都包含了 $(n-1)$ 条通道。</p>
<p>当任意一组通道运行时，居民都可以通过这组通道从任意一个传送站前往任意的另一个传送站。也就是说，所有的传送站都会被通道所连通。</p>
<p>三组通道按照 1、2、3 的顺序轮流运行，循环反复。在任意一个时刻，都有且只有一组传送通道可以使用。形式化地，在第 $i$ 天中，有且只有第 $((i-1) \bmod 3 + 1)$ 组通道运行。</p>
<p>C 国著名科学家 Access Globe 正在进行一项社会调查实验：调查两个传送站之间的传送通道使用者的信息。Access Globe 的计划是这样的：</p>
<ul><li>选定两个传送站 $a$、$b$</li>
<li>第一天，他从 $a$ 出发，使用正在运行的这组通道沿最短路径到达 $b$，并调查经过的所有通道上使用者的信息</li>
<li>第二天，他从 $b$ 出发，使用正在运行的这组通道沿最短路径到达 $a$，并调查经过的所有通道上使用者的信息</li>
<li>第三天，他从 $a$ 出发，使用正在运行的这组通道沿最短路径到达 $b$，并调查经过的所有通道上使用者的信息</li>
</ul><p>Access Globe 知道每一条传输线路在运行时的使用者人数。他希望找出一对 $a$、$b$，使得在整个实验过程中所有经过的通道的使用者数量之和最大。Access Globe 希望参加 CCF NOI 2018 冬令营的你帮他解决这个简单的小问题。如果你成功地解决了这个问题，Access Globe 会送你一份小礼物——100 分！</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入文件的第 $1$ 行包含一个正整数 $n$，表示传送站的个数，传送站从 $1$ 到 $n$ 编号；</p>
<p>输入文件的第 $2$ 到第 $n$ 行，每行包含 $3$ 个数 $u,v,w$，表示第一组通道中有一条连接 $u,v$ 的通道，其运行时使用者数量为 $w$ 人；</p>
<p>输入文件的第 $(n+1)$ 到第 $(2n-1)$ 行，每行包含 $3$ 个数 $u,v,w$，表示第二组通道中有一条连接 $u,v$ 的通道，其运行时使用者数量为 $w$ 人；</p>
<p>输入文件的第 $2n$ 到第 $(3n-2)$ 行，每行包含 $3$ 个数 $u,v,w$，表示第三组通道中有一条连接 $u,v$ 的通道，其运行时使用者数量为 $w$ 人。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出文件共 $1$ 行，包含一个整数，表示最大的使用者数量之和。</p>

# 样例一


<h4>input</h4>
<pre>5
1 2 2
1 3 0
1 4 1
4 5 7
1 2 0
2 3 1
2 4 1
2 5 3
1 5 2
2 3 8
3 4 5
4 5 1

</pre>



<h4>output</h4>
<pre>27

</pre>

<h4>explanation</h4>
<p>一种可行的方案是选择 $a=2,b=5$，这样的使用者数量之和为 $(3)+(8+5+1)+(2+1+7)=27$。</p>

# 提示


<ul><li><p>在两组通道中，可能都包含了连接传送站 $x,y$ 的通道，此时我们认为这两条通道是<strong>不同</strong>的。</p>
</li>
<li><p>特殊性质中，A 组通道和 B 组通道的“构成完全相同”是指：如果在 A 组中 $u,v$ 之间存在一条使用人数为 $w$ 的通道，那么在 B 组中 $u,v$ 之间一定也存在一条使用人数为 $w$ 的通道。是否相同<strong>与描述方式与描述顺序均无关</strong>。即在构成完全相同的两组通道 A 和 B中，<strong>通道输入的顺序不一定相同，每条通道的端点的输入顺序也不一定相同</strong>（对于 A、B 组中一条连接 $u,v$ 的使用人数为 $w$ 的通道，一种可能出现的输入为：A 组通道中输入 $u$ $v$ $w$，而 B 组通道中输入 $v$ $u$ $w$）。</p>
</li>
</ul>
# 限制和约定


<p>对于所有数据，$2\le n\le 10^{5}, 0\le w\le 10^{12}$。</p>
<p>特殊性质 0：任意两组通道构成完全相同。</p>
<p>特殊性质 1：第二组通道和第三组通道构成完全相同。</p>
<p>特殊性质 2：对于第二组的每一个传送站，最多只有两个通道可以到达它，且编号为 $x,y$ 的传送站之间通过<strong>一条</strong>通道直接连接充要条件是 $|x-y|=1$。</p>
<p>特殊性质 3：对于第三组的每一个传送站，最多只有两个通道可以到达它。</p>
<p>特殊性质 4：$n \le 3000$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点</th><th rowspan="1">$n\le$</th><th rowspan="1">$w$</th><th rowspan="1">特殊性质</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="3">$10^{2}$</td><td rowspan="1">$=1$</td><td rowspan="1">$0,1$</td></tr><tr><td rowspan="1">2</td><td rowspan="2">$\le 10^{12}$</td><td rowspan="2">无</td></tr><tr><td rowspan="1">3</td></tr><tr><td rowspan="1">4</td><td rowspan="4">$3,000$</td><td rowspan="2">$=1$</td><td rowspan="1">$0,1$</td></tr><tr><td rowspan="1">5</td><td rowspan="3">无</td></tr><tr><td rowspan="1">6</td><td rowspan="6">$\le 10^{12}$</td></tr><tr><td rowspan="1">7</td></tr><tr><td rowspan="1">8</td><td rowspan="4">$10^{5}$</td><td rowspan="1">$0,1,2,3$</td></tr><tr><td rowspan="1">9</td><td rowspan="3">$0,1$</td></tr><tr><td rowspan="1">10</td></tr><tr><td rowspan="1">11</td></tr><tr><td rowspan="1">12</td><td rowspan="2">$5 \times 10^{4}$</td><td rowspan="1">$=1$</td><td rowspan="3">$1,2,3$</td></tr><tr><td rowspan="1">13</td><td rowspan="2">$\le 10^{12}$</td></tr><tr><td rowspan="1">14</td><td rowspan="1">$10^{5}$</td></tr><tr><td rowspan="1">15</td><td rowspan="1">$5 \times 10^{4}$</td><td rowspan="1">$=1$</td><td rowspan="2">$1$</td></tr><tr><td rowspan="1">16</td><td rowspan="1">$10^{5}$</td><td rowspan="1">$\le 10^{12}$</td></tr><tr><td rowspan="1">17</td><td rowspan="2">$5 \times 10^{4}$</td><td rowspan="1">$=1$</td><td rowspan="3">$2,3$</td></tr><tr><td rowspan="1">18</td><td rowspan="2">$\le 10^{12}$</td></tr><tr><td rowspan="1">19</td><td rowspan="1">$10^{5}$</td></tr><tr><td rowspan="1">20</td><td rowspan="4">$5 \times 10^{4}$</td><td rowspan="1">$=1$</td><td rowspan="2">$3$</td></tr><tr><td rowspan="1">21</td><td rowspan="1">$\le 10^{12}$</td></tr><tr><td rowspan="1">22</td><td rowspan="1">$=1$</td><td rowspan="4">无</td></tr><tr><td rowspan="1">23</td><td rowspan="1">$\le 10^{12}$</td></tr><tr><td rowspan="1">24</td><td rowspan="2">$10^{5}$</td><td rowspan="1">$=1$</td></tr><tr><td rowspan="1">25</td><td rowspan="1">$\le 10^{12}$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$4\texttt{s}$</p>
<p><strong>空间限制：</strong>$1\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=347">样例数据下载</a></p>
