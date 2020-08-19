# 题目描述

<p>在很久以前的黄金时代，澳大利亚的土地是矩形的，它可以被划分成 $R$ 行 $C$ 列的网格状， 行的编号从北到南依次为 $1$ 到 $R$，列的编号从西到东依次为 $1$ 到 $C$，$(r,c)$ 表示第 $r$ 行第 $c$ 列的土地。一天，伟大的彩虹蛇从 $(s_r, s_c)$ 出发在澳大利亚的土地上移动，彩虹蛇连续进行了 $M$ 次移动，每次它会向正北 (N)、正南(S)、正东(E)或正西(W)方向移动一格，其经过的所 有的格子(包括起点和终点)都会变成河流。
数百万年之后，你想购买一块矩形区域纪念伟大的彩虹蛇。你想给所购买矩形区域内每一块<strong>不是河流</strong>的格子都染上颜色，要求相邻的格子颜色<strong>必须相同</strong>，两个格子相邻当且仅当两个格子有一条<strong>公共边</strong>，你所购买区域之外的格子无须染色。
现在给出彩虹蛇 $M$ 次移动的方向，你有 $Q$ 个购买矩形区域的方案，问每个方案<strong>最多</strong>能够将土地染上多少种不同的颜色。</p>

# 实现细节


<p>你需要包含头文件 rainbow.h。</p>
<p>你需要实现函数 init 和 colours:</p>
<ul><li><p>init(R, C, sr, sc, M, S) --- 该函数会在开始时调用并且只会调用一次</p>
<ul><li>R 和 C: 表示网格的行数和列数</li>
<li>sr 和 sc: 彩虹蛇的起点坐标</li>
<li>M: 彩虹蛇移动的步数</li>
<li>S: 一个长度为 M 的字符串, S[i] 是N、S、E、W之一, 分别表示彩虹蛇的第 $i$ 次移动是向正北、正南、正东、正西移动一格，$0 \leq i\leq M - 1$ 。保证彩虹蛇不会移动到网格外面。</li>
</ul></li>
<li><p>colours(ar, ac, br, bc) --- 在调用init一次之后, 该函数会被总共调用 $Q$ 次</p>
<ul><li>$(a_r, a_c)$ 表示你所购买矩形的西北角的格子的坐标，$(b_r, b_c)$ 表示你所购买矩形的东南角的格子的坐标，返回一个整数表示在这种购买方案下最多能够将土地染上多少种不同的颜色</li>
<li>$1 \leq a_r \leq b_r \leq R$, $1 \leq a_c \leq b_c \leq C$</li>
</ul></li>
</ul><p>请参考提供的模板文件以获取更多的细节。</p>

# 样例测试程序


<p>样例测试程序按照以下格式输入:</p>
<ul><li>第1行:四个整数 $R$, $C$, $M$ 和 $Q$;</li>
<li>第2行:两个整数 $s_r$ 和 $s_c$;</li>
<li>第3行:一个包含 $M$ 个字符的字符串 $S$, 每个字符是N、S、E、W之一 (如果 $M = 0$ 则此行应留空);</li>
<li>第4行到 $Q+3$ 行:每行四个整数$a_r$, $a_c$, $b_r$ 和 $b_c$。</li>
</ul>
# 样例和解释


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>函数调用</th>
<th>返回值</th>
<th>解释</th>
</tr></thead><tbody><tr><td>init(6, 4, 3, 3, 9, &#34;NWESSWEWS&#34;)</td><td></td><td>提供了网格的大小，彩虹蛇的起点和它的移动路径。</td>
</tr><tr><td>colours(2, 3, 2, 3)</td><td>0</td><td>只有 $(2, 3)$ 被矩形包含,但 $(2, 3)$ 是河，所以没有格子需要染色，颜色数为 $0$ 。</td>
</tr><tr><td>colours(3, 2, 4, 4)</td><td>2</td><td>河将矩形区域分成了两部分:一部分包含 $(3, 2)$，另一部分包含 $(3,4)$ 和 $(4,4)$ ;因此最多染 $2$ 种不同的颜色。</td>
</tr><tr><td>colours(5, 3, 6, 4)</td><td>1</td><td>矩形区域内不包含河，所有格点都是联通的，所以你最多染 $1$ 种 颜色。</td>
</tr><tr><td>colours(1, 2, 5, 3)</td><td>3</td><td>河将矩形区域分成了三部分:第一部分包含 $(1, 2)$ 和 $(1, 3)$ ，第二 部分包含 $(3, 2)$，第三部分包含 $(5, 3)$，因此最多可以染$3$种不同的颜色。</td>
</tr></tbody></table></div>

<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/303/coturh.png" alt="例子"/></p>
<p>注:上图中的蓝色格子表示河流</p>

# 样例输入


<pre>6 4 9 4 
3 3 
NWESSWEWS 
2 3 2 3 
3 2 4 4 
5 3 6 4 
1 2 5 3
</pre>


# 样例输出


<pre>0
2
1
3
</pre>


# 子任务


<p>对于全部任务, $0 \leq M \leq 100000$, $R, C, Q \geq 1$。</p>
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分数</th><th>R</th><th>C</th><th>Q</th></tr></thead><tbody><tr><td>1</td><td>11</td><td> $R \leq 50$ </td><td> $C \leq 50$ </td><td> $Q \leq 1000$ </td></tr><tr><td>2</td><td>12</td><td> $R = 2$ </td><td> $C \leq 200000$ </td><td> $Q \leq 100000$ </td></tr><tr><td>3</td><td>24</td><td> $R = 200000$ </td><td> $C \leq 200000$ </td><td> $Q = 1$ </td></tr><tr><td>4</td><td>27</td><td> $R = 1000$ </td><td> $C \leq 1000$ </td><td> $Q = 100000$ </td></tr><tr><td>5</td><td>26</td><td> $R = 200000$ </td><td> $C \leq 200000$ </td><td> $Q = 100000$ </td></tr></tbody></table><p>在本题的 hack 中，你可以提交与样例交互库相同格式的输入，该输入需要满足 $ 1 \le R, C \le 200000, 1 \le Q \le 100000, 0 \le M \le 100000 $。</p>
<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=303">样例及测评库下载</a></p>
