
# Description

<div class="content"><div><span style="font-size: medium">给定带权无向图，求出一颗方差最小的生成树，方差的定义如下：</span></div>
<div><span style="font-size: medium"><img height="142" width="309" alt="" src="source/bzoj/3080/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwMy8xMSg1KS5qcGc=.jpg"/></span></div></div>

# Input

<div class="content"><p><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">
</span></font></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">多组测试数据。第一行为</span><span lang="EN-US"><font face="Calibri">N,M</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，依次是点数和边数。接下来</span><span lang="EN-US"><font face="Calibri">M</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行，每行三个整数</span><span lang="EN-US"><font face="Calibri">U,V,W</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，代表连接</span><span lang="EN-US"><font face="Calibri">U,V</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的边，和权值</span><span lang="EN-US"><font face="Calibri">W</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。保证图连通。</span><span lang="EN-US"><font face="Calibri">(1&lt;=U,V&lt;=N&lt;=50,N-1&lt;=M&lt;=1000,0&lt;=W&lt;=50) </font></span></font></font></p><font size="3">
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><o:p><font face="Calibri" size="3"> </font></o:p></span></p>
</font><p></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><o:p><font face="Calibri" size="3"> </font></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium">输出最小方差，四舍五入到<span lang="EN-US"><font face="Calibri">0.01</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。输出格式按照样例。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">N=m=0</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">标志着测试文件的结束。</span></font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
1 2 1<br/>
2 3 2<br/>
3 4 2<br/>
4 1 1<br/>
2 4 3<br/>
4 6<br/>
1 2 1<br/>
2 3 2<br/>
3 4 3<br/>
4 1 1<br/>
2 4 3<br/>
1 3 3<br/>
0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 0.22<br/>
Case 2: 0.00<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

