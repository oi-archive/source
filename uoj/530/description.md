# 题目描述

<p>蒜斜一旦有作业做不出的时候，就会刷一刷北大算协的公众号。
他最喜欢的一篇推文是 <a href="https://mp.weixin.qq.com/s/6isTIy5_xCvbbA70OuyHCQ">震惊 | 50%程序猿都不会的算法题！</a>。每做出里面的一道题，他就感觉自己的智商提高了一些，作业里的困难也立马迎刃而解。</p>
<p>这一回算协的朋友送给了蒜斜一道非常很有趣的题目。所谓“独IQ++ 不如众IQ++”，蒜斜也把这道题送给了你～</p>

# 题目描述


<p>对于两个长度为 $m$ 的01串 $\alpha,\beta$，定义它们的<em>汉明距离</em> $d(\alpha,\beta) = \sum_{i=1}^m |\alpha_i-\beta_i|$。例如，当 $\alpha=001,\beta=100$ 时，$d(\alpha,\beta) = |0-1|+|0-0|+|1-0| = 2$。</p>
<p>现在给出一个神秘01串 $\pi=110010010000111\cdots$，它的长度是 $n=2^{19}$。我把完整的串放在了下发文件$\texttt{pi.txt}$里。</p>
<p>你需要写一个程序，程序输入一个长度为 $n$ 的01串 $\sigma$ 后，需要输出 $d(\pi,\sigma)$ 的<strong>估计值</strong>：设你输出的<strong>整数</strong>为 $D$，则 $D$ 需要满足不等式 $D\le 2d(\pi,\sigma)\le 4D$。</p>
<p>特别地，你的程序<strong>代码长度不能超过2048B</strong>（超出长度限制的代码无法提交）。</p>

# 输入格式


<p>输入一个长度为 $2^{19}$ 的01串 $\sigma$。</p>

# 输出格式


<p>输出一个<strong>非负整数</strong>，表示你给出的 $d(\pi,\sigma)$ 的估计值。</p>

# 样例一


<p>见下发文件下载。在这个样例中，汉明距离的准确值是 $3$。因此所有被视为正确的输出为 $2,3,4,5,6$。</p>

# 限制与约定


<p><strong>Small Task:</strong> 对于所有 $11000&lt; i \le 2^{19}$ 都满足 $\sigma_i = \pi_i$。包含 $20$ 个数据，只有同时通过这些数据才能得到这一部分的 $35$ 分。</p>
<p><strong>Large Task:</strong> 无特殊限制，同样包含 $20$ 个数据。只有同时通过 Small 和 Large 的共计 $40$ 个数据，才能获得这一部分的 $65$ 分。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=530">下发文件下载</a></p>
