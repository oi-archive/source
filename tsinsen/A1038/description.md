<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给定一个仅包含小写字母的字符串，求其中的最长连续重复子串的长度。<br/>
　　设给定的字符串为S[1...n]，那么最长连续重复子串S[i...j]满足以下条件：<br/>
　　1．1&lt;=i&lt;=j&lt;=n并且j-i+1为偶数；<br/>
　　2．设L=(j-i+1)/2，那么对于0&lt;=k&lt;L都有S[I+K]=S[I+L+K]；<br/>
　　3．最长重复子串是满足1,2的i,j中j-i+1的值最大的。</div>
# 输入格式

<div class="pdcont">　　输入仅一行，为给出的字符串，长度不超过100。</div>
# 输出格式

<div class="pdcont">　　输出仅包含一个整数，为最长连续重复子串的长度。</div>
# 样例输入

<pre class="pddata">abababa</pre>
<p></p>
<br/><p></p><p class="subtitle">样例输出</p><p class="probcontent">
</p><p><font face="Times New Roman" size="3"></font></p><pre><font face="Times New Roman" size="3">4</font></pre>
<p></p>
<br/>



</div>