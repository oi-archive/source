# 题目描述

<p>巴库有 $n$ 处景点。从 $0$ 到 $n-1$ 编号。另外还有 $m$ 条双向道路，从 $0$ 到 $m-1$ 编号。每条道路连接两个不同的景点。经由这些道路，可以在任意两处景点之间往来。</p>
<p>Fatima 打算在三天之内参观完所有这些景点。她已经决定要在第一天参观 $a$ 处景点，第二天参观 $b$ 处景点，第三天参观 $c$ 处景点。因此，她要把这 $n$ 处景点划分为三个集合 $A,B$ 和 $C$，其规模分别为 $a,b$ 和 $c$ 。每处景点恰好属于其中一个集合，因此有 $a+b+c=n$ 。</p>
<p>Fatima 想要找到这样的集合划分 $A,B$ 和 $C$，使得这三个集合中的至少两个是连通的。一个景点集合 $S$ 被称为是连通的，如果能够经由这些道路在 $S$ 中的任意两处景点之间往来，且不需要经过不在 $S$ 中的景点。如果满足上述要求，则景点的一个划分 $A$ 和 $B$ 被称为是合法的。</p>
<p>请帮助 Fatima 找到一个合法的景点划分（给定 $a,b$ 和 $c$），或者判定合法的划分不存在。如果存在多个合法的划分，你可以给出其中的任意一个。</p>

# 输入格式


<p>第一行两个整数 $n,m$，分别表示景点数与道路数；</p>
<p>第二行三个整数 $a,b,c$，表示集合 $A,B$ 和 $C$ 的大小；</p>
<p>接下来 $m$ 行，第 $i$ 行两个整数 $x_{i},y_i$，表示编号为 $x_i$ 的景点和编号为 $y_i$ 的景点之间有一条双向道路。</p>

# 输出格式


<p>输出一行 $n$ 个整数，每两个整数之间用一个空格隔开。</p>
<p>如果不存在合法的划分，输出的 $i$ 个整数均为 $0$。否则，对于输出的第 $i$ 个整数 ，应为 $1,2$ 或 $3$ 中的一个，表示景点 $i-1$ 被归到集合 $A,B$ 或 $C$。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">9 10
4 2 3
0 1
0 2
0 3
0 4
0 6
0 8
1 7
3 7
4 5
5 6</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">1 1 3 1 2 2 3 1 3</code></pre>
<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/535/attr1.png" alt="样例一示意图"/></p>
<p>一个可能的正确解为 $[1,1,3,1,2,2,3,1,3]$。这个解刻画了这样的划分：$A={0,1,3,7},B={4,5}$ 和 $C={2,6,8}$。集合 $A$ 和 $B$ 是连通的。</p>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">6 5
2 2 2
0 1
0 2
0 3
0 4
0 5</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">0 0 0 0 0 0</code></pre>
<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/535/attr2.png" alt="样例二示意图"/></p>
<p>合法的划分不存在。因此，唯一的正确答案是 $[0,0,0,0,0,0]$。</p>

# 数据范围


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试包编号</th><th>限制与约定</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>每处景点至多可做两条道路的端点</td><td>7</td></tr><tr><td>$2$</td><td>$a=1$</td><td>11</td></tr><tr><td>$3$</td><td>$m=n-1$</td><td>22</td></tr><tr><td>$4$</td><td>$n \le 2500,m \le 5000$</td><td>24</td></tr><tr><td>$5$</td><td>无特殊约定</td><td>36</td></tr></tbody></table></div>

<p>对于所有测试数据，满足$3 \le n \le 100000,2 \le m \le 200000,1 \le a,b,c \le n,a+b+c=n$。</p>
<p>保证给定的图中不包含重边或自环。</p>
<p><strong>时间限制:</strong> $2\texttt{s}$</p>
<p><strong>空间限制:</strong> $1\texttt{GB}$</p>
