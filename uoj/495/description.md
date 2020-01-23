# 题目描述

<p>要过年了！《蓝猫淘气三千问》里的淘气决定囤积一些好吃的以完成“每逢佳节胖十斤”的计划。然而，超威蓝猫早就把他之前的大米都偷吃完了，淘气只好出门买一些。</p>
<p>这天，淘气带着 $m$ 块钱来到了一家有 $n$ 袋大米正在出售的商店。这 $n$ 袋大米的编号依次为 $1, \dots, n$，其中第 $i$ 袋大米的重量为 $w_i$，价格为 $p_i$。</p>
<p>正当淘气觉得价格太贵准备走的时候，老板突然告诉他：这家商店正在进行年底促销，有两种促销方式！</p>
<ol><li>买 $a$ 赠一：每买 $a$ 袋大米，即可白送一袋没有买的大米；</li>
<li>买 $b$ 赠一：每买 $b$ 袋大米，即可白送一袋没有买的大米。</li>
</ol><p>不仅如此，这两种促销方式还可以同时使用。也即，如果淘气如果买了 $k$ 袋大米，那么他就可以<strong>在剩下的没有买的大米中</strong>，挑至多 $\lfloor k/a \rfloor + \lfloor k/b \rfloor$ 袋免费拿走（其中$\lfloor x \rfloor$ 表示小于等于 $x$ 的最大的整数）。</p>
<p>现在淘气想知道，对于每一个 $1 \le j \le m$，在花费至多 $j$ 块钱的情况下，从商店买走或免费拿走的大米总重量最大是多少。</p>

# 输入格式


<p>第一行四个正整数 $n, m, a, b$。保证 $1 \le a \le b \le n$。</p>
<p>第二行包含 $n$ 个正整数，分别表示 $w_1, \dots, w_n$。</p>
<p>第三行包含 $n$ 个正整数，分别表示 $p_1, \dots, p_n$。保证 $1 \le p_i \le m$。</p>

# 输出格式


<p>一行，包含 $m$ 个整数。其中第 $j$ 个整数表示在花费至多 $j$ 块钱的情况下，从商店买走或免费拿走的大米的最大总重量。</p>

# 样例一


<h4>input</h4>
<pre>8 4 1 2
4 5 3 2 6 7 3 1
2 2 2 2 2 2 2 2

</pre>

<h4>output</h4>
<pre>0 13 13 25

</pre>

<h4>explanation</h4>
<ul><li>如果淘气只花一块钱，那么什么都买不到。</li>
<li>如果淘气花两块钱，那么淘气可以买下重量为 $7$ 的大米，然后利用 “买一赠一” 拿走一袋重量为 $6$ 的大米。</li>
<li>如果淘气花四块钱，那么淘气可以买下重量为 $4$ 和 $5$ 的大米，然后利用 “买一赠一” 和 “买二赠一” 拿走三袋重量分别为 $3, 6, 7$ 的大米。</li>
</ul>
# 样例二


<h4>input</h4>
<pre>10 15 3 3
9 9 2 6 9 7 6 2 8 5
6 2 2 2 9 2 8 7 3 2

</pre>

<h4>output</h4>
<pre>0 9 9 16 17 40 42 45 48 48 53 53 63 63 63

</pre>

<h4>explanation</h4>
<p>在这个例子里，$a = b = 3$，也就是 “买三赠二”。淘气可买下的米的重量随着花的钱数递增。当淘气可以花 $13$ 块钱的时候，淘气可以买走第 $2, 3, 4, 6, 9, 10$ 号大米，然后免费拿走剩下的大米。</p>

# 样例三


<p>见“样例数据下载”</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m$</th><th>特殊限制</th></tr></thead><tbody><tr><td>$1$</td><td rowspan="2">$\le 10$</td><td rowspan="6">$\le 150$</td><td rowspan="6">无</td></tr><tr><td>$2$</td></tr><tr><td>$3$</td><td rowspan="4">$\le 50$</td></tr><tr><td>$4$</td></tr><tr><td>$5$</td></tr><tr><td>$6$</td></tr><tr><td>$7$</td><td rowspan="4">$\le 300$</td><td rowspan="4">$\le 1000$</td><td rowspan="2">$a = b$</td></tr><tr><td>$8$</td></tr><tr><td>$9$</td><td rowspan="2">无</td></tr><tr><td>$10$</td></tr></tbody></table></div>

<p>对于所有数据，保证 $1 \le w_i \le 10^6$。</p>
<p><strong>时间限制</strong>：$\texttt{1s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=495">样例数据下载</a></p>
