
# Description

<div class="content"><div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">给出N个数，要求把其中重复的去掉，只保留第一次出现的数。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">例如，给出的数为1 2 18 3 3 19 2 3 6 5 4，其中2和3有重复，去除后的结果为1 2 18 3 19 6 5 4。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">输入第一行为正整数T，表示有T组数据。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">接下来每组数据包括两行，第一行为正整数N，表示有N个数。第二行为要去重的N个正整数。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="layout-grid-mode: char"> </div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">对于每组数据，输出一行，为去重后剩下的数字，数字之间用一个空格隔开。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
11<br/>
1 2 18 3 3 19 2 3 6 5 4<br/>
6<br/>
1 2 3 4 5 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2 18 3 19 6 5 4<br/>
1 2 3 4 5 6<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">对于</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">30%</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">的数据，</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">1 &lt;= N &lt;= 100</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">，给出的数不大于</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">100</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">，均为非负整数；</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt"><o:p></o:p></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">对于</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">50%</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">的数据，</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">1 &lt;= N &lt;= 10000</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">，给出的数不大于</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">10000</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">，均为非负整数；</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt"><o:p></o:p></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">对于</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">100%</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">的数据，</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">1 &lt;= N &lt;= 50000</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">，给出的数在</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">32</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">位有符号整数范围内。</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">提示</span></b><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">:<o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">由于数据量很大，使用</span><span lang="EN-US"><font face="Times New Roman">C++</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的同学请使用</span><span lang="EN-US"><font face="Times New Roman">scanf</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">printf</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">来进行输入输出操作，以免浪费不必要的时间。</span></font></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

