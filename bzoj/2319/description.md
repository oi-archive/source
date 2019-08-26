
# Description

<div class="content"><div class="Section0" style="layout-grid:  15.6pt none">
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">黑白棋游戏是这样玩的：首先<font face="Times New Roman">GEN</font><font face="宋体">随机生成</font><font face="Times New Roman">N</font><font face="宋体">个</font><font face="Times New Roman">01</font><font face="宋体">序列，</font><font face="Times New Roman">0</font><font face="宋体">表示白棋，</font><font face="Times New Roman">1</font><font face="宋体">表示黑棋。接着两个人轮流按如下规则取棋：首先选取一个非空的</font><font face="Times New Roman">01</font><font face="宋体">序列，然后从该序列的左边开始连续取若干个棋子，这些被取的棋子中最多只能有一个黑棋，且该黑棋必需恰好是连续取的最后一个棋子，比如当前的序列为</font><font face="Times New Roman">001001</font><font face="宋体">，则可以取走的棋子有三种情况，分别为：</font><font face="Times New Roman">0</font><font face="宋体">，</font><font face="Times New Roman">00</font><font face="宋体">，</font><font face="Times New Roman">001</font><font face="宋体">。如果某人没有棋子可取了，则他负。</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">你通过特殊手段得到了<font face="Times New Roman">GEN</font><font face="宋体">生成时每一行生成的白棋数目和黑棋数目，由于不知道它们的排列情况，你做不到必胜，你只想知道你先手获胜的概率有多大</font><font face="Times New Roman">(</font><font face="宋体">假设你和你的对手都无限聪明</font><font face="Times New Roman">)</font><font face="宋体">。</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
</div>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-weight: bold; font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span> </p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行一个数<font face="Times New Roman">N</font><font face="宋体">。</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第二行<font face="Times New Roman">N</font><font face="宋体">个数，第</font><font face="Times New Roman">i</font><font face="宋体">个数表示第</font><font face="Times New Roman">i</font><font face="宋体">个</font><font face="Times New Roman">01</font><font face="宋体">序列中黑棋的个数。</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第三行<font face="Times New Roman">N</font><font face="宋体">个数，第</font><font face="Times New Roman">i</font><font face="宋体">个数表示第</font><font face="Times New Roman">i</font><font face="宋体">个</font><font face="Times New Roman">01</font><font face="宋体">序列中白棋的个数。</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">仅一行，一个保留<font face="Times New Roman">6</font><font face="宋体">为小数的的实数表示先手获胜的概率。</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
<br/>
1<br/>
<br/>
1<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.500000<br/>
</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p><br/><br/>
样例解释</p><br/>
<p>若生成序列为01，则先手必胜；若生成序列为10，则后手必胜。</p><br/>
<p>两种情况出现的概率均为0.5，故先手获胜的概率为0.5。</p><br/>
<p>0&lt;=每行的黑棋个数&lt;=100</p><br/>
<p>0&lt;=每行的白棋个数&lt;=100</p><br/>
<p>1&lt;=N&lt;=50</p><br/>
<p>数据保证每个序列至少有一个棋子。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

