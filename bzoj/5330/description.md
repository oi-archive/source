
# Description

<div class="content"><div>“回文串什么的最讨厌了……”</div>
<div>小Q讨厌任何形式的回文串：</div>
<div>（1）如果一个字符串从左往右读和从右往左读是一样的，那么小Q讨厌它；例如aa和aba</div>
<div>（2）对于一个字符串来说，若将某个前缀子串移除并拼接到字符串的尾部，能得到一个小Q讨厌的字符串，</div>
<div>那么小Q也会讨厌原来的这个字符串；例如aab和baa。</div>
<div>现在问题来了，如果任意字符串只可以由k种已知的字符组成（也就是说字符集的大小为k），</div>
<div>那么长度为n的所有字符串里，有多少字符串是小Q讨厌的？</div>
<div>答案可能很大，你只需要给出答案对p取模后的值。</div>
<div></div>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数T，表示有T组测试数据。</div>
<div>接下来T行，每行描述一组测试数据，包含三个正整数n,k和p。</div>
<div>1&lt;=T&lt;=10,1&lt;=n&lt;=10^18,1&lt;=k&lt;=n,10^9&lt;=p&lt;=2^30</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组测试数据，输出一行，包含一个整数，表示答案对p取模的值。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
9311702400 2063322107 1032035101<br/>
9311702400 3847844404 1014424217<br/>
9311702400 6992683534 1067435323<br/>
9311702400 1356819643 1024817347<br/>
9311702400 6944668829 1042812553<br/>
9311702400 9162670852 1003177793<br/>
9311702400 6567188538 1062813337<br/>
9311702400 3910301217 1018910293<br/>
9311702400 2463242636 1018694167<br/>
9311702400 4797739673 1050709027</span></div>

# Sample Output

<div class="content"><span class="sampledata">618961590<br/>
28597316<br/>
1016219343<br/>
977847638<br/>
108994801<br/>
100559666<br/>
694084378<br/>
492868358<br/>
336126742<br/>
176095716</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

