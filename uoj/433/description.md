# 题目描述

<p><b>f<font color="#FF0000">ateice</font></b> 喜欢串串，尤其喜欢双回文串。</p>
<p>如果你不知道啥是双回文串，一个串 $s$ 是双回文串当且仅当存在非空的回文串 $a$ 和 $b$ 满足 $s$ 由 $a$ 和 $b$ 拼接而成。例如，$aabcb$ 为双回文串，而 $aba$ 不是双回文串。</p>
<p>一天 <b>f<font color="#FF0000">ateice</font></b> 看到了一个新鲜的字符串 $s$，他把 $s$ 的所有本质不同的子串列举了出来，并且数出了其中的双回文串个数。两个字符串本质不同当且仅当它们的长度不同或存在一个下标它们对应位置的字符不同。</p>
<p><b>f<font color="#FF0000">ateice</font></b> 当然飞快地报出了答案，但是他想考考你。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>一行一个非空字符串 $s$。保证由小写字母组成。</p>

# 输出格式


<p>输出到标准输出中。</p>
<p>输出一行一个整数表示 $s$ 中本质不同的双回文串子串个数。</p>

# 样例一


<h4>input</h4>
<pre><code>abbbab</code></pre>
<h4>output</h4>
<pre><code>11</code></pre>
<h4>explanation</h4>
<p>$s$ 中本质不同的双回文子串有：ab,abb,abbb,abbbab,ba,bb,bba,bbab,bbb,bbba,bbbab，共11个。</p>

# 样例二


<h4>input</h4>
<pre><code>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</code></pre>
<h4>output</h4>
<pre><code>233</code></pre>
<h4>explanation</h4>
<p>稍有常识的人...</p>

# 样例三


<h4>input</h4>
<pre><code>abbbbaaabbbabbabbbabaababbaaababbcbbbbbaabbcbbaabbaabbbbabaabbbabbbbbaaaaabbbbbcbbbbababcaabbabcabbabaaababbbaaaabbcbcbaabbbbbabbbbbaababaababaaaabbbabaabbabaacaabaaaababbaaaaababbbbbabbaabbaabbaaabbbabaabbabaaabbabaabbbbbbababcaabbabababbbbbabbaaaaacbbaabbbaabbacbbbaacabbbabcaacbbbabaaaabbbaaababbb</code></pre>
<h4>output</h4>
<pre><code>614</code></pre>
<h4>explanation</h4>
<p>我有一个绝妙的解释，可是这里空间太小写不下。</p>

# 限制与约定


<p>对于所有数据，满足 $1 \leq |s| \leq 5 \times 10^5$。</p>
<p>共有6个子任务，每个子任务的特殊限制和分值如下：</p>
<ol><li>(10分) $|s| \leq 300$。</li>
<li>(20分) $|s| \leq 5000$。</li>
<li>(20分) $|s| \leq 40000$。</li>
<li>(20分) $|s| \leq 1.5 \times 10^5$。</li>
<li>(10分) $s$ 仅由 $\{a,b\}$ 组成并且每个字符在 $\{a,b\}$ 中等概率随机。</li>
<li>(20分) 没有附加限制。</li>
</ol><p><strong>时间限制：</strong> $\texttt{5s}$</p>
<p><strong>空间限制：</strong> $\texttt{2048MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=433">样例数据下载</a></p>
