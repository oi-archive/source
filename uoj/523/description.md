# 题目描述

<p>蒜斜刚来PKU的时候还不知道有“北大算协”这个社团，因此他总是觉得周围的人在偷偷议论着他，比如说：</p>
<p>“算协（注：非蒜斜）举办的活动好有趣啊！”</p>
<p>“算协（注：非蒜斜）好帅啊！”</p>
<p>蒜斜每次听到这些话就会想入非非，但仔细想想，自己好像也没有那么帅吧？最离谱的一次还是：</p>
<p>“算协（注：非蒜斜）有好多小哥哥”（雾）</p>
<p>自从蒜斜学习了<strong>半前缀</strong>之后，他把这些话都看开了 —— 对他来说，只要这些话里有 “蒜斜好” 的半前缀就足够了。</p>

# 题目描述


<p>设小写字母字符串 $s$, 长度为 $n$, $s[l:r]$ 表示第 $l$ 个到第 $r$ 个字符构成的子串, $l&gt;r$ 时对应空串。</p>
<p>定义半前缀是 $s[1:i] + s[j:k]$, 其中 $0 \leq i &lt; len(s), i &lt; j \leq len(s),j-1 \leq k\leq len(s)$。直观上来说，你可以把半前缀理解成某一个前缀 $s[1:k]$ 删除掉某一个子串后形成的结果（当然也允许不删）。</p>
<p>给出字符串 $s$，你需要求出 $s$ 的所有半前缀中，有多少个不同的字符串。</p>

# 输入格式


<p>输入一行包含一个小写字符串 $s (1 \leq |s| \leq 10^6)$。</p>

# 输出格式


<p>输出一行一个整数，表示答案。</p>

# 样例一


<h4>input</h4>
<pre>aab

</pre>

<h4>output</h4>
<pre>6

</pre>

<h4>explanation</h4>
<p>字符串 <code>aab</code> 的半前缀有：空串，<code>a</code>，<code>b</code>，<code>aa</code>，<code>ab</code>，<code>aab</code>。</p>

# 样例二


<h4>input</h4>
<pre>pkusaamtcup

</pre>

<h4>output</h4>
<pre>217

</pre>



# 限制与约定


<p><strong>Small Task</strong>: $|s| \leq 3000$。</p>
<p><strong>Large Task</strong>: $|s| \leq 10^6$。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=523">样例数据下载</a></p>
