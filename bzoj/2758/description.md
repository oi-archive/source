
# Description

<div class="content"><div><span style="font-size: medium">一天Blinker醒来，发现自己成为了一个二维世界的点，而且被标记上了一个奇怪的值。 </span><span style="font-size: medium">这个世界是由N个边界互不相交（且不相切）的图形组成，这里图形仅包括圆和凸多</span><span style="font-size: medium">边形。每个图形还有一个权值。每次Blinker走进或走出某个图形时（相切时经过不算），</span><span style="font-size: medium">Blinker的标记值就会被异或上那个值。 </span><span style="font-size: medium">现在，我们记录了Blinker在这个世界的M天的信息。每天可能发生两种事情，一种是</span><span style="font-size: medium">某个图形的权值更改为某个值；另一种是Blinker从某个点走到另一个点。 </span><span style="font-size: medium">我们假设Blinker首次出发前的标记值为0，我们希望知道他每次到达目的地后的标记</span></div>
<div><span style="font-size: medium">值。 </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">输入的第一行包含2个数，N和M，分别表示这个世界的图形数和记录的天数。 </span><span style="font-size: medium">接下来有N行，每行表示一个图形。 </span><span style="font-size: medium">如果一行以字符C开头，表示这个图形是一个圆，后面紧跟着三个实数x, y, r和一个整</span><span style="font-size: medium">数v，分别表示圆的x坐标，y坐标和圆的半径以及该图形对应的值。 </span><span style="font-size: medium">如果一行以字符P开头，表示这个图形是凸多边形，后面紧跟着一个整数L，表示凸多</span></div>
<div><span style="font-size: medium">边形的点数，然后后面有L对实数x0,y0,x1,y1…，表示L个点的坐标，这一行最后一个数</span><span style="font-size: medium">是一个整数v，表示这个图形对应的值，保证凸多边形上的点按照顺时针给出。 </span><span style="font-size: medium">接下来有M行，每行表示一天的记录信息。 </span></div>
<div><span style="font-size: medium">如果一行以字符Q开头，表示这一天Blinker出行了，接下来有x0,y0,x1,y1四个实数，</span></div>
<div><span style="font-size: medium">分别表示出发点的坐标和目的地的坐标。 </span></div>
<div><span style="font-size: medium">如果一行以字符C开头，表示这一天某个图形的值改变了，接下来有两个i 和v，表示</span></div>
<div><span style="font-size: medium">输入中第i 个出现的图形的值变成v。 </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">对于Blinker的每个出行输出他到达目的地后的标记值，很显然这个值与Blinker的路径</span></div>
<div><span style="font-size: medium">无关。 </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 4 <br/>
C 0 0 2 1 <br/>
P 4 -1 -1 -1 1 1 1 1 -1 2 <br/>
Q -2 -2 2 2 <br/>
Q -1.5 0 0.0 0.0 <br/>
C 1 1005 <br/>
Q -1.5 0 0.0 0.0 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 <br/>
2 <br/>
0 </span></div>

# Hint

<div class="content"><p></p><p><img height="593" alt="" width="759" src="/source/bzoj/2758/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwNC8xMS5naWY=.gif"/></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">对于</span><span lang="EN-US"><font face="Calibri">30%</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的数据，保证：</span><span lang="EN-US"><font face="Calibri"> </font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">1&lt;=M&lt;=10.0</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，凸多边形的点数加上圆的个数小于等于</span><span lang="EN-US"><font face="Calibri">1000 </font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">剩余数据中，保证：</span><span lang="EN-US"><font face="Calibri"> </font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">存在一组无图形值变动的数据；</span><span lang="EN-US"><font face="Calibri"> </font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">存在一组无凸多边形的数据；</span><span lang="EN-US"><font face="Calibri"> </font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">对于</span><span lang="EN-US"><font face="Calibri">100%</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的数据，保证：</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">1&lt;=N&lt;=100000</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，</span><span lang="EN-US"><font face="Calibri">1&lt;=M&lt;=100000</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，单个凸多边形的点数小于等于</span><span lang="EN-US"><font face="Calibri">34</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。图形互不相交，且</span><span lang="EN-US"><font face="Calibri">Blinker</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的出发点和目的地不在图形的边界。</span></font></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

