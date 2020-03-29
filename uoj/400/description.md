# 题目描述


# 题目描述


<p> temporaryDO 是一个很菜的 OIer 。在 4 月，他在省队选拔赛的考场上见到了《林克卡特树》一题，其中 $k = 0$ 的部分分是求树 $T$ 上的最长链。可怜的   temporaryDO 并不会做这道题，他在考场上抓猫耳挠猫腮都想不出一点思路。<br/>这时，善良的板板出现在了空中，他的身上发出璀璨却柔和的光芒，荡漾在考场上。‘‘题目并不难。’’ 板板说。那充满磁性的声音，让 temporaryDO 全身充满了力量。</p>
<p>他决定：写一个枚举点对求 LCA 算距离的 $k = 0$ 的 $O(n^2\log\ n)$ 的部分分程序！于是， temporaryDO 选择以 $1$ 为根，建立了求 LCA 的树链剖分结构，然后写了二重 for 循环枚举点对。     </p>
<p>然而，菜菜的 temporaryDO 不小心开小了数组，于是数组越界到了一片神秘的内存区域。但恰好的是，那片内存区域存储的区域恰好是另一棵树 $T′$ 。这样一来，程序并没有 RE ，但他求 $x$ 和 $y$ 的距离的时候，计算的是</p>
<p>$$depth(x) + depth(y) - (depth(LCA(x , y)) + depth′ (LCA′ (x, y)))$$</p>
<p>最后程序会输出每一对点对 $i, j (i \le j)$ 的如上定义的‘‘距离’’ 的最大值。    </p>
<p>temporaryDO 的程序在评测时光荣地爆零了。但他并不服气，他决定花好几天把自己的程序跑出来。请你根据 $T$ 和 $T′$ 帮帮可怜的 temporaryDO 求出他程序的输出。</p>

# 输入格式


<p>第一行包含一个整数 $n$ ，表示树上的节点个数；   </p>
<p>第 $2$ 到第 $n$ 行，每行三个整数 $x , y , v$ ，表示 $T$ 中存在一条从 $x$ 到 $y$ 的边，其长度为 $v$ ；</p>
<p>第 $n + 1$ 到第 $2n - 1 行$ ，每行三个整数 $x , y , v$ ，表示 $T′$ 中存在一条从 $x$ 到 $y$ 的边，其长度为 $v$ 。</p>

# 输出格式


<p>输出一行一个整数，表示 temporaryDO 的程序的输出。</p>

# 样例


<h4>样例输入 1</h4>
<pre><code class="sh_plain">6
1 2 2
1 3 0
2 4 1
2 5 -7
3 6 0
1 2 -1
2 3 -1
2 5 3
2 6 -2
3 4 8</code></pre>
<h4>样例输出 2</h4>
<pre><code class="sh_plain">5</code></pre>
<h4>样例解释 1</h4>
<p>点对 $(3, 4)$ 的距离计算为 $3 + 0 - (0 + (-2)) = 5$ 。</p>
<h4>样例 2</h4>
<p>见附加文件。</p>

# 数据范围与提示


<p>对于所有数据， $n \le 366666 , |v| \le 2017011328$ 。</p>
<p>详细数据范围见下表，表格中的‘‘无’’ 表示无特殊限制。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n\le$</th><th>$v$</th><th>$T$是一条链</th><th>$T&#39;$是一条链</th></tr></thead><tbody><tr><td>1</td><td>36</td><td rowspan="2">$=1$</td><td rowspan="9">否</td><td rowspan="9">否</td></tr><tr><td>2</td><td>366</td></tr><tr><td>3</td><td>1388</td><td rowspan="3">$&gt;0$</td></tr><tr><td>4</td><td>1999</td></tr><tr><td>5</td><td>2666</td></tr><tr><td>6</td><td>5666</td><td rowspan="4">无</td></tr><tr><td>7</td><td>8666</td></tr><tr><td>8</td><td>11111</td></tr><tr><td>9</td><td>12345</td></tr><tr><td>10</td><td rowspan="7">366666</td><td>$&gt;0$</td><td rowspan="4">是</td><td rowspan="2">是</td></tr><tr><td>11</td><td>无</td></tr><tr><td>12~13</td><td>$&gt;0$</td><td rowspan="2">否</td></tr><tr><td>14</td><td>无</td></tr><tr><td>15~16</td><td>$&gt;0$</td><td rowspan="3">否</td><td rowspan="2">是</td></tr><tr><td>17</td><td rowspan="2">无</td></tr><tr><td>18~20</td><td>否</td></tr></tbody></table></div>

<p> $depth(p)$ 和 $depth′(p)$ 分别表示树 $T$ 、 $T′$ 中点 $1$ 到点 $p$ 的距离，这里规定，距离指的是经过的<strong>边</strong>的边权总和，其中 $depth(1) = 0$ 。    </p>
<p> $LCA(x, y)$ 和 $LCA′(x, y)$ 分别表示树 $T$ 、 $T′$ 中点 $x$ 与点 $y$ 的最近公共祖先，即在从 $x$ 到 $y$ 的最短路径上的距离根<strong>经过边数最少</strong>的点。</p>
<hr/><p><strong>时间限制：</strong>$4\mathtt{s}$</p>
<p><strong>空间限制：</strong>$512\mathtt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=400">样例数据下载</a></p>
