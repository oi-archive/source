# 题目描述

<p>小P最近迷上了石头剪刀布，他观看了一场沙雕石头剪刀布大赛</p>
<p>比赛共有 $2^n$ 个沙雕参加， 分为 $n$ 轮，在每轮中，第 $0$ 位选手和第 $1$ 位选手对战，胜者作为新的第 $0$ 位选手，第 $2$ 位和第 $3$ 位对战，胜者作为新的第 $1$ 位选手，以此类推。</p>
<p>小P得知，每个沙雕都有一种固定的偏爱决策，每个沙雕在每一次对战中都只会使用他的偏爱决策。</p>
<p>如果一次对战的双方的偏爱决策相同，那么这次对战就永远不会结束，那么作为观众会十分无聊。</p>
<p>现在，小P知道了偏爱每种决策的沙雕数目，他想知道一种能够决出最终胜负的初始的次序。</p>
<p>若有多种可能次序，我们设<strong>字典序最小</strong>的为答案。</p>
<p>因为答案可能很长，你只需要输出答案的$hash$值以及第$l$到$r$位。</p>
<p>$$hash=\sum_{i=0}^{2^n-1}S_i \times 233^i \bmod998244353$$</p>
<p>($S_i$表示初始标号为$i$的人的偏好决策对应的大写字母 ASCII 码)</p>

# 输入格式


<p>第一行两个整数$n, op$，表示数据规模和数据类型。</p>
<p>第二行一个大整数，表示偏爱决策为石头$R$的人数。</p>
<p>第三行一个大整数，表示偏爱决策为剪刀$S$的人数。</p>
<p>第四行一个大整数，表示偏爱决策为布$P$的人数。</p>
<p>若$op\neq 1$，第五，六行，两个$n$位二进制数$l,r$，表示要求你输出的范围。</p>

# 输出格式


<p>若不存在合法初始序列，输出<code>-1</code>，否则：</p>
<p>若$op\neq 2$，输出一个整数，表示最优序列$hash$值。</p>
<p>若$op\neq 1$，输出一个由$&#34;R,S,P&#34;$构成的字符串，表示最优序列的第$l$到$r$位。</p>

# 样例一


<h4>input</h4>
<pre><code>4 3
4
4
8
0000
1111</code></pre>
<h4>output</h4>
<pre><code>-1</code></pre>

# 样例二


<h4>input</h4>
<pre><code>1 1
1
1
0</code></pre>
<h4>output</h4>
<pre><code>19421</code></pre>

# 样例三


<h4>input</h4>
<pre><code>2 2
1
2
1
01
10</code></pre>
<h4>output</h4>
<pre><code>SR</code></pre>

# 样例四


<h4>input</h4>
<pre><code>3 3
2
3
3
011
110</code></pre>
<h4>output</h4>
<pre><code>879001374
SPSR</code></pre>

# 样例五至样例六


<p>见样例数据下载。</p>

# 限制与约定


<p>本题采用捆绑测试。</p>
<p>对于所有子任务均满足 $1\ \leq\ n\ \leq\ 300000,\ 0\leq\ r-l\leq\ 300000 ,\ R+S+P=2^n$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th><th>子任务分值</th><th>$n$的范围</th><th>$r-l$的范围</th><th>数据类型</th></tr></thead><tbody><tr><td>$1$</td><td>3</td><td>$4$</td><td>$10$</td><td>$3$</td></tr><tr><td>$2$</td><td>19</td><td>$20$</td><td>$1000$</td><td>$3$</td></tr><tr><td>$3$</td><td>11</td><td>$2000$</td><td>$10000$</td><td>$1$</td></tr><tr><td>$4$</td><td>8</td><td>$2000$</td><td>$10000$</td><td>$2$</td></tr><tr><td>$5$</td><td>14</td><td>$2000$</td><td>$10000$</td><td>$3$</td></tr><tr><td>$6$</td><td>15</td><td>$300000$</td><td>$300000$</td><td>$1$</td></tr><tr><td>$7$</td><td>10</td><td>$300000$</td><td>$300000$</td><td>$2$</td></tr><tr><td>$8$</td><td>20</td><td>$300000$</td><td>$300000$</td><td>$3$</td></tr></tbody></table></div>

<p><strong>时间限制：$\texttt{1s}$</strong></p>
<p><strong>空间限制：$\texttt{512MB}$</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=442">样例数据下载</a></p>
