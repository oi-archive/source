
# Description

<div class="content"><p><img height="476" width="1067" alt="" src="/source/bzoj/1608/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMigxNSkuanBn.jpg"/></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行是两个整数</span><span lang="EN-US"><font face="Times New Roman">R</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">C</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，用空格隔开．从第</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行到第</span><span lang="EN-US"><font face="Times New Roman">RxC+I</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，每一行包含</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个数字和</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个代表边界的符号（可以是字母或数字</span><span lang="EN-US"><font face="Times New Roman">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">）．</span></font></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输出换位及旋转后的拼图．共</span><span lang="EN-US"><font face="Times New Roman">RxC</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行，每行第一个数字代表第几块拼图块，后面四个字符，按顺序代表</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个边界字母（边界线仍用</span><span lang="EN-US"><font face="Times New Roman">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">表示）．</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">答案可能有多组，输出一组即可．</span></font></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
1 c d 0 0<br/>
2 0 d b 0<br/>
3 c 0 d a<br/>
4 b a b 0<br/>
5 d 0 0 e<br/>
6 0 0 b e<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Describes the input puzzle although with some of the pieces rotated<br/>
compared to the sample solution.<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 0 c d 0<br/>
3 0 d a c<br/>
5 0 0 e d<br/>
2 d b 0 0<br/>
4 a b 0 b<br/>
6 e 0 0 b<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
As shown in the diagram in the task text. Other solutions (like<br/>
reflections) are possible; a grading program will check your answer.<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>请不要提交!</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

