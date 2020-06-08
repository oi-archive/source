# 题目描述

<p>19 世纪初，统治者下令在俯瞰美丽河景的高原上建造一座宫殿。这块高原被看做是一个由正方形单元格组成的 $n \times m$ 网格。网格的行从 $0$ 到 $n-1$ 编号，列从 $0$ 到 $m-1$ 编号。第 $i$ 行第 $j$ 列 $(0 \le i \le n-1,0 \le j \le m-1) $的单元格记为单元格 $(i,j)$ 。每个单元格 $(i,j)$ 有特定的海拔高度，记为 $a_{i,j}$。</p>
<p>统治者指示他的建筑师选择一个矩形区域来建造宫殿。该区域不能包含网格边界（第 $0$ 行，第 $n-1$ 行，第 $0$ 列，以及第 $m-1$ 列）上的任何单元格。为此，建筑师应选出四个整数 $r1,r2,c1$ 和 $c2 (1 \le r1 \le r2 \le n-2,1 \le c1 \le c2 \le m-2)$ ，对应于包括所有满足 $r1 \le i \le r2$ 且 $c1 \le i \le c2$ 的单元格 $(i,j)$ 的矩形区域。</p>
<p>此外，一个区域被认为是合法的，当且仅当对于该区域中的每个单元格 $(i,j)$，以下条件成立：对于与该区域相邻的、位于第 $i-1$ 行的两个单元格（单元格 $(i,c1-1)$ 和 $(i,c2+1)$)，以及与该区域相邻的位于第 $j$ 列的两个单元格（单元格 $(r1-1,j)$ 和 $(r2+1,j)$），单元格 $(i,j)$ 的海拔高度必须严格小于这四个单元格的海拔高度。</p>
<p>你的任务是帮助建筑师统计可建宫殿的合法区域的数量（也就是所对应区域为合法的 $r1,r2,r1$ 和 $c2$ 的数量）。</p>

# 输入格式


<p>第一行两个整数 $n,m$。</p>
<p>接下来 $n$ 行，每行 $m$ 个整数，第 $i-1$ 行的第 $j-1$ 个整数表示 $a_{i,j}$。</p>

# 输出格式


<p>一行一个数字表示答案。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">6 5
4 8 7 5 6
7 4 10 3 5
9 7 20 14 2
9 14 7 3 6
5 7 5 2 7
4 5 13 5 6</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">6</code></pre>
<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/534/rect.png" alt="样例一示意图"/></p>
<p>一共有 $6$ 个合法区域，分别为：</p>
<ul><li>$r1=r2=1,c1=c2=1$</li>
<li>$r1=1,r2=2,c1=c2=1$</li>
<li>$r1=r2=1,c1=c2=3$</li>
<li>$r1=r2=1,c1=2,c2=3$</li>
<li>$r1=r2=4,c1=c2=3$</li>
<li>$r1=3,r2=4,c1=c2=1$</li>
</ul><p>例如，$r1=1,r2=2,c1=c2=1$ 对应一个合法区域，原因是以下两个条件都成立：</p>
<p> $a_{1,1}=4$ 严格小于 $a_{0,1}=8$，$a_{3,1}=14$，$a_{1,0}=7$和 $a_{1,2}=10$。
 $a_{2,1}=7$ 严格小于 $a_{0,1}=8$，$a_{3,1}=14$，$a_{2,0}=9$和 $a_{2,2}=20$。</p>

# 数据范围


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试包编号</th><th>限制与约定</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$n,m \le 30$</td><td>8</td></tr><tr><td>$2$</td><td>$n,m \le 80$</td><td>7</td></tr><tr><td>$3$</td><td>$n,m \le 200$</td><td>12</td></tr><tr><td>$4$</td><td>$n,m \le 700$</td><td>22</td></tr><tr><td>$5$</td><td>$n \le 3$</td><td>10</td></tr><tr><td>$6$</td><td>$a_{i,j} \le 1$</td><td>13</td></tr><tr><td>$7$</td><td>无特殊限制</td><td>28</td></tr></tbody></table></div>

<p>对于所有测试数据，满足$1 \le n,m \le 2500,1 \le a_{i,j} \le 7000000$。</p>
<p><strong>时间限制:</strong> $4\texttt{s}$</p>
<p><strong>空间限制:</strong> $1\texttt{GB}$</p>
<p><strong>时限有微调，请选手注意一下自己的常数问题。</strong></p>
