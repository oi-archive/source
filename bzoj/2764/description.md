
# Description

<div class="content"><div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">在生物课中我们学过，碱基组成了DNA（脱氧核糖核酸），他们分别可以用大写字母A,C,T,G表示，其中A总与T配对，C总与G配对。两个碱基序列能相互匹配，当且仅当它们等长，并且任意相同位置的碱基都是能相互配对的。例如ACGTC能且仅能与TGCAG配对。一个相对短的碱基序列能通过往该序列中任意位置补足碱基来与一个相对长的碱基序列配对。补全碱基的位置、数量不同，都将视为不同的补全方案。现在有两串碱基序列S和T，分别有n和m个碱基(n&gt;=m)，问一共有多少种补全方案。</span></div>
<div style="layout-grid-mode: char; text-indent: 23.65pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">数据包括三行。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">第一行有两个整数n，m，表示碱基序列的长度。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">第二行包含n个字符，表示碱基序列S。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">第三行包含m个字符，表示碱基序列T。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">两个碱基序列的字符种类只有A,C,G,T这4个大写字母。</span></div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="layout-grid-mode: char"> </div>
<div style="layout-grid-mode: char; text-indent: 21pt"><span style="font-size: medium">答案只包含一行，表示补全方案的个数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">10 3<br/>
CTAGTAGAAG<br/>
TCC<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt; layout-grid-mode: char"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">样例解释</span></b><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">:<o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span lang="EN-US"><font face="Times New Roman">TCC</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">种补全方案（括号中字符为补全的碱基）</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><span lang="EN-US"><font face="Times New Roman" size="3">(GA)TC(AT)C(TTC)</font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><span lang="EN-US"><font face="Times New Roman" size="3">(GA)TC(ATCTT)C</font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><span lang="EN-US"><font face="Times New Roman" size="3">(GA)T(CAT)C(TT)C</font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><span lang="EN-US"><font face="Times New Roman" size="3">(GATCA)TC(TT)C</font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><o:p><font face="Times New Roman" size="3"> </font></o:p></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; layout-grid-mode: char"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.5pt">数据范围</span></b><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.5pt">:<o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span lang="EN-US"><font face="Times New Roman">30%</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">数据</span><span lang="EN-US"><font face="Times New Roman">n&lt;=1000,m&lt;=2</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span lang="EN-US"><font face="Times New Roman">50%</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">数据</span><span lang="EN-US"><font face="Times New Roman">n&lt;=1000,m&lt;=4</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt 21pt; mso-para-margin-left: 2.0gd"><font size="3"><span lang="EN-US"><font face="Times New Roman">100%</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">数据</span><span lang="EN-US"><font face="Times New Roman">n&lt;=2000,m&lt;=n</font></span></font></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

