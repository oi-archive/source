
# Description

<div class="content"><div class="plm"></div>
<div class="ptx" lang="en-US">John and Brus are playing a military strategic game on a PC. The game is played on the flat world map. At the beginning of the game Brus places his army. Then John has to choose strategic points for his army according to the following rules: <br/>
<p style="padding-left: 30px"><br/>
each strategic point must be a lattice point (x, y) (a lattice point is a point with integer coordinates) such that |x| + |y| &lt; N; <br/>
John can choose any positive number of strategic points; <br/>
all the strategic points must be distinct; <br/>
each of the strategic points must be free (i.e. not occupied by Brus’s army); <br/>
each pair of different strategic points must be connected (possibly via some other strategic points). <br/>
</p>
<br/>
Here two different lattice points (x1, y1) and (x2, y2) are connected if |x1 – x2| + |y1 – y2| = 1. If A, B and C are strategic points, A and B are connected, B and C are connected, then A and C are also connected. <br/>
Your task is to find the number of ways for John to choose strategic points for his army.</div>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt"><font size="3"><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">给定一个形状特殊的棋盘如右图，其中有些格子已经被选定了。</span><span lang="EN-US" style="mso-bidi-font-size: 10.5pt"><o:p></o:p></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt"><font size="3"><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">问取出一个连通块的方案数有多少种。</span><span lang="EN-US" style="mso-bidi-font-size: 10.5pt"><o:p></o:p></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt"><font size="3"><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">其中</span><span lang="EN-US" style="mso-bidi-font-size: 10.5pt"><font face="Times New Roman">N&lt;=6</font></span><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">（也就是竖着最长的一条长度</span><span lang="EN-US" style="mso-bidi-font-size: 10.5pt"><font face="Times New Roman">&lt;=13</font></span><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">）。</span></font><span lang="EN-US" style="mso-bidi-font-size: 10.5pt"><o:p></o:p></span></p>
<p></p></div>

# Input

<div class="content"><div class="ptx" lang="en-US">The first line contains single integer T – the number of test cases. Each test case starts with a line containing two integers N and M separated by a single space. N is the number mentioned in the first rule. M is the number of lattice points on the world map already occupied by Brus’s army. Each of the following M lines contains two integers Xk and Yk separated by a single space. Each lattice point (Xk, Yk) is occupied by Brus’s army.</div></div>

# Output

<div class="content"><div class="ptx" lang="en-US">For each test case print a single line containing the number of ways for John to choose strategic points for his army.</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
2 1 <br/>
7 7 <br/>
2 3 <br/>
0 0 <br/>
4 -7 <br/>
7 -4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">20 <br/>
4<br/>
Hint<br/>
<br/>
Constraints: <br/>
1 ≤ T ≤ 74, <br/>
1 ≤ N ≤ 7, <br/>
1 ≤ M ≤ 225, <br/>
-7 ≤ Xk, Yk ≤ 7, <br/>
all (Xk, Yk) will be distinct.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

