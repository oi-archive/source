
# Description

<div class="content"><div>带有子串包含约束的最长公共子序列问题可以具体表述如下。 </div>
<div>给定2个长度分别为n和m的序列X和Y，以及一个子串包含约束集S。</div>
<div>S中共有k个字符串S={S1,S2,…,Sk}，其中字符串Si的长度为li，1≤i≤k。带有子串包含约束的最长公共子序列问题就是要找出X和Y的包含约束集S中所有字符串为其子串的最长公共子序列。 </div>
<div>例如，如果给定的序列X和Y分别为X=actaagacct, Y=gacctacctc，子串包含约束集S={ata, tact}，则子序列actacct是X和Y的一个无约束的最长公共子序列，而包含约束集S中所有字符串为其子串的一个最长公共子序列是atact 。 </div>
<div>在本题中请特别关注子串与子序列的区别。字符串T=t1…tn的子串是一个形如T’=t1+i…tm+i的字符串，其中，0≤i，m+i≤n。例如，T=abcdefg，则bcd是T 的一个子串，而bce是T的一个子序列，但不是T 的子串。</div>
<div>设计一个算法，找出给定序列X和Y带有子串包含约束S的最长公共子序列。 </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第1行中给出正整数n,m,k，m＜300, n＜300, k＜6。n和m分别表示给定序列X和Y的长度。k表示子串包含约束集S中共有k个字符串。</div>
<div>
<div>第2行中有k个整数li，0≤li≤300,1≤i≤k，分别表示子串包含约束集S中k个字符串的长度度。</div>
<div>第3行和第4行分别给出序列X和Y 。</div>
<div>接下来k行每行一个字符串Si</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>将计算出的X和Y带子串包含约束S的最长公共子序列的长度输出。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 10 2<br/>
3 4<br/>
actaagacct<br/>
gacctacctc<br/>
ata<br/>
tact</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p>字符串仅包含大小写字母.</p><br/>
<p>2016.3.26加强数据 By <span style="color: rgb(61, 136, 45); font-family: &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; font-weight: bold; line-height: 23px;">immortalCO</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

