# 题目描述

<p>有一棵 $n$ 个结点的有根树 $T$。结点编号为 $1 \dots n$，其中根结点为 $1$。</p>
<p>树上每条边的长度为 $1$。我们用 $d(x,y)$ 表示结点 $x, y$ 在树上的距离，$\text{LCA}(x,y)$ 表示 $x, y$ 的最近公共祖先（即树中最深的既是 $v$ 的祖先也是 $u$ 的祖先的结点）。</p>
<p>对于两个结点 $u,v$ $(u\neq v)$，令 $a=\text{LCA}(u,v)$，定义 $f(u,v)=\gcd (d(u,a),d(v,a))$。其中 $\gcd(x,y)$ 表示 $x,y$ 的最大公约数，特别地， $\gcd(0,x)=\gcd(x,0)=x$ $(x\neq 0)$。</p>
<p>对于所有 $i \in \{1,2,\cdots,n-1 \}$，求出有多少对 $(u,v)$ $(u &lt; v)$，满足 $f(u,v) = i$。</p>

# 输入格式


<p>输入第一行包含一个正整数 $n$。保证 $n \geq 2$。</p>
<p>第 $2$ 到 $n$ 行中，第 $i$ 行有一个正整数 $p_i$，表示结点 $i$ 在树上的父亲是 $p_i$。保证 $p_i &lt; i$。</p>

# 输出格式


<p>输出共 $n-1$ 行，其中第 $i$ 行表示对于 $i$ 的答案。</p>
<p>C/C++ 输入输出 long long 时请用 <code>%lld</code>。C++ 可以直接使用 cin/cout 输入输出。</p>

# 样例一


<h4>input</h4>
<pre>5
1
2
2
1

</pre>

<h4>output</h4>
<pre>8
2
0
0

</pre>


# 样例二


<h4>input</h4>
<pre>8
1
2
3
4
1
6
6

</pre>

<h4>output</h4>
<pre>16
9
2
1
0
0
0

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
<th>备注</th>
</tr></thead><tbody><tr><td>1</td><td>$n \leq 2000$</td><td rowspan="3">$p_i$ 在 $\{1,2,\cdots,i-1\}$ 中均匀随机</td></tr><tr><td>2</td><td>$n \leq 100000$</td></tr><tr><td>3</td><td>$n \leq 200000$</td></tr><tr><td>4</td><td>$n \leq 200000$</td><td>除根结点外的每个结点至多拥有一个孩子</td></tr><tr><td>5</td><td>$n \leq 200000$</td><td>$p_i$ 在 $\max\{i - 10, 1\}$ 到 $i - 1$ 之间均匀随机</td></tr><tr><td>6</td><td>$n \leq 50000$</td><td rowspan="5">无</td></tr><tr><td>7</td><td>$n \leq 100000$</td></tr><tr><td>8</td><td>$n \leq 150000$</td></tr><tr><td>9</td><td>$n \leq 200000$</td></tr><tr><td>10</td><td>$n \leq 200000$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=33">样例数据下载</a></p>
