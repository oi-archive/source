
# Description

<div class="content"><p><span style="font-size: medium"><img alt="" width="917" height="227" src="source/bzoj/3341/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8xMS5qcGc=.jpg"/></span></p>
<p><span style="font-size: medium"><img alt="" width="920" height="382" src="source/bzoj/3341/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMi5qcGc=.jpg"/></span></p>
<p><span style="font-size: medium"><img alt="" width="914" height="240" src="source/bzoj/3341/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8zMy5qcGc=.jpg"/></span></p>
<p></p>
<p><span style="font-size: medium"><span style="widows: 2; text-transform: none; text-indent: 0px; display: inline !important; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; float: none; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px">琪琪在大海上搜索涛涛，琪琪把大海分为2500*2500的网格，现在琪琪拥有N条小帆船，她可以在船之间移动，由于风向的原因，她只能从一条船移动到位于这条船严格左上方或严格右下方的船。对于</span><br style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"/>
<br style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"/>
<span style="widows: 2; text-transform: none; text-indent: 0px; display: inline !important; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; float: none; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px">每条帆船，琪琪想要知道从这条船跳到其他各条船的最小跳转次数和。</span><br style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"/>
<br style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"/>
</span></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="text-align: left; line-height: 13.5pt; margin: 7.5pt -1.5pt 0pt 0cm; mso-line-height-rule: exactly; tab-stops: 191.75pt 453.65pt; mso-layout-grid-align: none"><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Trebuchet MS&#34;; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt">The first line of input contains an integer <i style="mso-bidi-font-style: normal"><span style="mso-tab-count: 1">  </span>N</i> (3 ≤ <i style="mso-bidi-font-style: normal">N</i> ≤ 250 000), the number of islands. The following <i style="mso-bidi-font-style: normal"><span style="mso-tab-count: 1">  </span>N</i> lines </span></span><span lang="EN-US" style="font-family: &#34;Trebuchet MS&#34;; color: black; font-size: 10pt; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="line-height: 13pt; margin: 0cm 16.7pt 0pt 0cm; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Trebuchet MS&#34;; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt">contain the locations of the islands. Each location is a pair of integers between 1 and 2500 (inclusive), the row and column numbers, respectively. </span></span><span lang="EN-US" style="font-family: &#34;Trebuchet MS&#34;; color: black; font-size: 10pt; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p><br style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"/>
<span style="widows: 2; text-transform: none; text-indent: 0px; display: inline !important; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; float: none; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px">第一行包含一个数N，表示帆船的个数。</span><br style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"/>
<span style="widows: 2; text-transform: none; text-indent: 0px; display: inline !important; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; float: none; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px">接下来的N行，每行包含一对数(x,y)，表示帆船的位置</span></p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="text-align: left; line-height: 13.5pt; margin: 7.5pt -1.5pt 0pt 0cm; mso-line-height-rule: exactly; tab-stops: 123.6pt; mso-layout-grid-align: none"><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Trebuchet MS&#34;; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt">The output should contain <i style="mso-bidi-font-style: normal"><span style="mso-tab-count: 1">  </span>N</i> lines. For each island, in the same order they were given in the input, output </span></span><span lang="EN-US" style="font-family: &#34;Trebuchet MS&#34;; color: black; font-size: 10pt; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="text-align: left; line-height: 13.5pt; margin: 0cm -1.5pt 0pt 0cm; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Trebuchet MS&#34;; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt">the sum of sailing distances from all other islands on a single line. </span></span><span lang="EN-US" style="font-family: &#34;Trebuchet MS&#34;; color: black; font-size: 10pt; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p><br style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"/>
<span style="widows: 2; text-transform: none; text-indent: 0px; display: inline !important; font: 14px/23px Helvetica, &#39;Microsoft Yahei&#39;, verdana; white-space: normal; orphans: 2; float: none; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px">输出需要包含N行，表示琪琪想要知道的答案。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 <br/>
1  7<br/>
7  5<br/>
4  5<br/>
4  8<br/>
6  6<br/>
6  1<br/>
2  3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">16 <br/>
11 <br/>
12 <br/>
11 <br/>
12 <br/>
16 <br/>
8 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

