
# Description

<div class="content"><div><span style="font-size: medium">    约翰的N(1≤N≤1,000,000,000)只奶牛要出发去探索牧场四周的土地．她们将沿着一条路走，一直走到三岔路口（可以认为所有的路口都是这样的）．这时候，这一群奶牛可能会分成两群，分别沿着接下来的两条路继续走．如果她们再次走到三岔路口，那么仍有可能继续分裂成两群继续走．    奶牛的分裂方式十分古怪：如果这一群奶牛可以精确地分成两部分，这两部分的牛数恰好相差K(1≤K≤1000)，那么在三岔路口牛群就会分裂．否则，牛群不会分裂，她们都将在这里待下去，平静地吃草．    请计算，最终将会有多少群奶牛在平静地吃草．</span></div></div>

# Input

<div class="content"><p><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">   </span><span style="font-size: 10.5pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">两个整数</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">N</span><span style="font-size: 10.5pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">K.</span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">最后的牛群数．</span></font></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 2<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
There are 6 cows and the difference in group sizes is 2.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
There are 3 final groups (with 2, 1, and 3 cows in them).<br/>
<br/>
   6<br/>
  / \<br/>
 2   4<br/>
    / \<br/>
   1   3<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">   6</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">只奶牛先分成</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">2</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">只和</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">4</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">只．</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">4</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">只奶牛又分成</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">1</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">只和</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">3</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">只．最后有三群奶牛．</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

