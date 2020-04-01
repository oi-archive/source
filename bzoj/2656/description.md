
# Description

<div class="content"><p><span style="font-size: 10.5pt">   </span><span style="font-size: 12pt">小白和小蓝在一起上数学课，下课后老师留了一道作业，求下面这个数列的通项公式：</span></p>
<p><span style="font-size: 12pt"><img height="182" alt="" width="288" src="/source/bzoj/2656/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwNC8xLmpwZw==.jpg"/></span></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 150%"><span lang="EN-US"><span style="mso-spacerun: yes"><font face="Calibri">   </font></span></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">小白作为一个数学爱好者，很快就计算出了这个数列的通项公式。于是，小白告诉小蓝自己已经做出来了，但为了防止小蓝抄作业，小白并不想把公式公布出来。于是小白为了向小蓝证明自己的确做出来了此题以达到其炫耀的目的，想出了一个绝妙的方法：即让小蓝说一个正整数</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">N</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，小白则说出</span><span lang="EN-US" style="position: relative; top: 4pt; mso-text-raise: -4.0pt"><v:shape id="_x0000_i1025" type="#_x0000_t75" style="width: 12.75pt; height: 15.75pt"><font face="Calibri"> <v:imagedata chromakey="white" o:title="" src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image001.png"></v:imagedata></font></v:shape></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的值，如果当</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">N</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">很大时小白仍能很快的说出正确答案，这就说明小白的确得到了公式。但这个方法有一个很大的漏洞：小蓝自己不会做，没法验证小白的答案是否正确。作为小蓝的好友，你能帮帮小蓝吗？</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><o:p></o:p></span></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 150%"><span lang="EN-US"><span style="mso-spacerun: yes"><font face="Calibri">      </font></span></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">输入文件第一行有且只有一个正整数</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">T</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，表示测试数据的组数。</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 150%"><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><span style="mso-spacerun: yes"><font face="Calibri">     </font></span></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">2</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">～</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">T+1</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行，每行一个<u>非负整数</u></span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">N</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 150%"><span lang="EN-US"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 150%"><span lang="EN-US"><span style="mso-spacerun: yes"><font face="Calibri">      </font></span></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">输出文件共包含</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">T</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行。</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 30pt; line-height: 150%; mso-char-indent-count: 2.5"><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">i</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行应包含一个<u>不含多余前缀</u></span><u><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">0</font></span></u><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的数，它的值应等于</span><span lang="EN-US" style="position: relative; top: 4pt; mso-text-raise: -4.0pt">An</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">(n</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">为输入数据中第</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">i+1</font></span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行被读入的整数</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">)<o:p></o:p></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 150%"><span style="font-size: 14pt; line-height: 150%; font-family: 宋体; mso-bidi-font-size: 11.0pt; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">【样例输入】</span><span lang="EN-US" style="font-size: 14pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; line-height: 150%"><span lang="EN-US"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">      3<br/>
<br/>
     1<br/>
<br/>
     3<br/>
<br/>
     10<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
3<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 12pt; line-height: 150%; mso-char-indent-count: 1.0"><span lang="EN-US" style="font-size: 12pt; line-height: 150%; mso-bidi-font-size: 11.0pt"><font face="Calibri">T&lt;=20,N&lt;=10^100<o:p></o:p></font></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

