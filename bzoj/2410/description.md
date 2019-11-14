
# Description

<div class="content"><div><span>         </span><span style="font-size: 12pt">一排</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">个格子，两人轮流用</span><span style="font-size: 12pt">k</span><span style="font-size: 12pt">种颜色给未染色的格子染色，要求每次染色后都不能有两个相邻的格子被染上了相同的颜色，你需要做的是判断一个已有部分格子被染色的初始局面是先手必胜还是后手必胜。</span></div>
<div> </div></div>

# Input

<div class="content"><div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">第一行一个数</span><span style="font-size: 12pt">time</span><span style="font-size: 12pt">，表示数据组数。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">接下来每组数据的第一行两个数</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">k</span><span style="font-size: 12pt">如题中所述，第二行</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">个</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">到</span><span style="font-size: 12pt">k</span><span style="font-size: 12pt">的整数，</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">表示格子未染色，否则表示该格子的颜色。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">保证初始局面没有两个相邻格子同色。</span></div>
<div> </div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">共</span><span style="font-size: 12pt">time</span><span style="font-size: 12pt">行，每行为“</span><span style="font-size: 12pt">y</span><span style="font-size: 12pt">”表示先手必胜，“</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">”表示后手必胜。</span></div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
NG.in                                       <br/>
       2                                          <br/>
       5 2                                         <br/>
       0 0 1 0 0<br/>
       5 1<br/>
       1 0 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">n<br/>
y<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第一局游戏中局面是对称的，所以只要先手可以给格子染色，后手就可以给其对称的格子染色，故后手必胜。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p><br/>
<p><span lang="EN-US" style="font-size: 12pt; font-family: Calibri; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA"><span style="mso-tab-count: 1">       </span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">第二局游戏中，先手给第</span><span lang="EN-US" style="font-size: 12pt; font-family: Calibri; mso-fareast-font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">4</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">个格子染色后，后手就不能染色了，故先手必胜。</span></p><br/>
<p><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA"><img height="130" width="521" alt="" src="/source/bzoj/2410/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwMy8xMSgzKS5qcGc=.jpg"/></span></p><br/>
<p><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA"><br/>
</span></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">对于</span><span lang="EN-US" style="font-size: 12pt"><font face="Calibri">100%</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的数据</span><span lang="EN-US" style="font-size: 12pt"><font face="Calibri"> 1</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US" style="font-size: 12pt"><font face="Calibri">n</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US" style="font-size: 12pt"><font face="Calibri">10<sup>5</sup></font><o:p></o:p></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

