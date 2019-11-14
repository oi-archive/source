
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">给</span><span lang="EN-US"><font face="Calibri">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">个抛物线</span><span lang="EN-US"><font face="Calibri">(</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">只会完整地存在在第一象限，不在第一象限的部分不需考虑，</span><font face="Calibri"> </font><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">如图</span><span lang="EN-US"><font face="Calibri">)</font></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">询问</span><span lang="EN-US"><font face="Calibri">M</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">次</span><font face="Calibri"> </font><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">每次询问第</span><span lang="EN-US"><font face="Calibri">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">到第</span><span lang="EN-US"><font face="Calibri">j</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">个抛物线在</span><span lang="EN-US"><font face="Calibri">[l, r]</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的</span><span lang="EN-US"><font face="Calibri">x</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">坐标区间上的最小值</span></font></p>
<p><img height="159" alt="" width="586" src="/source/bzoj/2646/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMy8xKDEyKS5qcGc=.jpg"/></p></div>

# Input

<div class="content"><div><span style="font-size: medium">
<div>所有输入均为整数</div>
<div>第一行 N</div>
<div>接下来N行 每行p, x, y 表示抛物线左边界的x坐标，顶点的x y坐标</div>
<div>接下来 M</div>
<div>接下来M行 每行i, j, l, r如题意所示</div>
</span></div>
<p></p></div>

# Output

<div class="content"><div><span style="font-size: medium">M行每行一个实数 表示第M次询问的答案 误差&lt;1e-4即可</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
10 30 10<br/>
20 30 30<br/>
4<br/>
1 2 0 11<br/>
1 2 20 25<br/>
1 2 25 35<br/>
1 2 45 100<br/>
 <br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
0.975<br/>
22.5<br/>
30.0<br/>
4.375<br/>
 </span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">1 </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> n </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> 50 000</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">0 </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> p &lt; x </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> 50 000,</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">0 &lt; y </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> 50</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">1 </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> m </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> 20 000</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">0 </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> l </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> r </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> 50 000</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">1 </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> a </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> b </font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">≤</span><span lang="EN-US"><font face="Calibri"> n</font></span></font></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Kac">鸣谢Kac</a></p></div>

