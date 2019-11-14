# 题目描述

<p>贾樟柯在《山河故人》里说，「生活就是重复」。在生活中，人们总是喜欢重复自己做过的事情。语言就是一个很经典的例子。  </p>
<p>比如，我们在表示疑问时，总不满足于使用一个问号「？」；使用一连串的问号「？？？？」总是显得比较有力。  </p>
<p>在表示抱歉
时，一句「对不起」总显得不够情愿；连着表示「对不起对不起」才足够表达自己的真诚。  </p>
<p>A 国就是一个喜欢重复的国家。在这个国家中，一个基本句子可以用一个长度恰好为 $m$ 的小写字母字符串表示。为了表达自己对重复的喜爱，A 国的人们总喜欢把自己想要表达的句子重复无限多次。  </p>
<p>有时，这样的重复是充满意义的。A 国的人们把一个字典序小于给定的字符串 $s$，且长度和 $s$ 相同的小写字母字符串称为一个有意义的语义片段。他们想知道，有多少个不同的基本句子（即长度恰好为 $m$ 的小写字母字符串）在经过无限重复后，可以从中找出至少一个有意义的语义片段？</p>

# 输入格式


<p>输入文件的第一行为一个正整数 $m$，表示基本句子的长度；第二行为一个小写字母字符串 $s$，其含义详见题目描述。</p>

# 输出格式


<p>输出一行一个整数，为满足条件的基本句子的数量。为了避免答案过大，你只需要输出将答案对 $998244353$ 取模后的结果。</p>

# 样例一


<h4>input</h4>
<pre><code>3
abc</code></pre>
<h4>output</h4>
<pre><code>79</code></pre>

# 样例二


<h4>input</h4>
<pre><code>5
zxcvb</code></pre>
<h4>output</h4>
<pre><code>11881375</code></pre>

# 限制与约定


<p>设字符串 $s$ 的长度为 $n$，对于所有测试数据：$1\le n,m\le 2000$。</p>
<p>每个测试点的具体限制见下表：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>测试点编号</th><th>$m$</th><th>$n$</th><th>特殊性质</th></tr></thead><tbody><tr><td>$1$</td><td>$\le 5$</td><td>$\le 10$</td><td>$m\lt n$</td></tr><tr><td>$2$</td><td>$\le 30$</td><td>$\le 30$</td><td>$m=n$</td></tr><tr><td>$3$</td><td>$\le 50$</td><td>$\le 30$</td><td>$m\gt n$</td></tr><tr><td>$4$</td><td>$\le 100$</td><td>$\le 100$</td><td>$m\lt n$</td></tr><tr><td>$5$</td><td>$\le 200$</td><td>$\le 200$</td><td>$m=n$</td></tr><tr><td>$6$</td><td>$\le 300$</td><td>$\le 200$</td><td>$m\gt n$</td></tr><tr><td>$7$</td><td>$\le 300$</td><td>$\le 2000$</td><td>$m\lt n$</td></tr><tr><td>$8$</td><td>$\le 1000$</td><td>$\le 1000$</td><td>$m=n$</td></tr><tr><td>$9$</td><td>$\le 2000$</td><td>$\le 200$</td><td>$m\gt n$</td></tr><tr><td>$10$</td><td>$\le 2000$</td><td>$\le 2000$</td><td>$m\gt n$</td></tr></tbody></table></div>

<p><strong>时间限制: 1s</strong></p>
<p><strong>空间限制: 512MB</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=476">样例数据下载</a></p>
