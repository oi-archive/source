<div id="pcont1" style="margin-top:20px; display:block;">

# 描述

<div class="pdcont">　　Freda非常喜欢字符串~，最近她想从商店买一个字符串作为礼物送给Rainbow。这个商店非常神犇——它有能通过给定的字符集组成的所有种类的字符串！字符集的大小是k。Freda恰好有这个商店的代金券，不过这个代金券有个限制：它只能用来购买&#34;最长次连续子串的长度等于w”的字符串。<br/>
　　长度为n的字符串a被称为长度为m的字符串s的”次连续子串“，当且仅当a是s的子串，并且还存在一系列编号1&lt;=i1&lt;i2&lt;i3&lt;……&lt;in&lt;=m满足如下条件：<br/>
　　对于1&lt;=k&lt;=n，a[k]=s[ik];<br/>
　　存在至少一个k(1&lt;=k&lt;=n)，满足i(k+1) - ik &gt; 1.<br/>
　　Freda想知道商店中有多少种字符串可以供她购买。由于这个数可能很大，你只需要求出它对1000000007取模后的结果。如果有无限个可供购买的字符串，输出-1。</div>
# 输入格式

<div class="pdcont">　　一行两个整数，k和w。</div>
# 输出格式

<div class="pdcont">　　输出可以供Freda购买的字符串数量mod 1000000007。</div>
# 样例输入

<div class="pddata">2 2</div>
# 样例输出

<div class="pddata">10</div>
# 样例输入

<div class="pddata">3 5</div>
# 样例输出

<div class="pddata">1593</div>
# 样例输入

<div class="pddata">2 139</div>
# 样例输出

<div class="pddata">717248223</div>
# 数据规模和约定

<div class="pdcont">　　1&lt;=k&lt;=10^6，2&lt;=w&lt;=10^9。<br/>
　　在第一个样例中Freda可以购买aaa, aab, abab, abb, abba, baa, baab, baba, bba, bbb这些字符串。</div>

</div>