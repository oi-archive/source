
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">这是一个双人游戏，一开始，nm个硬币，摆成n行m列的矩阵，双方轮流操作。</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">，将其中所有的硬币全部翻转（正变反，反变正），要求满足该连通块中存在一个硬币X，使得其它硬币均在X的左上方（正左方或正上方亦可），并且要求X是从反面向上翻成正面向上。谁无法操作则输掉游戏。</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-align: left"><span style="font-weight: bold; font-size: 12pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">Your Task</span><span style="font-weight: bold; font-size: 12pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">判断给定的状态是先手必胜还是先手必败。</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行T表示数据组数</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每组数据，第一行n m表示矩阵大小</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来n行m列表示初始的硬币情况，‘H</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">’</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">表示正面朝上，否则反面朝上，第一行第一个硬币是最左上角的硬币</span><span style="font-size: 10.5pt; vertical-align: sub; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每组数据，若给定矩阵为先手必胜则输出“-_-”，否则输出“=_=</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">”</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-size: 10pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
<br/>
2 3<br/>
<br/>
HHH<br/>
<br/>
HHH<br/>
<br/>
2 3<br/>
<br/>
HHH<br/>
<br/>
TTH<br/>
<br/>
2 1<br/>
<br/>
T<br/>
<br/>
H<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
=_=<br/>
<br/>
-_-<br/>
<br/>
-_-<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

