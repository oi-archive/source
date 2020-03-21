# 题目描述

<p>小 E 同学非常喜欢书法，他听说 NOI2013 已经开始了，想题一幅 “NOI” 的字送给大家。</p>
<p>小 E 有一张非常神奇的纸，纸可以用一个 $n$ 行 $m$ 列的二维方格矩阵来表示，为了描述方便，我们定义矩阵左下角方格坐标为 $(1,1)$，右上角方格坐标为 $(m, n)$。</p>
<p>矩阵的每个方格有一个整数的幸运值。在格子上面写字可以增加大家的幸运度，幸运度的大小恰好是所有被笔写到的方格的幸运值之和。现在你要在上面写上 “<samp>N</samp>”, “<samp>O</samp>”, “<samp>I</samp>” 三个字母。</p>
<p>下面给出 $3$ 个书法字的定义:</p>
<ol><li>“<samp>N</samp>” 由若干 （$\geq 3$） 个边平行于坐标轴的矩形组成，设由 $K$ 个矩形组成（标号 $1 \sim K$），第 $i$ 个矩形的左下角方格坐标设为 $(L_i, B_i)$，右上角坐标设为 $(R_i, T_i)$，要求满足：<ul><li>$L_i \leq R_i, B_i \leq T_i$</li>
<li>对任意 $1 &lt; i \leq K$，有 $L_i = R_{i−1} + 1$</li>
<li>对任意 $3 \leq i &lt; K$，有 $B_{i−1} − 1 \leq T_i \leq T_{i−1}$，$B_i \leq B_{i−1}$</li>
<li>$B_2 &gt; B_1$，$T_2 = T_1$，$B_{K−1} = B_K$，$T_{K−1} &lt; T_K$</li>
</ul></li>
<li>“<samp>O</samp>” 由一个大矩形 $A$，挖去一个小矩形 $B$ 得到，这两个矩形的边都平行于坐标轴。设大矩形 $A$ 左下角的方格坐标为 $(u, v)$，长为 $W$，宽为 $H$，则小矩形 $B$ 满足左下角方格坐标为 $(u + 1, v + 1)$，长 $W − 2$，宽 $H − 2$。要求满足：<ul><li>$W \geq 3, H \geq 3$</li>
<li>$u &gt; R_K + 1$</li>
</ul></li>
<li>“<samp>I</samp>” 为 $3$ 个边平行于坐标轴的从下到上的实心矩形组成，从下到上依次标号为 $1,2,3$，第 $i$ 个矩形的左下角格子坐标设为 $(P_i, Q_i)$，右上角格子坐标设为 $(G_i, H_i)$，要求满足：<ul><li>$P_i \leq G_i, Q i \leq H_i$</li>
<li>$P_1 = P_3 &gt; u + W$，$G_1 = G_3$</li>
<li>$Q_1 = H_1 = Q_2 − 1$，$H_2 + 1 = Q_3 = H_3$</li>
<li>$P_1 &lt; P_2 \leq G_2 &lt; G_1$</li>
</ul></li>
</ol><p>下图是一个 “<samp>N</samp>”，“<samp>O</samp>”，“<samp>I</samp>” 的例子。</p>
<p><img src="//img.uoj.ac/problem/125/a.png" alt="NOI的例子" class="img-responsive center-block"/></p>
<p>另外，所有画的图形均不允许超过纸张的边界。现在小 E 想要知道，他能画出的最大幸运度是多少。</p>

# 输入格式


<p>第一行包含两个正整数 $n$ 和 $m$，分别表示矩阵的行数和列数。</p>
<p>接下来 $n$ 行，每行有 $m$ 个整数，第 $i + 1$ 行的第 $j$ 个数表示格子 $(j, n − i + 1)$ 的幸运值。</p>

# 输出格式


<p>输出一个整数 $T$，表示小 E 能够获得的最大幸运度。</p>

# 样例一


<h4>input</h4>
<pre>3 13
1 1 -1 -1 1 -1 1 1 1 -1 1 1 1
1 -1 1 -1 1 -1 1 -1 1 -1 -1 1 -1
1 -1 -1 1 1 -1 1 1 1 -1 1 1 1

</pre>

<h4>output</h4>
<pre>24

</pre>


# 样例二


<h4>input</h4>
<pre>3 13
-1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1
-1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1
-1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1 -1

</pre>

<h4>output</h4>
<pre>-20

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>幸运值范围</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="4">$=3$</td><td rowspan="4">$=12$</td><td rowspan="4">$[-50, 50]$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="4">$\leq 10$</td><td rowspan="4">$\leq 20$</td><td rowspan="4">$[-50, 50]$</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="2">$\leq 150$</td><td rowspan="2">$\leq 500$</td><td rowspan="2">$= 1$</td></tr><tr><td>10</td></tr><tr><td>11</td><td rowspan="4">$\leq 80$</td><td rowspan="4">$\leq 80$</td><td rowspan="4">$[-200, 200]$</td></tr><tr><td>12</td></tr><tr><td>13</td></tr><tr><td>14</td></tr><tr><td>15</td><td rowspan="6">$\leq 150$</td><td rowspan="6">$\leq 500$</td><td rowspan="6">$[-200, 200]$</td></tr><tr><td>16</td></tr><tr><td>17</td></tr><tr><td>18</td></tr><tr><td>19</td></tr><tr><td>20</td></tr></tbody></table></div>

<p>对于所有的测试数据，保证 $n \geq 3, m \geq 12$。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=125">样例数据下载</a></p>
