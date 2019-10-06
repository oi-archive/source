# 题目描述

<p>小p参加政治考试，总共有$n$道判断题。一些题目小p可以靠自己的能力蒙一个答案，然而对于一些他完全不会的题，他会通过某种方式得到标准答案然后填上去。小p具有时间倒流的能力，因此可以参加$q$次同样的考试，不过每次考试他的策略未必相同。众所周知，只有AK才能满足小p的欲望，而每道题的答案是未知的，小p想知道有多少种标准答案使得他在至少一次考试中能AK。</p>

# 输入格式


<p>第一行两个整数$n,q$。</p>
<p>下接$q$行，每行一个长为$n$的字符串，包含<code>0</code> 、<code>1</code> 、<code>?</code> 这三种字符，数字意味着答案是小p蒙的（可以匹配这种字符），$?$ 表示这道题他得到了标准答案（可以匹配任意字符）。</p>

# 输出格式


<p>一行一个整数，表示有多少长为$n$的$01$串$s$，使得$s$满足$q$ 个串中至少一个串的形式。</p>

# 样例一


<h4>input</h4>
<pre><code>4 2
??01
1??1</code></pre>
<h4>output</h4>
<pre><code>6</code></pre>
<h4>explanation</h4>
<p>共有这些合法的串：<code>0001</code>, <code>0101</code>, <code>1001</code>, <code>1101</code>, <code>1011</code>, <code>1111</code></p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>$n\leq$</th><th>$q\leq$</th><th>特殊性质</th><th>分值</th>
</tr></thead><tbody><tr><td>1</td><td>$20$</td><td>$20$</td><td></td><td>$3$</td>
</tr><tr><td>2</td><td>$30$</td><td>$20$</td><td></td><td>$12$</td>
</tr><tr><td>3</td><td>$25$</td><td>$30$</td><td></td><td>$11$</td>
</tr><tr><td>4</td><td>$30$</td><td>$30$</td><td></td><td>$6$</td>
</tr><tr><td>5</td><td>$30$</td><td>$100$</td><td>问号总数$\leq 40$</td><td>$11$</td>
</tr><tr><td>6</td><td>$30$</td><td>$50$</td><td></td><td>$16$</td>
</tr><tr><td>7</td><td>$30$</td><td>$100$</td><td></td><td>$41$</td>
</tr></tbody></table></div>

<p><strong>时间限制</strong>：$\texttt{1s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=425">样例数据下载</a></p>
