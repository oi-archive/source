
# Description

<div class="content"><div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%">Secsa最近对最小生成树问题特别感兴趣。他已经知道如果要去求出一个n个点、m条边的无向图的最小生成树有一个Krustal算法和另一个Prim的算法。另外，他还知道，某一个图可能有多种不同的最小生成树。例如，下面<span><span><span>图</span><span> 3</span></span></span>中所示的都是<span><span><span>图</span><span> 2</span></span></span>中的无向图的最小生成树：</div>
<p><img alt="" src="/source/bzoj/2521/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMS8yKDUpLmpwZw==.jpg"/></p>
<p class="MsoPlainText" style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%; mso-para-margin-top: .5gd; mso-para-margin-right: 0cm; mso-para-margin-bottom: 1.0gd; mso-para-margin-left: 0cm; mso-char-indent-count: 2.0"><font size="3"><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">当然啦，这些都不是今天需要你解决的问题。</font></span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;">Secsa</span><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">想知道对于某一条无向图中的边</font></span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;">AB</span><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">，至少需要多少代价可以保证</font></span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;">AB</span><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">边在这个无向图的最小生成树中。为了使得</font></span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;">AB</span><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">边一定在最小生成树中，你可以对这个无向图进行操作，一次单独的操作是指：先选择一条图中的边</font></span></font><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;"><span style="position: relative; top: 5pt; mso-text-raise: -5.0pt"><v:shapetype id="_x0000_t75" stroked="f" filled="f" path="m@4@5l@4@11@9@11@9@5xe" o:preferrelative="t" o:spt="75" coordsize="21600,21600"><font size="3"> P1P2<v:stroke joinstyle="miter"></v:stroke><v:formulas><v:f eqn="if lineDrawn pixelLineWidth 0"></v:f><v:f eqn="sum @0 1 0"></v:f><v:f eqn="sum 0 0 @1"></v:f><v:f eqn="prod @2 1 2"></v:f><v:f eqn="prod @3 21600 pixelWidth"></v:f><v:f eqn="prod @3 21600 pixelHeight"></v:f><v:f eqn="sum @0 0 1"></v:f><v:f eqn="prod @6 1 2"></v:f><v:f eqn="prod @7 21600 pixelWidth"></v:f><v:f eqn="sum @8 21600 0"></v:f><v:f eqn="prod @7 21600 pixelHeight"></v:f><v:f eqn="sum @10 21600 0"></v:f></v:formulas><v:path o:connecttype="rect" gradientshapeok="t" o:extrusionok="f"></v:path><o:lock aspectratio="t" v:ext="edit"></o:lock></font></v:shapetype></span></span><font size="3"><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">，再把图中除了这条边以外的边，每一条的权值都减少</font></span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;">1</span><font face="宋体"><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">。如</span>图 <span lang="EN-US" style="mso-no-proof: yes">4</span><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">所示就是一次这样的操作：</span></font></font></p>
<p class="MsoPlainText" style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%; mso-para-margin-top: .5gd; mso-para-margin-right: 0cm; mso-para-margin-bottom: 1.0gd; mso-para-margin-left: 0cm; mso-char-indent-count: 2.0"><font size="3"><font face="宋体"><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><img alt="" src="/source/bzoj/2521/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMS8zKDUpLmpwZw==.jpg"/></span></font></font></p></div>

# Input

<div class="content"><div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">输入文件的第一行有3个正整数n、m、Lab分别表示无向图中的点数、边数、必须要在最小生成树中出现的AB边的标号。</span></div>
<div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">接下来m行依次描述标号为1,2,3…m的无向边，每行描述一条边。每个描述包含3个整数x、y、d，表示这条边连接着标号为x、y的点，且这条边的权值为d。</span></div>
<div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">输入文件保证1&lt;=x,y&lt;=N,x不等于y,且输入数据保证这个无向图一定是一个连通图。</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">输出文件只有一行，这行只有一个整数，即，使得标号为Lab边一定出现最小生成树中的最少操作次数。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 6 1<br/>
1 2 2<br/>
1 3 2<br/>
1 4 3<br/>
2 3 2<br/>
2 4 4<br/>
3 4 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p><p class="MsoPlainText" style="margin: 6pt 0cm; text-indent: 21pt; line-height: 150%; mso-para-margin-top: .5gd; mso-para-margin-right: 0cm; mso-para-margin-bottom: .5gd; mso-para-margin-left: 0cm; mso-char-indent-count: 2.0"><span style="font-size: medium"><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">第</font></span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;">1</span><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体">个样例就是问题描述中的例子。</font></span></span></p><br/>
<p class="MsoPlainText" style="margin: 6pt 0cm; text-indent: 21pt; line-height: 150%; mso-para-margin-top: .5gd; mso-para-margin-right: 0cm; mso-para-margin-bottom: .5gd; mso-para-margin-left: 0cm; mso-char-indent-count: 2.0"><span style="font-size: medium"><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">1&lt;=n&lt;=500,1&lt;=M&lt;=800,1&lt;=D&lt;10^6</span></font></span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=day2">day2</a></p></div>

