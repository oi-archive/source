# 题目描述

<p>今天是世界水日，著名的水题资源专家蝈蝈大臣向世界宣布了他的一项新发明 —— 水题生成器。</p>
<p>每道题目都有一个正整数的难度值。水题生成器虽然强大但是功能有限。水题生成器内部有一个参数 $n$，你可以告诉水题生成器一个能<strong>整除</strong> $n!$ 的<strong>正整数</strong> $d$，水题生成器就会产生一道难度值恰为 $d$ 的水题。这里 $n!$ 表示 $n$ 的阶乘。</p>
<p>现在蝈蝈大臣的助手欧姆想用水题生成器产生不超过 $n$ 道水题，且难度值之和恰为 $m$。保证 $1 \leq m \leq n!$。</p>
<p>欧姆当然知道怎么做啦！但是他想考考你。请你给出一组合法方案或输出无解。</p>

# 输入格式


<p>第一行一个正整数 $n$。</p>
<p>第二行一个正整数 $m$。保证 $1 \leq m \leq n!$。</p>

# 输出格式


<p>不超过 $n$ 行，每行一个正整数 $d$，表示你每次告诉水题生成器的难度值。</p>
<p>输出的每个难度值都必须是 $n!$ 的约数，且难度值之和恰为 $m$。</p>
<p>如果有多组解，输出任意一组均可。如果无解请直接输出卖萌表情 “<samp>&gt;w&lt;</samp>”（不含引号）</p>

# 样例一


<h4>input</h4>
<pre>5
100

</pre>

<h4>output</h4>
<pre>40
40
20

</pre>

<h4>explanation</h4>
<p>$5! = 1 \times 2 \times 3 \times 4 \times 5 = 120$。$20$ 和 $40$ 都是 $120$ 的约数，且 $40 + 40 + 20 = 100$。</p>

# 样例二


<h4>input</h4>
<pre>10
3628800

</pre>

<h4>output</h4>
<pre>3628800

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
</tr></thead><tbody><tr><td>1, 2, 3, 4, 5, 6</td><td>$n \leq 5$</td></tr><tr><td>7, 8, 9, 10, 11, 12, 13, 14</td><td>$n \leq 9$</td></tr><tr><td>15, 16, 17, 18, 19, 20</td><td>$n \leq 20$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=82">样例数据下载</a></p>
