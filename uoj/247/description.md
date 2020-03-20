# 题目描述

<p>公元 3000 年，科学家发现了一个神秘的太空站。经过几个月的研究之后，他们作出了一张电子地图并发送了一个机器人过去进行进一步调查。</p>
<p>这张地图由 $n \times m$ 的方格组成，每个格子上为空或有障碍物，每次可以从东西南北四个方向中选择一个方向，发送指令让机器人向该方向移动一个格子。然而，这个空间站里没有光，所以机器人只能在黑暗中乱走乱撞。当机器人试图移动到障碍物上时此次移动便会失败，可据此推断出前方是否有障碍物。</p>
<p>这张地图还有一个特别的地方：所有的障碍物都是四连通的（通过东西南北四个方向连通），并且所有空格子被障碍物包围。所有的空格子之间均可互相到达，并且该空间站不存在通道。不存在通道的意思是，对于每个空格子，南北两个相邻格子中至多只有一个障碍物，东西两个相邻格子中至多只有一个障碍物。</p>
<p>我们将所有的空格子从北到南、从西到东依次编号为 $1, 2, 3, \dots$，如下图所示：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/247/a.png" alt="图1"/></p>
<p>有 $k$ 个传送控制器，每个控制器连接了两个不同的空格子，称为传送格。每个传送格仅可最多与一个传送控制器连接，并且传送格的 $8$ 个相邻格子不可能是另一个传送格或障碍物。</p>
<p>如果两个传送格由同一个控制器连接，那么机器人一旦从某个方向走到了其中一个格子，它就会立刻被传送到另一个格子上，并且以同样的方向移动到相邻格子上。显然这个过程中机器人不会再次被传送。</p>
<p>现在，科学家已经将机器人发送到某一个特定的格子上。由于一些技术上的原因，起始的格子总是与一个障碍物相邻。</p>
<p>例如在上图中，机器人可能会被发送到 $12$ 号格子。如果没有传送控制器，那么向机器人发送指令 <samp>EN</samp> 后，机器人最后会停在 $8$ 号格子。但再向机器人发送 <samp>N</samp> 指令时，机器人将被障碍物堵住。如果 $10$ 号格子和 $13$ 号格子之间有一个传送控制器，那么机器人就可以成功地执行 <samp>ENN</samp> 指令，实际的移动路线为 $12 \rightarrow (13 \rightarrow 10 \rightarrow) 11 \rightarrow 5 \rightarrow 1$。（<samp>E</samp>、<samp>W</samp>、<samp>S</samp>、<samp>N</samp> 分别代表东西南北四个方向）</p>
<p>你的任务是发送指令控制这台机器人，在合理的移动指令个数内发现所有传送控制器的位置。</p>

# 交互格式


<p>本题是一道交互式试题，你的程序需要和交互程序通过标准输入输出进行交互。每次向标准输出打印了一行后，<strong>请立即刷新缓冲区</strong>。</p>
<p>第一行三个正整数 $n, m, k$。</p>
<p>接下来 $n$ 行，每行 $m$ 个字符。其中 “<samp>.</samp>” 表示空格子，“<samp>*</samp>” 表示障碍物，“<samp>S</samp>” 表示起始位置。</p>
<p>选手程序需要输出若干 MoveRobot 命令进行移动并读取交互程序返回的移动结果，最后输出恰好 $k$ 个 Answer 命令提交答案。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>命令</th>
<th>描述</th>
</tr></thead><tbody><tr><td><samp>MoveRobot $D$</samp></td><td>试图向方向 $D$ 移动，若成功返回 $1$，若失败返回 $0$。</td></tr><tr><td><samp>Answer $\mathrm{pos}_1$ $\mathrm{pos}_2$</samp></td><td>告诉交互程序你找到了一个连接 $\mathrm{pos}_1$ 和 $\mathrm{pos}_2$ 的传送控制器，该命令不返回任何信息。</td></tr></tbody></table></div>

<p>注意每个传送控制器应被输出恰好一次，但可以按任意顺序。</p>

# 样例一


<div class="table-responsive">
<table class="table table-bordered table-condensed table-with-pre"><thead><tr><th>交互程序输出</th>
<th>选手程序输出</th>
</tr></thead><tbody><tr><td><pre>7 8 1
********
*****..*
***....*
*.....**
*S.....*
*......*
********</pre></td><td></td></tr><tr><td></td><td><pre>MoveRobot E</pre></td></tr><tr><td><pre>1</pre></td><td></td></tr><tr><td></td><td><pre>MoveRobot N</pre></td></tr><tr><td><pre>1</pre></td><td></td></tr><tr><td></td><td><pre>MoveRobot N</pre></td></tr><tr><td><pre>1</pre></td><td></td></tr><tr><td></td><td><pre>MoveRobot W</pre></td></tr><tr><td><pre>0</pre></td><td></td></tr><tr><td></td><td><pre>MoveRobot N</pre></td></tr><tr><td><pre>0</pre></td><td></td></tr><tr><td></td><td><pre>MoveRobot E</pre></td></tr><tr><td><pre>1</pre></td><td></td></tr><tr><td></td><td><pre>MoveRobot E</pre></td></tr><tr><td><pre>0</pre></td><td></td></tr><tr><td></td><td><pre>Answer 10 13</pre></td></tr></tbody></table></div>


# 限制与约定


<p>保证 $6 \le n,m \le 15$，$1 \le k \le 5$。</p>
<p>MoveRobot 命令的调用次数不能超过 $32767$。</p>
<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$256\texttt{MB}$</p>

# 来源


<p>Uva Online Judge，题目作者刘汝佳。</p>

# 下载


<p>没有什么可下载的。</p>
