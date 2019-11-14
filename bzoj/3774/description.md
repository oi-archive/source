
# Description

<div class="content"><p class="MsoNormal" align="center" style="text-align:center"></p>
<p class="MsoNormal" style="text-align: left;">小N手上有一个N*M的方格图，控制某一个点要付出Aij的代价，然后某个点如果被控制了，或者他周围的所有点(上下左右)都被控制了，那么他就算是被选择了的。一个点如果被选择了，那么可以得到Bij的回报，现在请你帮小N选一个最优的方案，使得回报-代价尽可能大。</p>
<p class="MsoNormal" style="text-indent:21.0pt"></p>
<p></p></div>

# Input

<div class="content"><div>
<p class="MsoNormal">第一行两个正整数N,M表示方格图的长与宽。</p>
<p class="MsoNormal">接下来N行每行M个整数Aij表示控制的代价。</p>
<p class="MsoNormal">接下来N行每行M个整数Bij表示选择的回报。</p>
</div>
<div>
<p></p>
</div></div>

# Output

<div class="content"><div>
<p class="MsoNormal">一个整数，表示最大的回报-代价(如果一个都不控制那么就是0)。</p>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 100 100<br/>
100 1 100<br/>
1 100 100<br/>
2 0 0<br/>
5 2 0<br/>
2 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">8</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;&lt;br /&gt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;&lt;br /&gt;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">对于</span><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:Calibri;&lt;br /&gt;
mso-fareast-font-family:宋体;mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:&lt;br /&gt;
1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:&lt;br /&gt;
AR-SA">100%</span><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;&lt;br /&gt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;&lt;br /&gt;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">的数据，</span><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:Calibri;&lt;br /&gt;
mso-fareast-font-family:宋体;mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:&lt;br /&gt;
1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:&lt;br /&gt;
AR-SA">N,M&lt;=50</span><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;&lt;br /&gt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;&lt;br /&gt;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">，</span><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:Calibri;&lt;br /&gt;
mso-fareast-font-family:宋体;mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:&lt;br /&gt;
1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:&lt;br /&gt;
AR-SA">Aij,Bij</span><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;&lt;br /&gt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;&lt;br /&gt;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">都是小于等于</span><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:Calibri;&lt;br /&gt;
mso-fareast-font-family:宋体;mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:&lt;br /&gt;
1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:&lt;br /&gt;
AR-SA">100</span><span style="font-size:10.5pt;mso-bidi-font-size:11.0pt;&lt;br /&gt;
font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;&lt;br /&gt;
mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">的正整数。</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

