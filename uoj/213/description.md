# 题目描述

<p>小C与 Saber 签订契约之后达成了共同争夺圣杯的目标，然而他们赢得圣杯的道路并没有这么轻易，小C需要与其他的英灵进行决战。</p>
<p>小C通过一些交易得知，其他的英灵已经结盟了。大决战那天，其他的英灵站成了一排，从左到右依次编号为 $1$ 到 $n$，血量依次为 $\mathrm{HP}_1, \dots, \mathrm{HP}_n$。</p>
<p>小C还知道，这些英灵暗自商量了一个整数 $m$ （$1 \leq m \leq n$）。Saber 和这些英灵之间的战斗将会持续 $n - m + 1$ 轮，其中第 $i$ 轮 Saber 将与编号为 $i, i + 1, \dots, i + m - 1$ 的英灵进行战斗，所需要耗费的魔力值为这些战斗的英灵中的血量的<strong>最大值</strong>。而由于人多力量大等因素，每轮战斗后英灵的血量不会有任何变化。</p>
<p>所有战斗结束后，Saber 耗费的总魔力值为每轮战斗耗费的魔力值之和。</p>
<p>小C和 Saber 必须挺过这 $n - m + 1$ 轮，之后这些英灵将一而再，再而三，三而竭，闻风丧胆，望风而逃，三十六计走为上。小C很焦虑，于是就来向您求救。小C想要知道所有可能的 $m = 1， 2， \dots, n$ 中，Saber 需要耗费的总魔力值分别是多少。</p>
<p>为了避免一些奇怪的原因，你只要输出所有情况的总魔力值模 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）后，逐个按位异或起来的结果。（异或即 C/C++ 中的 <samp>^</samp>，Pascal 中的 <samp>xor</samp>）</p>

# 输入格式


<p>第一行一个正整数 $n$。</p>
<p>第二行包含了 $n$ 个整数 $\mathrm{HP}_1, \dots, \mathrm{HP}_n$，表示这 $n$ 个英灵的血量。</p>
<p><strong>注意：由于本题目的输入可能很大，请选择较为快速的读入方式。</strong></p>

# 输出格式


<p>输出一行，一个整数，表示所有情况的总魔力值取模后逐个按位异或起来的结果。</p>

# 样例一


<h4>input</h4>
<pre>6
19 4 20 19 1 10

</pre>

<h4>output</h4>
<pre>94

</pre>


# explanation


<p>$m= 1, 2, 3, 4, 5, 6$ 时候的对应的每个值分别是 $73,88,79,60,40,20$。</p>
<p>答案是 $73 \mathbin{\mathrm{xor}} 88 \mathbin{\mathrm{xor}} 79 \mathbin{\mathrm{xor}} 60 \mathbin{\mathrm{xor}} 40 \mathbin{\mathrm{xor}} 20= 94$。</p>

# 样例二


<h4>input</h4>
<pre>6
5 19 7 10 16 7

</pre>

<h4>output</h4>
<pre>85

</pre>


# 样例三


<p>见样例数据下载，限制与约定跟第 $5$ 个测试点相同。</p>

# 样例四


<p>见样例数据下载，限制与约定跟第 $8$ 个测试点相同。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td rowspan="1">$\leq 10^2$</td><td rowspan="3"></td></tr><tr><td>2</td><td rowspan="2">$\leq 10^3$</td></tr><tr><td>3</td></tr><tr><td>4</td><td>$\leq 10^5$</td><td rowspan="3">$\mathrm{HP}_i$ 在 $[0,10^9]$ 均匀随机</td></tr><tr><td>5</td><td>$\leq 2 \times 10^5$</td></tr><tr><td>6</td><td>$\leq 5 \times 10^5$</td></tr><tr><td>7</td><td>$\leq 10^5$</td><td rowspan="4"></td></tr><tr><td>8</td><td>$\leq 2 \times 10^5$</td></tr><tr><td>9</td><td>$\leq 5 \times 10^5$</td></tr><tr><td>10</td><td>$\leq 10^6$</td></tr></tbody></table></div>

<p>对于所有数据，$0 \leq \mathrm{HP}_i \leq 10^9$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=213">样例数据下载</a></p>
