# 题目描述

<p>最近，小Z迷上了一款新型消除游戏。这款游戏在一个$n\times m$的方格中进行。初始时方格中均为$0 \sim 9$的整数。进行消除后方格中会出现空白，用$-1$表示。为了方便，我们将第$i$行，第$j$列的数记为$A_{i,j}$，并将其坐标记为$(i,j)$。</p>
<p>给定三个参数$l_{min},l_{max}$以及$K$，玩家可以进行不超过$K$次操作。对于每次操作，玩家需要在方格中找到一条长度为$l$的路径。形式化地，该路径用两个长度为$l$的序列$x_1,x_2,\ldots,x_l$和$y_1,y_2,\ldots,y_l$表示，需要满足如下条件：</p>
<ol><li>$1\le x_i\le n$, $1\le y_i\le m$，其中$1\le i\le l$，即$(x_i,y_i)$对应于方格中的一个合法位置；</li>
<li>$\left|x_i-x_{i+1} \right|+ \left|y_i-y_{i+1} \right|=1$，其中$1 \le i &lt; l$，即$(x_i,y_i)$与$(x_{i+1},y_{i+1})$是方格中相邻的两个位置；</li>
<li>$x_i \neq x_j$ 或 $y_i \neq y_j$，其中 $1\le i &lt; j\le l$，即路径不能经过重复的格子；</li>
<li>$A_{x_i,y_i} \neq -1$，其中$1\le i\le l$，即路径不能经过空白的格子；</li>
<li>$A_{x_1,y_1} \neq 0$，即路径不能以数字$0$为起点；</li>
<li>$l_{min}\le l\le l_{max}$，即路径的长度需要在给定的范围内。</li>
</ol><p>将路径上的数字串成一个整数$N$，形式化地</p>
<p>\begin{equation}
N=\sum\limits_{i=1}^l A_{x_i,y_i}\times 10^{l-i}
\end{equation}</p>
<p>游戏会给出两个参数$c_1$, $c_2$用于计算玩家本次操作的得分：</p>
<ol><li>如果数$N$是质数，那么将获得<strong>质数得分</strong>$l^{c_1}$，否则获得<strong>质数得分</strong>$1$。</li>
<li>如果数$N$是回文数（即，将数$N$的十进制表达看成一个字符串，这个字符串的逆序串和它本身完全相同），那么将获得<strong>回文数得分</strong>$l^{c_2}$，否则获得<strong>回文数得分</strong>$1$。</li>
<li>如果<strong>质数得分</strong>和<strong>回文数得分</strong>均为$1$，那么<strong>本次操作的得分</strong>为$0$；否则<strong>本次操作的得分</strong>为<strong>质数得分与回文数得分</strong>之和。</li>
</ol><p>每次操作过后，若<strong>该次操作的得分</strong>等于$0$，那么你浪费了一次操作机会，而局面不会有任何改变。若<strong>该次操作的得分</strong>大于$0$，则将路径上的数替换为空白，并使空白上方的数字垂直下落。形式化地，执行以下操作：</p>
<ol><li>执行$A_{x_i,y_i}\leftarrow -1$，其中$1\le i\le l$。</li>
<li>枚举所有格子。如果存在某个格子$(i ,j)$，满足$i \neq n, A_{i,j} \neq -1, A_{i+1,j} = -1$，执行$A_{i+1,j} \leftarrow A_{i,j}, A_{i,j}\leftarrow -1$。反复执行这个操作直到方格中不再存在这样的格子。</li>
</ol><p>我们还会给你一个参数$F$ ，在所有操作完成后，玩家的<strong>最终得分</strong>的计算方式由$F$决定：如果$F$取值为$0$，那么玩家的最终得分为所有操作的分数总和；如果$F$取值为$1$，那么玩家的最终得分为所有操作的分数总和除$2^d$后向下取整，即
\begin{equation}
\text{最终得分} =
\begin{cases}
\text{所有操作的分数之和}, &amp; F=0\\\\
\left \lfloor \frac{\text{所有操作的分数之和}}{2^d} \right \rfloor, &amp; F=1
\end{cases}
\end{equation}</p>
<p>其中$d$为最终方格中非空白格子的数目。</p>
<p>小Z沉迷于这个有趣的游戏中不能自拔。她想请你帮助, 针对给定的输入参数，给出游戏局面的操作方案。当然，最终得分越大越好。</p>

# 输入格式


<p>所有输入数据game1.in ~ game10.in见数据下载。 输入的第1行包含8个用空格分隔的整数$n, m, K, l_{min}, l_{max}, c_1, c_2, F$，含义同题面描述。 </p>
<p>随后$n$行，每行$m$个整数，表示方格A。数之间用一个空格分隔。</p>
<p>输入文件中不会包含多余的空行，行末不会存在多余的空格。</p>

# 输出格式


<p>针对给定的$10$个输入文件game1.in ~ game10.in，你需要分别提交你的输出文件game1.out ~ game10.out。</p>
<p>输出文件第1行为一个整数$M (0 \leq M \leq K)$，为你的操作次数。</p>
<p>随后, 输出文件还应包含$M$行，每行描述一次操作。对于每一行，最开始的整数$l$表示这次操作中选定路径的长度。接下来有$2l$个数字，分别为$x_1, y_1, x_2, y_2, \dots, x_l, y_l$。</p>
<p>输出文件中不应包含多余的空格和空行。一行的多个整数之间使用一个空格分隔。</p>

# 样例一


<h4>input</h4>
<pre>3 3 100 2 3 1 1 0 
2 1 1 
2 3 3 
4 7 1

</pre>

<h4>output</h4>
<pre>4
2 2 2 3 2
2 3 1 3 2
2 2 1 3 1
3 1 3 2 3 3 3

</pre>

<h4>explanation</h4>
<p>4次消除得到的数与相应的分数分别是：37，得分为2+1=3；41，得分为2+1=3；22，得分为1+2=3；131，得分为3+3=6。总共得分为15。可能存在更优的方案。</p>

# 样例二


<h4>input</h4>
<pre>1 3 100 2 3 1 1 1
2 1 1

</pre>

<h4>output</h4>
<pre>1 
2 1 2 1 3

</pre>

<h4>explanation</h4>
<p>本方案仅一次消除操作。消除的数为11，本次操作得分为2+2=4。由于F=1，最终得分为每次操作得分之和4除以$2^1 = 2$后下取整，为2。若选择消除路径211，则会得到本局面最佳分数4。</p>

# 评分方式


<p>对于每组数据，我们设置了$9$个评分参数$a_{10},a_9, \dots ,a_2$。如果选手的输出不合法，则得零分。否则，在你的方案中，若游戏得分为$w_{user}$，你的分数将会由下表给出：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>得分</th><th>条件</th><th>得分</th><th>条件</th></tr></thead><tbody><tr><td>10</td><td>$w_{user} \geq a_{10}$</td><td>5</td><td>$w_{user} \geq a_5$</td></tr><tr><td>9</td><td>$w_{user} \geq a_9$</td><td>4</td><td>$w_{user} \geq a_4$</td></tr><tr><td>8</td><td>$w_{user} \geq a_8$</td><td>3</td><td>$w_{user} \geq a_3$</td></tr><tr><td>7</td><td>$w_{user} \geq a_7$</td><td>2</td><td>$w_{user} \geq a_2$</td></tr><tr><td>6</td><td>$w_{user} \geq a_6$</td><td>1</td><td>$w_{user} &gt; 0$</td></tr></tbody></table></div>


# 如何测试你的输出


<p>在终端中先切换到该试题的目录下：（windows用户请使用cmd）</p>
<p><code>cd game</code></p>
<p>我们提供checker这个工具来测试你的输出文件是否是可接受的。使用这个工具的方法是，在终端中运行</p>
<p><code>./checker_linux64 &lt;case_no&gt;</code></p>
<p>其中<code>case_no</code>是测试数据的编号。例如</p>
<p><code>./checker_linux64 3</code></p>
<p>将测试game3.out是否可以接受。（windows用户请使用<code>checker_win32 3</code>）（什么你是windows 64位？放心吧可以运行win32应用程序的。）</p>
<p>当然我们有对应的linux 32位版本：<code>checker_linux32</code>。如果linux用户发现无法运行程序，请尝试执行<code>chmod +x checker_linux64</code>或<code>chmod +x checker_linux32</code>后重试。</p>
<p>其它操作系统请安装 <a href="//nodejs.org/">node.js</a> 然后使用 <code>node checker.js &lt;case_no&gt;</code> 运行checker。</p>
<p>在你调用这个程序后，checker将根据你给出的输出文件给出测试的结果。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=4">输入数据及checker下载</a></p>
