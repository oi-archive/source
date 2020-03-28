# 题目描述


# 题目背景


<p>小d是4xx9小游戏高手。</p>

# 题目描述


<p>有一天，小d发现了一个很经典的小游戏：跳青蛙。</p>
<p>游戏在一个<strong>5</strong>个格子的棋盘上进行。在游戏的一开始，最左边的两个格子上各有一个向右的青蛙，最右边的两个格子上各有一个向左的青蛙。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/342/frog1.png" style="width:423px;" alt="青蛙"/></p>
<p>每次移动可以选取一个青蛙，向这只青蛙的前方移动一格到空格子中或跳过前方的<strong>一个不同朝向</strong>的青蛙并移动到空格子中。</p>
<p> <img class="img-responsive center-block" src="//img.uoj.ac/problem/342/frog2.png" style="width:423px;" alt="青蛙"/></p>
<p> <img class="img-responsive center-block" src="//img.uoj.ac/problem/342/frog3.png" style="width:423px;" alt="青蛙"/></p>
<p>为了使你更好地理解这个游戏，我们下发了一个游戏demo作为参考（<strong>注意</strong>：这个demo中的棋盘大小和题目中并不相同）。</p>
<p>这个游戏本身当然难不倒小d，小d轻松地就解决了这个游戏。但是一个人玩游戏实在是太寂寞了，于是小d找到了小m和他一起玩耍。小d规定，自己只能操控向右的青蛙，小m只能操控向左的青蛙。</p>
<p>小d很快发现，这个游戏想要做到双方轮流行动，就无法达到交换所有青蛙的游戏结局。于是，小d打开了<code>m</code>个游戏，并规定双方轮流行动，每次选择其中一个游戏并控制自己的青蛙行动一步（不能不动）。小d发现，这么做的话就能够使大部分的游戏最终都交换所有的青蛙了。</p>
<p>由于小d是坑队友高手，所以他们玩了一会之后，就开始互相坑害对方，都希望使对方无法行动。他们约定，当轮到一方行动时，若其所有的青蛙都无法行动，则<strong>对方</strong>获得游戏的胜利。正当博弈论大师小d计算着谁会成为最后的胜者时，电脑卡死了。小d发现，只能kill掉一些游戏才能使剩下的游戏进行下去了。由于电脑已经卡死了，小d无法自由选择kill掉哪些游戏，只能运行系统自带的随机kill小程序。具体来说，小d运行这个随机kill小程序之后，每个游戏有$\frac{1}{2}$的概率被kill掉，有$\frac{1}{2}$的概率能够继续下去。游戏之间被kill掉的概率是独立的。</p>
<p>小d思考了一番，决定如果运行小程序之后他的胜率过低，就直接重启电脑。这时，小d突然发现自己已经不记得刚才轮到谁行动了，于是他决定综合考虑自己先手和后手的胜率。</p>
<p>小d并不擅长概率论，他想让你告诉他运行小程序后，剩下的局面为小d必胜、小m必胜、先手必胜、后手必胜的概率各为多少，这样他才能更好地决定是否重启电脑。</p>
<p>为了避免精度问题，输出答案乘$2^m$之后对$998244353$取模的结果。</p>
<p><strong>注意：题目并不保证输入的所有<code>m</code>个状态中小m和小d之前的总行动步数相差不超过1，但是保证不会出现起始状态无法到达的状态</strong></p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>我们使用一个长度为5的字符串来表示一个状态，其中，<code>L</code>表示面朝<strong>右</strong>的青蛙，<code>R</code>表示面朝<strong>左</strong>的青蛙，<code>_</code>（下划线）表示空格子。例如，初始状态为<code>LL_RR</code>。</p>
<p>本题含有多组数据，第一行两个整数<code>T,C</code>($1\leq C\leq 100$)分别表示测试点编号和数据组数。</p>
<p>对于每组数据，第一行一个整数<code>n</code>($1\leq n\leq 23$)表示不同状态的棋盘个数，接下来<code>n</code>行每行一个长度为5的字符串$s_i$和一个正整数$a_i$($1\leq a_i\leq 10^6$)，分别表示棋盘的状态和在该状态下的棋盘的个数。</p>
<p>保证输入的字符串合法且不重复。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>定义$m=\sum a_i$。</p>
<p>对于每组数据，输出一行四个整数，分别表示小d必胜（即L的控制方必胜）、小m必胜（即R的控制方必胜）、先手必胜、后手必胜的概率乘$2^m$之后对$998244353$取模的结果。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">0 1
1
LL_RR 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">0 0 1 1</code></pre>
<h4>explanation</h4>
<p>对于样例1，若该游戏没有被kill，双方唯一可能的操作序列为<code>LL_RR -&gt; L_LRR -&gt; LRL_R -&gt; LR_LR -&gt; LRRL_ -&gt; LRR_L -&gt; L胜</code>，小m先手时同理，故该情况为先手必胜。若该游戏被kill了，双方都没有合法行动，后手必胜。</p>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">0 1
3
LRRL_ 1
LRR_L 1
LLR_R 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">4 2 0 2</code></pre>
<h4>explanation</h4>
<p>对于样例2，令这三个棋盘的状态从上到下为<code>A,B,C</code>，则$\{A,B,C\},\{A,B\},\{A,C\},\{A\}$为小d必胜，$\{C\},\{B,C\}$为小m必胜，$\{B\},\{\}$为后手必胜。</p>

# 样例三


<h4>input</h4>
<pre><code class="sh_plain">0 1
1
LRRL_ 1000000</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">421273116 0 0 1</code></pre>

# 限制与约定


<p>保证数据中不会出现从<code>LL_RR</code>状态无法到达的状态（如<code>RLLR_</code>），故合法的状态共有23种。</p>
<p>定义 <strong>$k-$不可达点</strong> 为从<code>LL_RR</code>操作$k$次（双方加起来一共操作$k$次，顺序任意）后依然无法到达的合法状态，如 1-不可达点 为 ：全集$\setminus${<code>LL_RR</code>,<code>L_LRR</code>,<code>LLR_R</code>} 共20个， 5-不可达点 为{<code>RLR_L</code>,<code>RRL_L</code>,<code>RR_LL</code>,<code>R_LRL</code>,<code>R_RLL</code>}。</p>
<p>对于100%的数据，$1\leq n\leq 23$,$1\leq m\leq 10^6$,$1\leq C\leq 100$，所有可能出现在该数据点的状态均为等概率出现（也就是说你可以认为最后一个点中每种状态的$a_i$之和大约为$10^8/23$）。</p>
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号($T$)</th><th rowspan="1">$C$</th><th rowspan="1">$m$</th><th rowspan="1">其他</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">=100</td><td rowspan="1">=1</td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">2</td><td rowspan="1">=100</td><td rowspan="1">$\leq 5$</td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">3</td><td rowspan="1">=100</td><td rowspan="1">$\leq 8$</td><td rowspan="1">n=m</td></tr><tr><td rowspan="1">4</td><td rowspan="1">=100</td><td rowspan="1">$\leq 10$</td><td rowspan="1">n=m</td></tr><tr><td rowspan="1">5</td><td rowspan="1">=100</td><td rowspan="1">无限制</td><td rowspan="1">n=1</td></tr><tr><td rowspan="1">6</td><td rowspan="1">=100</td><td rowspan="1">无限制</td><td rowspan="1">n=1</td></tr><tr><td rowspan="1">7</td><td rowspan="1">=100</td><td rowspan="1">$\leq 500$</td><td rowspan="1">只含5-不可达点</td></tr><tr><td rowspan="1">8</td><td rowspan="1">=100</td><td rowspan="1">$\leq6\times 10^5$</td><td rowspan="1">只含5-不可达点</td></tr><tr><td rowspan="1">9</td><td rowspan="1">=100</td><td rowspan="1">$\leq 100$</td><td rowspan="1">只含2-不可达点</td></tr><tr><td rowspan="1">10</td><td rowspan="1">=100</td><td rowspan="1">$\leq7\times 10^5$</td><td rowspan="1">只含2-不可达点</td></tr><tr><td rowspan="1">11</td><td rowspan="1">=100</td><td rowspan="1">$\leq 16$</td><td rowspan="1">只含1-不可达点</td></tr><tr><td rowspan="1">12</td><td rowspan="1">=100</td><td rowspan="1">$\leq8\times 10^5$</td><td rowspan="1">只含1-不可达点</td></tr><tr><td rowspan="1">13</td><td rowspan="1">=100</td><td rowspan="1">$\leq 14$</td><td rowspan="1">只含0-不可达点</td></tr><tr><td rowspan="1">14</td><td rowspan="1">=100</td><td rowspan="1">$\leq9\times 10^5$</td><td rowspan="1">只含0-不可达点</td></tr><tr><td rowspan="1">15</td><td rowspan="1">=100</td><td rowspan="1">$\leq 12$</td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">16</td><td rowspan="1">=100</td><td rowspan="1">$\leq 5000$</td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">17</td><td rowspan="1">=100</td><td rowspan="1">$\leq 10^5$</td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">18</td><td rowspan="1">=100</td><td rowspan="1">$\leq2\times 10^5$</td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">19</td><td rowspan="1">=100</td><td rowspan="1">无限制</td><td rowspan="1">无限制</td></tr><tr><td rowspan="1">20</td><td rowspan="1">=100</td><td rowspan="1">无限制</td><td rowspan="1">无限制</td></tr></tbody></table><p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 关于本题的Hack!


<p>在提交Hack!数据的时候，$T$ 值没有意义！</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=342">样例数据下载</a></p>
