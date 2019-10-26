
# Description

<div class="content"><div style="text-indent: 6pt"><span style="font-size: 12pt">作为一名间谍，你的任务是确定国家之间运送的货物。每箱货物在驶离出口国后，都会被导向至少一个中间港口。在所有的港口，货物都储存在仓库之中，所以你没法从出口国到进口国追踪特定的箱子。卫星照片告诉你每条航道上每个方向运输了多少箱货物。同时你还知道这些箱子都走最短路。</span></div>
<p><span style="font-size: 12pt">你的任务是确定指定的两个国家之间的最大可能货运量和最小可能货运量，以箱数记。货运网络可以看作是一棵无根树，其中国家是叶子节点，中间港口是中间节点。同时你了解到，每箱货物一旦到达离开港口，绝对不会折返原路。</span></p>
<p><span style="font-size: 12pt"><img alt="" src="/source/bzoj/2504/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMS8zLmpwZw==.jpg"/><br/>
<br/>
</span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 6pt; mso-char-indent-count: .5"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">如上图所示，有</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">6</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个国家，标号为</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1,2,4,5,7,9</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，还有三个港口，标号为</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">3,6,8</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。虽然从</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">号国家到</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">4</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">号国家的路径上的每条边都通过了至少</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">4</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">箱货物，但是实际上没法从</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">号国家到</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">4</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">号国家输送</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">4</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">箱货物。非要如此，则在</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">6</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">号港口会有</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">箱从</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">2</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">号国家的送来的货物被迫折返，如是不可。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><o:p></o:p></span></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-tab-count: 1"><font face="Times New Roman">       </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输入的第一行有一个整数</span><font face="Times New Roman"><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt">n</span></i><span lang="EN-US" style="font-size: 12pt"> (3 &lt;= <i style="mso-bidi-font-style: normal">n</i> &lt;= 10000)</span></font><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">：节点个数（包括了国家和中间港口）。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">之后的</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">n-1</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行每行有四个整数</span><font face="Times New Roman"><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt">a</span></i><span lang="EN-US" style="font-size: 12pt">, <i style="mso-bidi-font-style: normal">b</i>, <i style="mso-bidi-font-style: normal">c1</i>, <i style="mso-bidi-font-style: normal">c2</i> (1 &lt;= <i style="mso-bidi-font-style: normal">a</i>, <i style="mso-bidi-font-style: normal">b</i> &lt;= <i style="mso-bidi-font-style: normal">n</i> and 0 &lt;= <i style="mso-bidi-font-style: normal">c1</i>, <i style="mso-bidi-font-style: normal">c2</i> &lt;= 1000)</span></font><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示从</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">a</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">到</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">b</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的航道上有</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">c1</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">箱货物，从</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">b</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">到</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">a</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的航道上有</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">c2</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">箱货物。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">最后一行是两个整数</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">fr</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><font face="Times New Roman"><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt">to </span></i><span lang="EN-US" style="font-size: 12pt">(1 &lt;= <i style="mso-bidi-font-style: normal">fr</i>, <i style="mso-bidi-font-style: normal">to</i> &lt;=<i style="mso-bidi-font-style: normal">n</i>, <i style="mso-bidi-font-style: normal">fr</i> != <i style="mso-bidi-font-style: normal">to</i>)</span></font><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">：指定的两个国家，分别是出口国和进口国。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">每行的整数由单个空格隔开。输入数据满足</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">Kirchhoff</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">定律：在每个港口输入的箱数等于输出的箱数。虽说满足此定律并不意味着必然存在一个输出方案满足输入的描述，但是，输入数据经过特殊设计，确保至少一个方案的存在性<a name="_GoBack"></a>。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><o:p><font face="Times New Roman"> </font></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-tab-count: 1"><font face="Times New Roman">       </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输出一行，包括两个由单个空格分隔开的整数，分别为从</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">fr</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">到</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">to</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的最小和最大可能运输箱数，要求满足给定的数据。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><o:p><font face="Times New Roman"> </font></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span lang="EN-US"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
<br/>
1 6 4 1<br/>
<br/>
2 6 2 1<br/>
<br/>
6 3 4 0<br/>
<br/>
7 3 1 1<br/>
<br/>
9 3 1 1<br/>
<br/>
3 8 6 2<br/>
<br/>
8 4 4 1<br/>
<br/>
8 5 2 1<br/>
<br/>
1 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 3<br/>
<br/>
【数据规模和约定】<br/>
50%的数据中n≤10；<br/>
100%的数据中n≤10000。<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

