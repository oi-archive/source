
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">初始在</span><span lang="EN-US"><font face="Calibri">(0, 0)</font></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">给你</span><span lang="EN-US"><font face="Calibri">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">个命令串</span><font face="Calibri"> </font><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">每个命令串包含若干命令</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">每个命令形式是</span><span lang="EN-US"><font face="Calibri"> GO LEFT RIGHT Fk</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">之一</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">GO </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">往前走</span><span lang="EN-US"><font face="Calibri">1</font></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">LEFT </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">左转</span><span lang="EN-US"><font face="Calibri">90</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">度</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">RIGHT </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">右转</span><span lang="EN-US"><font face="Calibri">90</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">度</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">Fk </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">执行第</span><span lang="EN-US"><font face="Calibri">k</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">个命令串</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">f1: GO F2 GO F2 GO F2</font></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">f2: F3 F3 F3 F3</font></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">f3: GO LEFT</font></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">命令轨迹如图</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri"><img height="132" alt="" width="330" src="/source/bzoj/2647/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMy8xMSgxKS5qcGc=.jpg"/></span></span></p></div>

# Input

<div class="content"><div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">第一行 N</span></div>
<div><span style="font-size: medium">接下来N行 每行先一个整数Ci表示命令数 接下来Ci个命令</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出曾经到达的最远的距离 如果到了无穷远 输出“Infinity”</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">Sample Input1<br/>
3<br/>
6 GO F2 GO F2 GO F2<br/>
4 F3 F3 F3 F3<br/>
2 GO LEFT<br/>
<br/>
Sample Output1<br/>
5<br/>
<br/>
Sample Input2<br/>
1<br/>
2 GO F1<br/>
<br/>
Sample Output2<br/>
<br/>
Infinity<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
HINT<br/><br/>
N&lt;=100<br/><br/>
Ci&lt;=100<br/><br/>
 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Kac">鸣谢Kac</a></p></div>

