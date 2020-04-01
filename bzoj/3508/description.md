
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 36pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">xx<font face="宋体">作为信息学界的大神，拥有众多的粉丝。为了感谢众粉丝的爱戴，</font><font face="Times New Roman">xx</font><font face="宋体">决定举办一场晚会。为了气派，</font><font face="Times New Roman">xx</font><font face="宋体">租了一个巨大的灯屏，这个灯屏有</font><font face="Times New Roman">m</font><font face="宋体">行，每行有</font><font face="Times New Roman">n</font><font face="宋体">个小灯泡。对于每一行灯，有</font><font face="Times New Roman">L</font><font face="宋体">种操作方法，</font></span><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第i种表示你能将任意长度恰为Ai的连续一段灯泡的状态取反（灭变亮，亮变灭）。</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">现</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">对于每一行</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">给定K个点，要求这K个点发光，其余点必须保持熄灭状态</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">。求每一行达到目标状态的最小操作数。</span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">第一行一个数m，表示LED屏的行数。</span></span><span style="font-size: 10.5pt; font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">对于LED屏的每一行：</span></span><span style="font-size: 10.5pt; font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">第一行为n,k,</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">L</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">，意义见上。</span></span><span style="font-size: 10.5pt; font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">第二行为k个数，表示要求发光的k个点。</span></span><span style="font-size: 10.5pt; font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">第三行为</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">L</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">个数，表示</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">L</span><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">种操作方式。</span></span><span style="font-size: 10.5pt; font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;">对于LED屏的每一行：如果无法达到目标状态，输出-1，否则输出最少次数。</span></span><span style="font-size: 10.5pt; font-family: &#39;微软雅黑&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
10 8 2<br/>
1 2 3 5 6 7 8 9<br/>
3 5<br/>
3 2 1<br/>
1 2<br/>
3<br/>
<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
2<br/>
-1<br/>
<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
对于100%的数据，T≤10，N≤10000，K≤10,L≤100,1≤A_i≤N。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By zjwst960422">By zjwst960422</a></p></div>

