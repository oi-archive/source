
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 12pt">TK</span><span style="font-size: 12pt">在虐题的同时，也喜欢玩游戏。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">现在，有这样的一个游戏，规则是这样的：</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">先随机给出一个数字</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">，然后你在操场上把</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">到</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">的所有数字写成一排，就像这样：</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">123456789101112131415….</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">接着你在每个数字前面添上加减号，每逢排在奇数位上的数字，就写上加号；每逢排在偶数位上的数字，就写上减号。恩</span><span style="font-size: 12pt">…</span><span style="font-size: 12pt">最后你得到一个超级长的式子。并且可以算出这个式子的结果。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">TK</span><span style="font-size: 12pt">觉得这个游戏很有意思，于是他没日没夜地玩啊玩啊玩啊</span><span style="font-size: 12pt">…</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">或许你觉得这个游戏没有意思</span><span style="font-size: 12pt">…</span><span style="font-size: 12pt">恩</span><span style="font-size: 12pt">…</span><span style="font-size: 12pt">但是，如果你是</span><span style="font-size: 12pt">TK</span><span style="font-size: 12pt">，对于给定的</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">，你能够算出来最后的结果应该是多少么？</span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 12pt">多组数据。每个测试点的数据组数不超过</span><span style="font-size: 12pt">1000</span><span style="font-size: 12pt">组。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">每一行仅一个正整数</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">。保证没有多余的什么奇怪的字符。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">每个测试点的数据最后一行一定是数字</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">。代表这个测试点的结束。</span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">对于每组数据，输出相应的结果。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">12<br/>
0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><b style="mso-bidi-font-weight: normal"><span style="font-size: 15pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">【样例说明】</span></b><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-size: 15pt; mso-fareast-font-family: 华文细黑"><o:p></o:p></span></b></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><span style="mso-tab-count: 1"><font face="Calibri">         </font></span></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">对于</span></font><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">12</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">这个数字：</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><o:p></o:p></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 20.25pt"><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">写成一行就是：</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">123456789101112<o:p></o:p></font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 20.25pt"><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">那么，形成的表达式就是：</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">+1-2+3-4+5-6+7-8+9-1+0-1+1-1+2=5.<o:p></o:p></font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><b style="mso-bidi-font-weight: normal"><span style="font-size: 15pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">【数据范围】</span></b><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-size: 15pt; mso-fareast-font-family: 华文细黑"><o:p></o:p></span></b></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><span style="mso-tab-count: 1"><font face="Calibri">         </font></span></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">对于</span></font><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">10%</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的数据：保证第一行是数字</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">100</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，第二行是</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">0.<o:p></o:p></font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><span style="mso-tab-count: 1"><font face="Calibri">       </font></span></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">对于</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">20%</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的数据：保证数据组数不超过</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">10</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">N</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">不超过</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">10^5<o:p></o:p></font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><span style="mso-tab-count: 1"><font face="Calibri">       </font></span></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">对于</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">50%</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的数据：保证数据组数不超过</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">20</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">N</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">不超过</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">10^10<o:p></o:p></font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><span style="mso-tab-count: 1"><font face="Calibri">       </font></span></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">对于</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">100%</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的数据：保证数据组数不超过</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">100</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">N</font></span><span style="font-size: 12pt; font-family: 华文细黑; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">不超过</span><span lang="EN-US" style="font-size: 12pt; mso-fareast-font-family: 华文细黑"><font face="Calibri">10^15<o:p></o:p></font></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

