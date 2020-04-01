
# Description

<div class="content"><p style="margin: 0cm 0cm 18pt; vertical-align: baseline; line-height: 18pt"><font size="3"><span style="color: #333333; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">有</font></span><span lang="EN-US" style="color: #333333; font-family: &#34;Times New Roman&#34;">n</span><span style="color: #333333; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">个阵地，已知我方在每个阵地上的士兵数，若我方士兵不为</font></span><span lang="EN-US" style="color: #333333; font-family: &#34;Times New Roman&#34;">0</span><span style="color: #333333; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">则表示该阵地由我方占领，否则为对方占领。某些阵地之间有通道，我们认为士兵可以经过</font></span><span lang="EN-US" style="color: #333333; font-family: &#34;Times New Roman&#34;">1</span><span style="color: #333333; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">单位时间从</font></span><span lang="EN-US" style="color: #333333; font-family: &#34;Times New Roman&#34;">1</span><font face="宋体"><span style="color: #333333; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">个阵地移动到相邻（有通道相连）的阵地。对于一个阵地，如果其相邻的阵地中有非我方阵地，则表示其受到威胁，该阵地中我方人数。</span><span lang="EN-US" style="color: #333333; font-family: &#34;Times New Roman&#34;"><o:p></o:p></span></font></font></p>
<p style="margin: 0cm 0cm 18pt; vertical-align: baseline; line-height: 18pt"><font size="3"><span style="color: #333333; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">现在求：对我方士兵进行一次</font></span><span lang="EN-US" style="color: #333333; font-family: &#34;Times New Roman&#34;">1</span><span style="color: #333333; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">个单位的移动（调动），在保证我方不丢失阵地的情况下（即我方每个阵地上的人数不为</font></span><span lang="EN-US" style="color: #333333; font-family: &#34;Times New Roman&#34;">0</span><span style="color: #333333; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">），使得我方所有受到威胁的阵地中人数最少的阵地的人数尽可能多。</font></span></font><span lang="EN-US" style="color: #333333; font-family: &#34;Times New Roman&#34;"><o:p></o:p></span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">On the first line a positive integer: the number of test cases, at most 100. After that per test case: </span></p>
<ul>
    <li><span style="font-size: medium">One line with an integer <var>n</var> (1 ≤ <var>n</var> ≤ 100): the number of regions. </span></li>
    <li><span style="font-size: medium">One line with <var>n</var> integers <var>a<sub>i</sub></var> (0 ≤ <var>a<sub>i</sub></var> ≤ 100): the number of your armies on each region. A number 0 indicates that a region is controlled by your opponents, while a positive number indicates that it is under your control. </span></li>
    <li><span style="font-size: medium"><var>n</var> lines with <var>n</var> characters, where each character is either &#39;Y&#39; or &#39;N&#39;. The <var>i</var>-th character of the <var>j</var>-th line is &#39;Y&#39; if regions <var>i</var> and <var>j</var> border, and &#39;N&#39; otherwise. This relationship is symmetric and the <var>i</var>-th character of the <var>i</var>-th line will always be &#39;N&#39;. </span></li>
</ul>
<p><span style="font-size: medium">In every test case, you control at least one region, and your opponents control at least one region. Furthermore, at least one of your regions borders at least one of your opponents&#39; regions. </span></p>
<div></div></div>

# Output

<div class="content"><div>
<p><span style="font-size: medium">Per test case: </span></p>
<ul>
    <li><span style="font-size: medium">One line with an integer: the maximum number of armies on your weakest border region after one turn of moving</span></li>
</ul>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
3 <br/>
1 1 0 <br/>
NYN <br/>
YNY <br/>
NYN <br/>
7 <br/>
7 3 3 2 0 0 5 <br/>
NYNNNNN <br/>
YNYYNNN <br/>
NYNYYNN <br/>
NYYNYNN <br/>
NNYYNNN <br/>
NNNNNNY <br/>
NNNNNYN</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

