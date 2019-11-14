# 题目描述

<p>小 q 有 $n$ 只机器人，一开始他把机器人放在了一条数轴上，第 $i$ 只机器人在 $a_i$ 的位置上静止，而自己站在原点。</p>
<p>在这之后小 q 会执行一些操作，他想要命令一个机器人向左或者向右移动 $x$ 格。但是机器人似乎听不清小 q 的命令，事实上它们会以每秒 $x$ 格的速度匀速移动。</p>
<p>看着自己的机器人越走越远，小 q 很着急，他想知道当前离他（原点）最远的机器人有多远。</p>
<p>具体的操作以及询问见输入格式。注意，不同的机器人之间互不影响，即不用考虑两个机器人撞在了一起的情况。</p>

# 输入格式


<p>共有 $m$ 个事件，输入将会按事件的时间顺序给出。</p>
<p>第一行两个正整数 $n,m$。</p>
<p>接下来一行 $n$ 个整数，第 $i$ 个数是 $a_i$，表示第 $i$ 个机器人初始的位置（初始移动速度为 $0$）。</p>
<p>接下来 $m$ 行，每行行首是一个非负整数 $t_i$，表示该事件点发生的时刻（以秒为单位）。第二个是一个字符串 $S$ ，代表操作的种类。数字与字符串之间用一个空格隔开。接下来的输入按 $S$ 的种类分类。</p>
<ol><li>若 $S$ 是 “<samp>command</samp>”（不带引号），则接下来两个整数 $k_i,x_i$，表示小 q 对第 $k_i$ 个机器人执行了操作，该机器人的速度将会被重置，变为向数轴正方向每秒移动 $x_i$ 格（若 $x_i$ 为负数就相当于向数轴负方向每秒移动 $\lvert x_i \rvert$ 格）。保证 $1 \leq k_i \leq n$。</li>
<li>若 S 是 “<samp>query</samp>”（不带引号），则你需要输出当前离原点最远的机器人有多远。</li>
</ol><p>保证 $t_1 \leq t_2 \leq t_2 \leq \dots \leq t_m$。</p>
<p>（注：若同一时间发生多次操作，则按读入顺序依次执行）</p>

# 输出格式


<p>对于每个 <samp>query</samp> 询问，输出一行，包含一个整数表示正确的答案。</p>
<p>C/C++ 输入输出 long long 时请用 <code>%lld</code>。<strong>由于本题数据量较大，建议不要使用 cin/cout 进行输入输出。</strong></p>

# 样例一


<h4>input</h4>
<pre>4 5
-20 0 20 100
10 command 1 10
20 command 3 -10
30 query
40 command 1 -30
50 query

</pre>

<h4>output</h4>
<pre>180
280

</pre>

<h4>explanation</h4>
<p>第一个命令执行时，各个机器人的位置为：$-20, 0, 20, 100$。</p>
<p>第二个命令执行时，各个机器人的位置为：$80, 0, 20, 100$。</p>
<p>第一个询问时，各个机器人的位置为：$180, 0, -80, 100$。</p>
<p>第三个命令执行时，各个机器人的位置为：$280, 0, -180, 100$。</p>
<p>第二个询问时，各个机器人的位置为：$-20, 0, -280, 100$。</p>

# 限制与约定


<p>设 <samp>command</samp> 的个数为 $C$，<samp>query</samp> 的个数为 $Q$。（所以 $C + Q = m$）</p>
<p>对于所有的事件满足 $0 \leq t_i \leq 10^9$，对于所有的 <samp>command</samp> 满足 $\lvert x_i \rvert \leq 10^4$。</p>
<p>对于所有的机器人满足 $\lvert a_i \rvert \leq 10^9$。</p>
<p>所有测试数据的范围和特点如下表所示：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>数据范围</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n, m \leq 2000$</td><td rowspan="2">无</td></tr><tr><td>2</td></tr><tr><td>3</td><td>$n, m \leq 10^5$</td><td>$-1 \leq x_i \leq 1$</td></tr><tr><td>4</td><td rowspan="2">$n, C \leq 10^5$，$Q \leq 5 \times 10^5$</td><td rowspan="2">两个机器人发生碰面或者超越另一个的次数 $\leq 4 \times 10^5$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="3">$n, m \leq 10^5$</td><td rowspan="2">不会在 $t_i &gt; 0$ 时出现 <samp>command</samp> 操作</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">无</td></tr><tr><td>9</td><td rowspan="2">$n, C \leq 10^5$，$Q \leq 5 \times 10^5$</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 来源


<p>中国国家集训队互测2015 - By 张恒捷</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=88">样例数据下载</a></p>
