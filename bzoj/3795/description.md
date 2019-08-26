
# Description

<div class="content"><div>魏总，也就是DP魏又开始刷DP了。一共有n道题，第i道题魏总原本需要u[i]秒的时间。不过，为了表达对这些水题的藐视，魏总决定先睡k秒再开始刷题。魏总并不清楚自己会睡多久，只知道k是不超过m的正实数。并且魏总还忘了这节课有多长，只记得这节课的长度T（单位：秒）是在L到R之间。（魏总是从开始上课的时候开始睡的）睡醒后，魏总神奇地发现自己做每道题所需的时间变成了原来的k倍。不过DP魏就是DP魏，他可以同时做这n道DP，互不影响。</div>
<div></div>
<div>魏总本想虐场，但他很快发现自己低估这些题了。于是他决定将题分为HARD和EASY。对于每道HARD的题，他希望能最晚在下课后late[i]秒内完成，而对于EASY的题，他希望在下课前rest[i]秒之前完成。</div>
<div></div>
<div>求魏总达到目标的概率。</div>
<div></div>
<p class="MsoNormal" align="center" style="text-align:center"></p></div>

# Input

<div class="content"><div>第一行，一个整数n</div>
<div></div>
<div>第二行，三个实数m，L，R</div>
<div></div>
<div>第三行，n个整数，第i个为u[i]</div>
<div></div>
<div>就下来n行，每行一个字符串和一个整数，字符串为”HARD”或”EASY”，整数为对应的late[i]或rest[i]。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一行，魏总达到目标的概率，保留4位小数。</div>
<div>
<div></div>
<div></div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1.50 0.630 1.810<br/>
2 2 <br/>
EASY 1<br/>
EASY 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.0618</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据，0&lt;n&lt;=100000,0&lt;m&lt;100000,0&lt;L&lt;R&lt;100000,0&lt;late[i],rest[i]&lt;=100000。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

