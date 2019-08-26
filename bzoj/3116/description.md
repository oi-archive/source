
# Description

<div class="content"><div><span style="font-size: medium">二维平面上的山脉由一系列顶点确定：(x1,y1),(x2,y2)...(xn,yn)。相邻的两个顶点之间由线段相连（保证xi严格递增），这样就构成了一座连绵的山脉，每个点的y值代表了该点的高度。如下图所示：</span></div>
<div></div>
<div><span style="font-size: medium"><img height="222" alt="" width="567" src="source/bzoj/3116/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNC8xKDEpLmpwZw==.jpg"/></span></div>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">我们定义山脉的内部为顶点之间的折线与</span><span lang="EN-US"><font face="Calibri">x</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">轴的所夹部分（不包括顶点之间的折线）。如果顶点</span><span lang="EN-US"><font face="Calibri">A</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">与顶点</span><span lang="EN-US"><font face="Calibri">B</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">之间的连线段没有穿过山脉的内部，则我们称顶点</span><span lang="EN-US"><font face="Calibri">A</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">能看见顶点</span><span lang="EN-US"><font face="Calibri">B</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">（或</span><span lang="EN-US"><font face="Calibri">B</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">能看见</span><span lang="EN-US"><font face="Calibri">A</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">）。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Calibri"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">现在</span><span lang="EN-US"><font face="Calibri">pty</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">从某个顶点出发，想要登到山脉的顶峰（最高点），他只能在顶点之间的折线上行走。经过思考，他将采取如下的一种登山方式：</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">、站在出发点，向左右看去，如果此时能够看到的最高山峰在左侧，则向左侧走去，否则向右侧走去。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">、在行走的同时，</span><span lang="EN-US"><font face="Calibri">pty</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">仍然观察着此时左右的最高山峰，一旦发现一座比之前看到的都要高的山峰，他将向此时的最高峰走去。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">、如果存在某个时刻，</span><span lang="EN-US"><font face="Calibri">pty</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">所站立的位置比左右能看到的最高峰都要高，则他到达了山脉的顶峰，此时他的爬山过程结束。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Calibri"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">pty</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">想知道，采取如上的策略，从每个顶点出发，到达最高点的路程分别是多少？（平面中两点的距离等于它们之间连线段的长度）</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Calibri"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第一行一个整数</span><span lang="EN-US"><font face="Calibri">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，表示山脉顶点个数。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">接下来</span><span lang="EN-US"><font face="Calibri">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行，第</span><span lang="EN-US"><font face="Calibri">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行两个整数</span><span lang="EN-US"><font face="Calibri">xi,yi</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，表示第</span><span lang="EN-US"><font face="Calibri">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">个顶点的坐标。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">保证</span><span lang="EN-US"><font face="Calibri">xi</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">严格递增，</span><span lang="EN-US"><font face="Calibri">yi</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">互不相同（</span><span lang="EN-US"><font face="Calibri">y1,yn</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">除外），</span><span lang="EN-US"><font face="Calibri">xi,yi</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">都为非负整数。保证</span><span lang="EN-US"><font face="Calibri">y1,yn</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的值为</span><span lang="EN-US"><font face="Calibri">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Calibri"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">输出共</span><span lang="EN-US"><font face="Calibri">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行：每行一个实数</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第</span><span lang="EN-US"><font face="Calibri">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">行的实数表示从第</span><span lang="EN-US"><font face="Calibri">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">个顶点出发，到达最高点的路程。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">如果输出与标准输出的误差不超过</span><span lang="EN-US"><font face="Calibri">$1e-2$</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，则该测试点得满分，否则得</span><span lang="EN-US"><font face="Calibri">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">分。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Calibri"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
0 0<br/>
1 6<br/>
2 4<br/>
3 1<br/>
5 5<br/>
6 0<br/>
<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6.08<br/>
0.00<br/>
2.24<br/>
6.52<br/>
9.87<br/>
14.97<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri"><font size="3">【数据规模与约定】</font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">所有的数据满足</span><span lang="EN-US"><font face="Calibri">xi,yi&lt;=100000</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">1-4</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的测试点</span><font face="Calibri"> </font><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">满足</span><span lang="EN-US"><font face="Calibri">n&lt;=20</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">5-8</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的测试点，满足</span><span lang="EN-US"><font face="Calibri">n&lt;=70</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">9-10</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的测试点，满足</span><span lang="EN-US"><font face="Calibri">n&lt;=100000</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">且每个顶点都能直接看到最高点。</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">11-14</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的测试点，满足</span><span lang="EN-US"><font face="Calibri">n&lt;=30000</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">15-20</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的测试点，满足</span><span lang="EN-US"><font face="Calibri">n&lt;=100000</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。</span></font></p><br/>
<p></p><br/>
<p></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri"><font size="3"><img height="293" alt="" width="324" src="source/bzoj/3116/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNC8yLmpwZw==.jpg"/></font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri"><font size="3">路线说明：</font></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">A</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">点出发：</span><span lang="EN-US"><font face="Calibri">A-&gt;B</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">B</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">点出发：</span><span lang="EN-US"><font face="Calibri">B</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">C</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">点出发：</span><span lang="EN-US"><font face="Calibri">C-&gt;B</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">D</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">点出发：</span><span lang="EN-US"><font face="Calibri">D-&gt;G-&gt;D-&gt;C-&gt;B</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">E</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">点出发：</span><span lang="EN-US"><font face="Calibri">E-&gt;D-&gt;C-&gt;B</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri">F</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">点出发：</span><span lang="EN-US"><font face="Calibri">F-&gt;E-&gt;D-&gt;C-&gt;B</font></span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">从</span><span lang="EN-US"><font face="Calibri">D</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">点出发时，看到的最高点是</span><span lang="EN-US"><font face="Calibri">E</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，当步行至</span><span lang="EN-US"><font face="Calibri">G</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">点时，发现更高点</span><span lang="EN-US"><font face="Calibri">B</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，转向后一直步行向</span><span lang="EN-US"><font face="Calibri">B</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">点。从其它点出发后都不需要转向。</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=PTY提供 ">PTY提供 </a></p></div>

