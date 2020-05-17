# 题目描述

<p>蒜斜一直怀疑自己和北大算协是高维空间中某个分形的两个分支。支撑这个观点的证据有很多。其一，他们都叫蒜斜（算协）；其二，他们都低调、奢华、有内涵，帅气、阳光、有魅力；其三，他们的好朋友都叫镁团（美团）。</p>
<p>蒜斜也常常思考，在高维空间里，他和北大算协之间有什么关系呢？这个问题过于高端，让我们先来看一个二维的版本吧。</p>
<p>定义如下的分形：</p>
<ol><li>$0$ 级的 <code>o</code> 是一个 $1\times 1$ 的字符矩阵，里面包含了一个字符 <code>o</code>。</li>
<li>$0$ 级的 <code>x</code> 是一个 $1 \times 1$ 的字符矩阵，里面包含了一个字符 <code>x</code>。</li>
<li>$i$ 级的 <code>x</code> 和 <code>o</code> 均是 $3^i \times 3^i$ 的字符矩阵，它们通过将 $i-1$ 级别的 <code>x</code>,<code>o</code> 通过如下方式排列得到（左侧表示 <code>x</code>，右侧表示 <code>o</code>）：</li>
</ol><pre><code>xox ooo
oxo oxo
xox ooo</code></pre>
<p>举例来说，二级的 <code>x</code> 和 <code>o</code> 分别为：</p>
<pre><code>xoxoooxox ooooooooo
oxooxooxo oxooxooxo
xoxoooxox ooooooooo
oooxoxooo oooxoxooo
oxooxooxo oxooxooxo
oooxoxooo oooxoxooo
xoxoooxox ooooooooo
oxooxooxo oxooxooxo
xoxoooxox ooooooooo</code></pre>
<p>一个人穷极一生，接触到的也只不过是世界的一部分。在这个二维的版本中，这个范围可以表示成 $n$ 级别的 <code>x</code> 中的一个子矩形：它包含第 $xl$ 行至第 $xr$ 行的第 $yl$ 列至 $yr$ 列。</p>
<p>人一生中接触到的一些事物是连续的，就像这个分形中的 <code>o</code> 一样；而又有一些事物是突然发生的，就像这个分形中的 <code>x</code> 一样。而这些突然发生的事物又把连续的一生给划分成了一块一块丰富多彩的篇章。在这题中，蒜斜希望你计算 $n$ 级 <code>x</code> 的某一个子矩形中，<code>o</code> 被分割成了多少个四连通块。</p>
<p>给定一个矩阵，两个字符 <code>o</code> 在同一个四连通块里，当且仅当从一个 <code>o</code> 出发，不停的向上下左右移动，可以在只经过 <code>o</code> 的情况下到达另一个 <code>o</code>。</p>

# 输入格式


<p>输入第一行是一个整数 $t(1 \leq t \leq 50)$，表示数据组数。</p>
<p>对于每组数据，输入包含一行五个整数 $n, xl, xr, yl, yr (1 \leq n \leq 35, 1 \leq xl \leq xr \leq 3^n, 1 \leq yl \leq yr \leq 3^n)$。</p>

# 输出格式


<p>对于每组数据，输出一行一个整数表示 <code>o</code> 的四连通块个数。答案可能很大，你只需要输出对 $998244353$ 取模后的值。</p>

# 样例一


<h4>input</h4>
<pre>5
1 1 3 1 3
2 1 9 1 9
2 3 5 4 8
2 1 6 2 7
35 1 50031545098999707 1 50031545098999707

</pre>

<h4>output</h4>
<pre>4
12
3
5
679477107

</pre>

<h4>explanation</h4>
<p>这儿以第三组数据为例，在第三组数据中，涉及到的子矩形为：</p>
<pre><code>oooxo
xoxoo
oxoox</code></pre>
<p>显然，在这个子矩形中，<code>o</code> 被 <code>x</code> 划分成了 $3$ 个四连通块。</p>

# 限制与约定


<p><strong>Small Task</strong>: $n \leq 35, xr - xl \leq 2$。</p>
<p><strong>Large Task</strong>: $n \leq 35$。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=528">样例数据下载</a></p>
