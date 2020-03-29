# 题目描述

<p>跳蚤国王和蛐蛐国王在玩一个游戏。</p>
<p>他们在一个 $n$ 行 $m$ 列的网格上排兵布阵。其中的 $c$ 个格子中 $(0 \le c \le nm)$，每个格子有一只蛐蛐，其余的格子中，每个格子有一只跳蚤。</p>
<p>我们称占据的格子有公共边的两只跳蚤是<strong>相邻</strong>的。</p>
<p>我们称两只跳蚤是<strong>连通</strong>的，当且仅当这两只跳蚤<strong>相邻</strong>，或存在另一只跳蚤与这两只跳蚤都<strong>连通</strong>。</p>
<p>现在，蛐蛐国王希望，将某些（0 个，1 个或多个）跳蚤替换成蛐蛐，使得在此之后存在至少两只跳蚤<strong>不连通</strong>。</p>
<p>例如：我们用图<img src="//img.uoj.ac/problem/220/flea.png" alt="flea"/>表示一只跳蚤，用图<img src="//img.uoj.ac/problem/220/cricket.png" alt="cricket"/>表示一只蛐蛐，那么图 1 描述了一个 $n=4, m=4, c=2$ 的情况。</p>
<p>这种情况下蛐蛐国王可以通过将第 2 行第 2 列，和第 3 行第 3 列的两只跳蚤替换为蛐蛐，从而达成他的希望，如图 2 所示。并且，不存在更优的方案，但是可能存在其他替换 2 只跳蚤的方案。</p>
<div class="row">
<div class="col-sm-6">
    <img class="img-responsive center-block" src="//img.uoj.ac/problem/220/img1.png" alt="图1"/><div class="text-center">图1</div>
</div>
<div class="col-sm-6">
    <img class="img-responsive center-block" src="//img.uoj.ac/problem/220/img2.png" alt="图2"/><div class="text-center">图2</div>
</div>
</div>

<p>你需要首先判断蛐蛐国王的希望能否被达成。如果能够达成，你还需要最小化被替换的跳蚤的个数。</p>

# 输入格式


<p>每个输入文件包含多组数据。</p>
<p>输入文件的第一行只有一个整数 $T$，表示数据的组数。保证 $1 \le T \le 20$。</p>
<p>接下来依次输入 $T$ 组数据，每组数据的第一行包含三个整数 $n,~m,~c$。保证$1 \le n,m \le 10^9, 0 \le c \le \min(nm,10^5)$。</p>
<p>接下来 $c$ 行，每行包含两个整数 $x,~y$，表示第 $x$ 行，第 $y$ 列的格子被一个蛐蛐占据（$1 \le x \le n, 1 \le y \le m$）。每一组数据当中，同一个蛐蛐不会被多次描述。</p>
<p>同一行相邻的整数之间由一个空格隔开。</p>

# 输出格式


<p>对于每一组数据依次输出一行答案。</p>
<p>如果这组数据中，蛐蛐国王的希望不能被达成，输出 $−1$。否则，输出被替换的跳蚤的个数的最小值。</p>

# 样例一


<h4>input</h4>
<pre>4
4 4 2
1 1
4 4
2 3 1
1 2
2 2 2
1 1
2 2
1 1 0

</pre>

<h4>output</h4>
<pre>2
1
0
-1

</pre>

<h4>explanation</h4>
<p>第一组数据就是问题描述中的例子。</p>
<p>对于第二组数据，可以将第 2 行第 2 列的一只跳蚤替换为蛐蛐，从而使得存在两只跳蚤<strong>不连通</strong>，并且不存在更优的方案。</p>
<p>对于第三组数据，最初已经存在两只跳蚤<strong>不连通</strong>，故不需要再进行替换。</p>
<p>对于第四组数据，由于最多只有一只跳蚤，所以无论如何替换都不能存在两只跳蚤<strong>不连通</strong>。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>对于全部的测试点，保证 $1 \le T \le 20$。我们记 $\sum c$ 为某个测试点中，其 $T$ 组输入数据的所有 $c$ 的总和。对于所有的测试点，$\sum c \le 10^5$。</p>
<p>对于全部的数据，满足 $1 \le n,m \le 10^9,~0 \le c \le nm,~1 \le x \le n,~1 \le y \le m$。</p>
<p>每个测试点的详细数据范围见下表。表中的 $n,m,c$ 均是对于单个输入数据（而非测试点）而言的，也就是说同一个测试点下的 $T$ 组数据均满足限制条件；而 $\sum c$ 是对于单个测试点而言的。为了方便阅读，“测试点”一列被放到了表格的中间而不是左边。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th colspan="2">$n,m$</th>
    <th>测试点编号</th>
    <th>$c$</th>
  </tr></thead><tbody><tr><td colspan="2">$nm \le 4$</td>
    <td>1</td>
    <td rowspan="7">$c \le nm$</td>
  </tr><tr><td colspan="2">$nm \le 8$</td>
    <td>2</td>
  </tr><tr><td colspan="2">$nm \le 15$</td>
    <td>3</td>
  </tr><tr><td colspan="2">$nm \le 30$</td>
    <td>4</td>
  </tr><tr><td colspan="2">$nm \le 100$</td>
    <td>5</td>
  </tr><tr><td colspan="2">$nm \le 300$</td>
    <td>6</td>
  </tr><tr><td colspan="2">$nm \le 1000$</td>
    <td>7</td>
  </tr><tr><td colspan="2" rowspan="3">$nm \le 20000$</td>
    <td>8</td>
    <td>$c \le 5$</td>
  </tr><tr><td>9</td>
    <td>$c \le 15$</td>
  </tr><tr><td>10</td>
    <td>$c \le 30$</td>
  </tr><tr><td rowspan="5">$n,m \le 20000$</td>
    <td>$nm \le 20000$</td>
    <td>11</td>
    <td rowspan="5">$\sum c \le 20000$</td>
  </tr><tr><td>$nm \le 10^5$</td>
    <td>12</td>
  </tr><tr><td>$nm \le 3 \times 10^5$</td>
    <td>13</td>
  </tr><tr><td>$nm \le 10^6$</td>
    <td>14</td>
  </tr><tr><td>$nm \le 10^9$</td>
    <td>15</td>
  </tr><tr><td colspan="2">$n,m \le 10^5$</td>
    <td>16</td>
    <td>$\sum c \le 10^5$</td>
  </tr><tr><td colspan="2" rowspan="9">$n,m \le 10^9$</td>
    <td>17</td>
    <td>$c=0$</td>
  </tr><tr><td>18</td>
    <td>$c \le 1$</td>
  </tr><tr><td>19</td>
    <td>$c \le 2$</td>
  </tr><tr><td>20</td>
    <td>$c \le 3$</td>
  </tr><tr><td>21</td>
    <td>$c \le 10$</td>
  </tr><tr><td>22</td>
    <td>$c \le 30$</td>
  </tr><tr><td>23</td>
    <td>$c \le 300$</td>
  </tr><tr><td>24</td>
    <td>$\sum c \le 20000$</td>
  </tr><tr><td>25</td>
    <td>$\sum c \le 10^5$</td>
  </tr></tbody></table></div>


<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$1\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=220">样例数据下载</a></p>
