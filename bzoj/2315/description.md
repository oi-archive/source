
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: left"></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">黑白游戏是一个双人游戏，黑方和白方轮流操作。一开始有四座塔，每座塔由一列若干个黑色或白色的砖块搭成（可能为空）。轮到一方操作时，该方可以选择某座塔中的某个与其颜色对应的砖块，将该砖块及其上面的砖块全部移去。若某方无法操作，则该方输掉游戏。</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于一个状态，若白方无论先手还是后手均必胜则称其为W状态。比如如图四座塔，考虑白方先手，黑方前两步必定操作两个不同的塔的第2个黑色砖块，假设是第一座与第二座，则白方只需操作第三座塔的两个白色砖块，然后剩下5个白色砖块与4个黑色砖块，双方轮流取，显然白方必胜。若白方后手同理易知其必胜。故该状态是一个W状态。</span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><img height="239" width="322" alt="" src="/source/bzoj/2315/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNS8yMzE1LmpwZw==.jpg"/></span></p>
<p></p><p></p>
<p></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-align: left"><span style="font-weight: bold; font-size: 12pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">Your Task</span><span style="font-weight: bold; font-size: 12pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">给定三座塔与另外三座塔，请判断是否对于任意的一座塔C，若状态是W状态则状态也是W状态。</span><span style="font-size: 10.5pt; vertical-align: sub; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行T表示数据组数</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每组数据，第一行n1 n2 n3表示三座塔的高度</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来一行n1个字符，从下到上描述，B表示黑色砖块，W表示白色砖块</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来两行类似的描述与</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来类似的四行描述</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">注意，当n=0时对应行是一个空行</span><span style="font-size: 10.5pt; vertical-align: sub; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--><!--EndFragment--></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; layout-grid-mode: char; text-indent: 21pt; text-align: left"><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每组数据，如果前面的条件满足则输出“Yes”否则输出“No”</span><span style="font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
<br/>
3 3 1<br/>
<br/>
W B B<br/>
<br/>
W B W<br/>
<br/>
B<br/>
<br/>
3 3 3<br/>
<br/>
B W W<br/>
<br/>
B W W<br/>
<br/>
W B B<br/>
<br/>
3 3 2<br/>
<br/>
W B B<br/>
<br/>
W B W<br/>
<br/>
B B<br/>
<br/>
3 3 3<br/>
<br/>
B W W<br/>
<br/>
B W W<br/>
<br/>
W B B<br/>
<br/>
1 0 0<br/>
<br/>
W<br/>
<br/>
<br/>
<br/>
0 0 1<br/>
<br/>
<br/>
<br/>
W<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No<br/>
Yes<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
100%：T≤100，0≤n≤50<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

