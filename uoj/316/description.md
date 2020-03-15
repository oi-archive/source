# 题目描述

<p>久莲是个爱玩的女孩子。</p>
<p>暑假终于到了，久莲决定请她的朋友们来游泳，她打算先在她家的私人海滩外圈一块长方形的海域作为游泳场。然而大海里有着各种各样的危险，有些地方水太深，有些地方有带毒的水母出没。她想让圈出来的这一块海域都是安全的。</p>
<p>经过初步的分析，她把这块海域抽象成了一个底边长为 $N$ 米，高为 $1001$ 米的长方形网格。其中网格的底边对应着她家的私人海滩，每一个 $1 米\times 1 米$ 的小正方形都代表着一个单位海域。她拜托了她爸爸明天去测量每一个小正方形是否安全。在得知了信息之后，她要做的就是圈出她想要的游泳场啦。</p>
<p>她心目中理想的游泳场满足如下三个条件：</p>
<ul><li>必须保证安全性。即游泳场中的每一个单位海域都是安全的。</li>
<li>必须是矩形。即游泳场必须是整个网格中的一个 $a \times b$ 的子网格。</li>
<li>必须和海滩相邻。即游泳场的下边界必须紧贴网格的下边界。</li>
</ul><p>例如：当 $N=5$ 时，若测量的结果如下（因为 $1001$ 太大，这儿只画出网格最下面三行的信息，其他部分都是危险的）。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/316/1.png" alt="游泳池" style="width:400px;"/></p>
<p>那么她可以选取最下面一行的 $1 \times 4$ 的子海域，也可以选择第三列的 $3 \times 1$ 的子海域。注意她不能选取最上面一行的 $1 \times 5$ 的子海域，因为它没有与海滩相邻。</p>
<p>为了让朋友们玩的开心，她想让游泳场的面积尽可能的大。因此她会选取最下面那一行的 $1 \times 4$ 的子海域作为最终方案。</p>
<p>虽然她要明天才能知道每一个单位海域是否安全，但是她现在就想行动起来估计一下她的游泳场面积有多大。经过简单的估计，她假设每一个单位海域都有独立的 $q$ 的概率是安全的，$1-q$ 的概率是不安全的。她想要知道她能选择的最大的游泳场的面积<strong>恰好</strong>为 $K$ 的概率是多少。</p>
<p>然而久莲对数学并不感兴趣，因此她想让你来帮她计算一下这个数值。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>输入一行四个正整数 $N,K,x,y$，其中 $1 \leq x &lt; y &lt; 998244353$。$q$ 的取值为 $\frac{x}{y}$。 </p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出一行一个整数表示答案在模 $998244353$ 意义下的取值。</p>
<p>即设答案化为最简分式后的形式为 $\frac{a}{b}$ ，其中 $a$ 和 $b$ 的互质。输出整数 $x$ 使得 $bx \equiv a \mod 998244353$ 且 $0 \leq x &lt; 998244353$。可以证明这样的整数 $x$ 是唯一的。 </p>

# 样例一


<h4>input</h4>
<pre>10 5 1 2

</pre>


<h4>output</h4>
<pre>342025319

</pre>


# 样例二


<p>见“样例数据下载”</p>

# 样例三


<p>见“样例数据下载”</p>

# 提示


<p>$x^{p-1} \equiv 1 \mod p$，其中 $p$ 为质数，$x \in [1,p)$。</p>

# 限制与约定


 <div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$N$</th><th rowspan="1">$K$</th></tr></thead><tbody><tr><td rowspan="1">1,2</td><td rowspan="1">$=1$</td><td rowspan="1">$\leq 1000$</td></tr><tr><td rowspan="1">3</td><td rowspan="1">$\leq 10$</td><td rowspan="1">$\leq 8$</td></tr><tr><td rowspan="1">4</td><td rowspan="1">$\leq 10$</td><td rowspan="1">$\leq 9$</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$\leq 10$</td><td rowspan="1">$\leq 10$</td></tr><tr><td rowspan="1">6</td><td rowspan="1">$\leq 1000$</td><td rowspan="1">$\leq 7$</td></tr><tr><td rowspan="1">7</td><td rowspan="1">$\leq 1000$</td><td rowspan="1">$\leq 8$</td></tr><tr><td rowspan="1">8</td><td rowspan="1">$\leq 1000$</td><td rowspan="1">$\leq 9$</td></tr><tr><td rowspan="1">9,10,11</td><td rowspan="1">$\leq 1000$</td><td rowspan="1">$\leq 100$</td></tr><tr><td rowspan="1">12,13,14</td><td rowspan="1">$\leq 1000$</td><td rowspan="1">$\leq 1000$</td></tr><tr><td rowspan="1">15,16</td><td rowspan="1">$\leq 10^9$</td><td rowspan="1">$\leq 10$</td></tr><tr><td rowspan="1">17,18</td><td rowspan="1">$\leq 10^9$</td><td rowspan="1">$\leq 100$</td></tr><tr><td rowspan="1">19,20</td><td rowspan="1">$\leq 10^9$</td><td rowspan="1">$\leq 1000$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=316">样例数据下载</a></p>
