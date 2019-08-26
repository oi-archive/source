
# Description

<div class="content"><p class="MsoNormal"></p>
<p class="MsoNormal">给定k个长度不超过L的01串，求有多少长度为n的01串S满足：</p>
<p class="MsoNormal">1.该串是回文串</p>
<p class="MsoNormal">2.该串不存在两个不重叠的子串，在给定的k个串中。</p>
<p class="MsoNormal">即不存在a&lt;=b&lt;c&lt;=d，S[a,b]是k个串中的一个，S[c,d]是k个串中的一个</p>
<p class="MsoNormal">(It does not contain two non-overlapped substrings in the given list of K binary strings.)</p>
<p class="MsoNormal">举个例子，若给定2(k=2)个01串：101和1001</p>
<p class="MsoNormal">1010001和1010101均不满足条件。前者不满足条件1，后者不满足条件2</p>
<p></p></div>

# Input

<div class="content"><div>
<p class="MsoNormal">第一行两个整数n,k</p>
<p class="MsoNormal">以下k行，每行一个01串</p>
</div>
<p></p></div>

# Output

<div class="content"><div>输出一个整数表示答案，答案mod 1000000007（10^9+7）</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 1<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">n&lt;=300,k&lt;=30,L&lt;=30</span></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

