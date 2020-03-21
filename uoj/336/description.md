# 题目描述


# 题目描述


<p>曾经有一款流行的游戏，叫做 <em>Infinity Loop</em>，先来简单的介绍一下这个游戏：</p>
<p>游戏在一个 $n \times m$ 的网格状棋盘上进行，其中有些小方格中会有水管，水管可能在方格某些方向的边界的中点有接口，所有水管的粗细都相同，所以如果两个相邻方格的公共边界的中点都有接头，那么可以看作这两个接头互相连接。水管有以下 15 种形状：</p>
<p><img src="//img.uoj.ac/problem/336/pipe1.webp" alt="pattern1.webp" height="200" width="200"/><img src="//img.uoj.ac/problem/336/pipe2.webp" alt="pattern2.webp" height="200" width="200"/></p>
<p>游戏开始时，棋盘中水管可能存在漏水的地方。</p>
<p>形式化地：如果存在某个接头，没有和其它接头相连接，那么它就是一个漏水的地方。</p>
<p>玩家可以进行一种操作：选定一个含有<strong>非直线型</strong>水管的方格，将其中的水管绕方格中心顺时针或逆时针旋转90度。</p>
<p>直线型水管是指左图里中间一行的两种水管。</p>
<p>现给出一个初始局面，请问最少进行多少次操作可以使棋盘上不存在漏水的地方。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行两个正整数 $n，m$，代表网格的大小。</p>
<p>接下来 $n$ 行每行 $m$ 个数，每个数是 $[0,15]$ 中的一个，你可以将其看作一个 $4$ 位的二进制数，从低到高每一位分别代表初始局面中这个格子上、右、下、左方向上是否有水管接头。</p>
<p>特别地，如果这个数是 $0$ ，则意味着这个位置没有水管。</p>
<p>比如 $3(0011_{(2)})$ 代表上和右有接头，也就是一个L型，而 $12(1100_{(2)})$ 代表下和左有接头，也就是将L型旋转180度。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出共一行，表示最少操作次数。如果无法达成目标，输出-1.</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">2 3
3 14 12
3 11 12</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">2</code></pre>
<h4>explanation</h4>
<p>样例1棋盘如下</p>
<p><img src="//img.uoj.ac/problem/336/sample.jpg" alt="sample.jpg" height="200"/></p>
<p>旋转方法很显然，先将左上角虚线方格内的水管顺时针转90度</p>
<p><img src="//img.uoj.ac/problem/336/process.webp" alt="process.webp" height="200"/></p>
<p>然后右下角虚线方格内的水管顺时针旋转90度，这样就使得水管封闭了</p>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">3 2
1 8
5 10
2 4</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">-1</code></pre>
<h4>explanation</h4>
<p>样例2为题目描述中的第一张图片，无法达成目标。</p>

# 样例三


<h4>input</h4>
<pre><code class="sh_plain">3 3
9 11 3
13 15 7
12 14 6</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">16</code></pre>
<h4>explantion</h4>
<p>样例3为题目描述中的第二张图片，将除了中心方格以外的每个方格内的水管都转180度即可。</p>

# 限制与约定


<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n+m$的范围</th><th rowspan="1">特殊约定</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="2">$nm\le 16$</td><td rowspan="2">无特殊要求</td></tr><tr><td rowspan="1">2</td></tr><tr><td rowspan="1">3</td><td rowspan="18">$nm\le 2000$</td><td rowspan="6">$\min(n,m)\le 15$</td></tr><tr><td rowspan="1">4</td></tr><tr><td rowspan="1">5</td></tr><tr><td rowspan="1">6</td></tr><tr><td rowspan="1">7</td></tr><tr><td rowspan="1">8</td></tr><tr><td rowspan="1">9</td><td rowspan="12">无特殊要求</td></tr><tr><td rowspan="1">10</td></tr><tr><td rowspan="1">11</td></tr><tr><td rowspan="1">12</td></tr><tr><td rowspan="1">13</td></tr><tr><td rowspan="1">14</td></tr><tr><td rowspan="1">15</td></tr><tr><td rowspan="1">16</td></tr><tr><td rowspan="1">17</td></tr><tr><td rowspan="1">18</td></tr><tr><td rowspan="1">19</td></tr><tr><td rowspan="1">20</td></tr></tbody></table><p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=336">样例数据下载</a></p>
