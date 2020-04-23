# 题目描述

<p>躲过了AlphaGo之后，你躲在SingleDog的长毛里，和它们一起来到了AlphaGo的家。此时你们才突然发现，AlphaGo的家居然是一个隐藏在地下的计算中心！难道AlphaGo如此人赢的秘密是...它其实是一个AI？</p>
<p>根据情报，这个地下的计算中心的结构构成了一棵无根树，整个计算中心名为被AT-field的力场保护起来，保护力场的直径恰好等于树的直径（树的直径定义为树上距离最远的两个结点之间的距离，结点 $u,v$ 的距离定义为从 $u$ 到 $v$ 最少需要经过的边数）。</p>
<p>由于保护力场的存在，SingleDog们每次只能进入整棵树的一个叶子（<strong>度为1的结点</strong>），由于狗的大脑很小，他们每次只会随机进攻一个<strong>原树</strong>的叶子，并且破坏里面的设备，更加狼狈的是他们甚至会重复进入一个已经被破坏过的叶子。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/351/351.png" alt="一棵树" style="width:300px;"/></p>
<p>比如这棵树中，SingleDog们攻击的就是$\{2,4,7,9\}$这四个点，他们不会攻击$1$号点，因为它不是原树的叶子。</p>
<p>他们想知道，期望多少次之后，可以使得保护力场的直径缩小？</p>
<p>即，对于一棵树，每次随机染黑一个叶子（可能会重复染黑），期望多少次后直径变小？</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行一个正整数$n$，表示树的点数。</p>
<p>接下来$n-1$行，每行两个正整数$x,y$，表示树上的一条边。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出一行一个整数表示答案在模 $998244353$ 意义下的取值。</p>
<p>即设答案化为最简分式后的形式为 $\frac{a}{b}$ ，其中 $a$ 和 $b$ 互质。输出整数 $x$ 使得 $bx\equiv a \pmod{998244353}$且 $0\le x &lt; 998244353$。可以证明这样的整数 $x$ 是唯一的。</p>

# 样例一


<h4>input</h4>
<pre>3
1 2
2 3

</pre>

<h4>output</h4>
<pre>1

</pre>


# 样例二


<h4>input</h4>
<pre>6
1 2
2 3
1 4
4 5
1 6

</pre>

<h4>output</h4>
<pre>499122178

</pre>


# 样例三


<p>见样例数据下载。</p>

# 样例四


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有数据，$3 \le n \le 5\times10^5$，$1\le x,y\le n$。</p>
<p>为了拿到每个子任务的分数，你必须通过<strong>所有</strong>他依赖的子任务。</p>
<div class="table-responsive">
 <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
    <th>分值</th>
    <th>$n$</th>
    <th>特殊性质</th>
    <th>依赖的subtask</th>
   </tr></thead><tbody><tr><td>1</td>
    <td>12</td>
    <td>$\le 10$</td>
    <td>无</td>
    <td>无</td>
   </tr><tr><td>2</td>
    <td>18</td>
    <td>$\le  3\times 10^3$</td>
    <td>无</td>
    <td>$1$</td>
   </tr><tr><td>3</td>
    <td>20</td>
    <td>$\le  5\times 10^5$</td>
    <td>树上任意两点距离（距离定义为两点间最短路边的条数）$\le 3$</td>
    <td>无</td>
   </tr><tr><td>4</td>
    <td>15</td>
    <td>$\le  5\times 10^5$</td>
    <td>任意点度数$\le 3$</td>
    <td>无</td>
   </tr><tr><td>5</td>
    <td>35</td>
    <td>$\le  5\times 10^5$</td>
    <td>无</td>
    <td>$1,2,3,4$</td>
   </tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=351">样例数据下载</a></p>
