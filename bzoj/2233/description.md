
# Description

<div class="content"><div><span style="font-size: 12pt">  </span></div>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-spacerun: yes"><font face="Times New Roman">   </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">在远古时代，信息的交流没有我们现在这么便利。一个国家在战争时期，可能花好几个月的时间来集合军队。但是在作战区用上烽火台，就有可能快速地传递军事信号。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-spacerun: yes"><font face="Times New Roman">   </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">当第一个烽火台被点燃，所有能看到这个烽火台的其他烽火台也将被点燃，所有能看到这些烽火台的其他烽火台也将被点燃，如此继续直到所有烽火台都被点燃</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">---</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">自然所有的烽火台都在彼此的视野范围内，直接地或间接地。如果不是这样，则紧急的信息必须由骑手们在一些烽火台间传递。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-spacerun: yes"><font face="Times New Roman">     </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">给出这个国家所有烽火台的位置，同时还给出山峰的位置和大小，写一个程序来决定多少信息要被骑手们传递，使得在敌人入侵这个国家时，所有的烽火台都要被点燃。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-spacerun: yes"><font face="Times New Roman">   </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">简单来说，我们这样来定义一个国家的模型：一个烽火台就用</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">XY</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">平面上的一个点来表示，一座山峰就用一个圆来表示。如果两个烽火台的连接直线上没有山峰座落，则认为这两个烽火台是在相互的视野内。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输入是这样构造的：任何一对烽火台的连线不会与山峰的圆周相切，除非这个连接线通过了别的山峰的内部。山峰不会重叠或相切，任何一个烽火台也不会在山峰内或它的圆周上。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p></p></div>

# Input

<div class="content"><p><font size="3"> <span style="font-size: 12pt">第一行有两个整数</span></font><span style="font-size: 12pt">n (1&lt;=n &lt;=1000) and m (0 &lt;=m &lt;=1000),n</span><span style="font-size: 12pt">表示烽火台的数量，</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">表示山峰的数量。接下来的</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">行定义了烽火台的位置。每个烽火台的位置用一对整数</span><span style="font-size: 12pt">X</span><span style="font-size: 12pt">和</span><span style="font-size: 12pt">Y</span><span style="font-size: 12pt">来表示</span><span style="font-size: 12pt">(0 &lt;= x; y &lt;= 10000).</span><span style="font-size: 12pt">接下来的</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">行描述了所有的山峰。每个山峰用三个数来表示：</span><span style="font-size: 12pt">X Y R. X Y</span><span style="font-size: 12pt">为整数</span><span style="font-size: 12pt">(0 &lt;= x; y &lt;= 10000)</span><span style="font-size: 12pt">定义了山峰的位置，</span><span style="font-size: 12pt">R</span><span style="font-size: 12pt">定义了半径</span><span style="font-size: 12pt">(1 &lt;= r &lt;= 5000)</span></p></div>

# Output

<div class="content"><div style="text-indent: 21.75pt"><span style="font-size: 12pt">输出一个整数：为使所有烽火台点燃，骑手们必须传递的信息数量</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6  3<br/>
1  8<br/>
5  4<br/>
7  7<br/>
9  2<br/>
16  6<br/>
17  10<br/>
4  7  2<br/>
6  3  1<br/>
12  6  3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

