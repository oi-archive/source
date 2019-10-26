
# Description

<div class="content"><p><span style="font-size: medium">It&#39;s election time. The farm is partitioned into a 5x5 grid of cow locations, each of which holds either a Holstein (&#39;H&#39;) or Jersey (&#39;J&#39;) cow. The Jerseys want to create a voting district of 7 contiguous (vertically or horizontally) cow locations such that the Jerseys outnumber the Holsteins. How many ways can this be done for the supplied grid? </span></p>
<p><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA"> </span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">农场被划分为</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">5x5</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">的格子，每个格子中都有一头奶牛，并且只有荷斯坦</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">(</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">标记为</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">H)</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">和杰尔西（标记为</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">J</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">）两个品种．如果一头奶牛在另一头上下左右四个格子中的任一格里，我们说它们相连．</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">    </span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">奶牛要大选了．现在有一只杰尔西奶牛们想选择</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">7</span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">头相连的奶牛，划成一个竞选区，使得其中它们品种的奶牛比荷斯坦的多．</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">  </span><span style="font-size: 10.5pt; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">要求你编写一个程序求出方案总数．</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Lines 1..5: Each of the five lines contains five characters per line, each &#39;H&#39; or &#39;J&#39;. No spaces are present. </span></p>
<div><span style="font-size: medium">    5行，输入农场的情况．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The number of distinct districts of 7 connected cows such that the Jerseys outnumber the Holsteins in the district. </span></p>
<div><span style="font-size: medium">    输出划区方案总数．</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">HHHHH<br/>
JHJHJ<br/>
HHHHH<br/>
HJHHJ<br/>
HHHHH<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="217" alt="" width="234" src="/source/bzoj/1675/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS80NCgzKS5qcGc=.jpg"/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

