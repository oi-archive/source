
# Description

<div class="content"><p>给出N个正整数a[1..N]，再给出K个关系符号（&gt;、&lt;或=）s[1..k]。<br/>
选出一个长度为L的子序列（不要求连续），要求这个子序列的第i项和第i+1项的的大小关系为s[(i-1)mod K+1]。<br/>
求出L的最大值。</p>
<p></p></div>

# Input

<div class="content"><p>第一行两个正整数，分别表示N和K (N, K &lt;= 500,000)。<br/>
第二行给出N个正整数，第i个正整数表示a[i] (a[i] &lt;= 10^6)。<br/>
第三行给出K个空格隔开关系符号（&gt;、&lt;或=），第i个表示s[i]。</p>
<p></p></div>

# Output

<div class="content"><p>一个正整数，表示L的最大值。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 3<br/>
2 4 3 1 3 5 3<br/>
&lt; &gt; =<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>选出的子序列为2 4 3 3 5 3，相邻大小关系分别是&lt; &gt; = &lt; &gt;。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

