
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">一个无向图，其中某些点是重要的。两人在该图上进行游戏，轮流操作。每次操作是指将某条边删去，该边必须与某个重要点连通，谁无法操作则输掉了游戏。</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-align: left"><span style="font-weight: bold; font-size: 12pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">Your Task</span><span style="font-weight: bold; font-size: 12pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">判断先手是否有必胜策略。</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行T表示数据组数</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每组数据，第一行n m分别表示点数、边数，点从1到n编号</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第二行p表示重要点的个数</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第三行p个数表示重要点的编号</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来m行每行三个数i j k表示点i与点j之间有k条边</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每组数据，在一行中输出答案，若先手必胜输出1否则输出0</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"> </span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-size: 10pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
<br/>
3 2<br/>
<br/>
1<br/>
<br/>
1<br/>
<br/>
1 2 1<br/>
<br/>
2 3 1<br/>
<br/>
2 1<br/>
<br/>
1<br/>
<br/>
1<br/>
<br/>
1 2 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

