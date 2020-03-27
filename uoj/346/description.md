# 题目描述


# 题目描述


<p>IA是一名会唱歌的女孩子。</p>
<p>IOI2018就要来了，IA决定给参赛选手们写一首歌，以表达美好的祝愿。这首歌一共有$n$个音符，第$i$个音符的音高为$h_i$。IA的音域是$A$，她只能唱出$1\sim A$中的正整数音高。因此$1\le h_i\le A$。</p>
<p>在写歌之前，IA需要确定下这首歌的结构，于是她写下了$Q$条限制，其中第$i$条为：编号在$l_i$到$r_i$之间的音符的最高音高为$m_i$。在确定了结构之后，她就可以开始写歌了。不过她还是想知道，一共有多少种可能的歌曲满足她的所有限制？她听说你还有9个月就要去IOI了，于是希望你帮她计算一下这个值。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入的第一行包含一个整数$T(T\le 20)$，代表测试数据的组数。</p>
<p>每组数据的第一行包含三个正整数$n,Q,A$。接下来$Q$行，每行三个整数$l_i,r_i,m_i$，表示一条限制。保证$1\le l_i\le r_i\le n$，$1\le m_i\le A$。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出文件只有一行，表示可能的歌曲数目。这个数可能很大，请将答案模 $998244353$ 输出。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">1
3 2 3
1 2 3
2 3 2</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">3</code></pre>
<h4>explanation</h4>
<p>以下是三种可能的歌曲：$(3,1,2),(3,2,1),(3,2,2)$。</p>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">2
4 2 4
1 2 3
2 3 4
7 3 74
3 6 56
2 5 56
3 7 70</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">20
160326468</code></pre>



# 限制与约定


<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n$</th><th rowspan="1">$Q$</th><th rowspan="1">$A$</th><th rowspan="1">$m_i$</th><th rowspan="1">分数</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$\leq 7$</td><td rowspan="1">$\leq 7$</td><td rowspan="1">$\leq 7$</td><td rowspan="1">$\leq A$</td><td rowspan="1">5</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$\leq 10$</td><td rowspan="1">$\leq 500$</td><td rowspan="1">$\leq 9\times 10^8$</td><td rowspan="1">$\leq A$</td><td rowspan="1">10</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$\leq 500$</td><td rowspan="1">$\leq 10$</td><td rowspan="1">$\leq 9\times 10^8$</td><td rowspan="1">$\leq A$</td><td rowspan="1">8</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$\leq 500$</td><td rowspan="1">$\leq 500$</td><td rowspan="1">$=2$</td><td rowspan="1">$=2$</td><td rowspan="1">12</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$\leq 9\times 10^8$</td><td rowspan="1">$\leq 500$</td><td rowspan="1">$=2$</td><td rowspan="1">$=2$</td><td rowspan="1">18</td></tr><tr><td rowspan="1">6</td><td rowspan="1">$\leq 500$</td><td rowspan="1">$\leq 500$</td><td rowspan="1">$\leq 9\times 10^8$</td><td rowspan="1">$\leq A$</td><td rowspan="1">28</td></tr><tr><td rowspan="1">7</td><td rowspan="1">$\leq 9\times 10^8$</td><td rowspan="1">$\leq 500$</td><td rowspan="1">$\leq 9\times 10^8$</td><td rowspan="1">$\leq A$</td><td rowspan="1">19</td></tr></tbody></table><p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=346">样例数据下载</a></p>
