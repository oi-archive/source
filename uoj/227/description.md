# 题目描述

<p>各位观众，各位观众，您现在收看的是第 666 届跳蚤奥运会的比赛现场。在刚刚的环城马拉松比赛中，天才跳高小将“最强跳蚤”靠着“最强跳蚤跳跳跳”和经验丰富的伏特跳蚤国王大战了三天三夜，最后战成 $233:233$ 平。考虑到迟迟不能决出胜者，比赛组委会决定临时更换比赛项目，而被选中的则是在跳蚤大陆流行已久的运动项目——维护数据结构。</p>
<p>维护数据结构可是个大麻烦！首先我来介绍一下数据结构比赛的规则，你有一个长度为 $n$ 的<strong>排列</strong> $a$，比赛分为 $q$ 轮，第 $i$ 轮选手将会得到长度为 $m_i$ 的<strong>排列</strong> $b_i$，对于一个 $x$（$1 \le x \le n - m_i + 1$)，它被称为合法的仅当序列 $a_x, a_{x + 1}, \cdots, a_{x + m_i - 1}$ 与序列 $b$ <strong>相似</strong>，现在你需要统计合法的 $x$ 的数量。</p>
<p>两个序列长度为 $m$ 的序列 $u$ 和 $v$ 被称为<strong>相似</strong>的，当且仅当对于任意 $1 \le i &lt; j \le n$，要么 $u_i &lt; u_j, v_i &lt; v_j$，要么 $u_i &gt; u_j, v_i &gt; v_j$。</p>
<p>你看，现在所有的序列都已经给出了，选手们已经开始着手计算了。这看上去将会是一场非常激烈的比赛啊。</p>
<p>观众朋友们也可以和选手同台竞技，最早给出答案的观众可以获得小高铁一列哦。</p>

# 输入格式


<p>第一行一个只可能是 $0$ 或者 $1$ 的自然数 $\mathrm{type}$，含义在下面解释。</p>
<p>接下来一行一个正整数 $n, q$。</p>
<p>接下来一行 $n$ 个正整数，表示排列 $a$。</p>
<p>接下来 $q$ 行，其中第 $i$ 行的第一个整数为 $m_i$，接下来 $m_i$ 个正整数，表示排列 $b_i$。</p>
<p><strong>注意给出的 $b_i$ 可能是经过加密的，如果 $\mathrm{type} = 1$，那么假设上一个询问的答案为 $\mathrm{ans}$（若为第一个询问则 $\mathrm{ans} = 0$），则应该进行变换 $c_{i, (j + \mathrm{ans} - 1) \bmod m_i + 1} = b_{i, j}$ 得到 $c_i$ 并将 $c_i$ 作为这次的询问序列。</strong></p>

# 输出格式


<p>输出 $q$ 行，每行一个整数表示每个询问对应的合法的 $x$ 的数量。</p>

# 样例一


<h4>input</h4>
<pre>1
5 3
1 5 2 4 3
1 1
2 2 1
3 2 1 3

</pre>

<h4>output</h4>
<pre>5
2
2

</pre>

<h4>explanation</h4>
<p>实际上的三个询问序列分别是：
\begin{equation}
\{1\}, \{1, 2\}, \{1, 3, 2\}
\end{equation}</p>
<p>对于第一个询问，由于长度为 $1$，所有长度为 $1$ 的区间都和询问序列相似。</p>
<p>对于后两个询问，$x$ 可以为 $1, 3$。</p>

# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$q$</th>
<th>$\sum{m_i}$</th>
<th>限制与约定</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="4">$\le 2000$</td><td rowspan="6">$\le 50$</td><td rowspan="4">$\le 10000$</td><td rowspan="12">$\mathrm{type} = 0$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="8">$\le 100000$</td><td rowspan="8">$\le 500000$</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="14">$\le 500000$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr><tr><td>11</td></tr><tr><td>12</td></tr><tr><td>13</td><td rowspan="8">$\le 100000$</td><td rowspan="8">$\le 500000$</td><td rowspan="4">$m_i \le 25$</td></tr><tr><td>14</td></tr><tr><td>15</td></tr><tr><td>16</td></tr><tr><td>17</td><td rowspan="4">无</td>
</tr><tr><td>18</td></tr><tr><td>19</td></tr><tr><td>20</td></tr></tbody></table></div>

<p>在所有数据中，满足 $1 \le n \le 100000, \sum{m_i} \le 500000, 1 \le m_i \le n$, $a$ 和 $b_i$ 均为排列。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$1\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=227">样例数据下载</a></p>
