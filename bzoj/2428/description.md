
# Description

<div class="content"><p><span style="line-height: 150%; text-indent: 21pt; font-family: 宋体;">已知</span><span lang="EN-US" style="line-height: 150%; text-indent: 21pt;">N</span><span style="line-height: 150%; text-indent: 21pt; font-family: 宋体;">个正整数：</span><span lang="EN-US" style="line-height: 150%; text-indent: 21pt;">A1</span><span style="line-height: 150%; text-indent: 21pt; font-family: 宋体;">、</span><span lang="EN-US" style="line-height: 150%; text-indent: 21pt;">A2</span><span style="line-height: 150%; text-indent: 21pt; font-family: 宋体;">、……、</span><span lang="EN-US" style="line-height: 150%; text-indent: 21pt;">An </span><span style="line-height: 150%; text-indent: 21pt; font-family: 宋体;">。今要将它们分成</span><span lang="EN-US" style="line-height: 150%; text-indent: 21pt;">M</span><span style="line-height: 150%; text-indent: 21pt; font-family: 宋体;">组，使得各组数据的数值和最平均，即各组的均方差最小。均方差公式如下：</span></p>
<p><img src="/source/bzoj/2428/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQxMC9hYSgxKS5qcGc=.jpg" width="390" height="94" alt=""/>,<span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">其中</span><span style="font-family:
宋体">σ</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">为均方差，<img src="/source/bzoj/2428/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQxMC9iYi5qcGc=.jpg" width="34" height="46" alt=""/></span><span style="font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">是各组数据和的平均值，</span><span lang="EN-US">x<sub>i</sub></span><span style="font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">为第</span><span lang="EN-US">i</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">组数据的数值和。</span></p>
<p class="MsoNormal"><span lang="EN-US"> </span></p>
<p></p></div>

# Input

<div class="content"><div>第一行是两个整数，表示N,M的值（N是整数个数，M是要分成的组数）</div>
<div>第二行有N个整数，表示A1、A2、……、An。整数的范围是1--50。</div>
<div>（同一行的整数间用空格分开）</div></div>

# Output

<div class="content"><p><a id="fck_paste_padding"><span style="font-family:宋体;
mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">这一行只包含一个数，表示最小均方差的值</span><span lang="EN-US">(</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">保留小数点后两位数字</span><span lang="EN-US">)</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">。</span></a></p>
<p></p>
<p></p>
<p></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata"> 6  3<br/>
1  2  3  4  5  6</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.00</span></div>

# Hint

<div class="content"><p></p><p>对于全部的数据，保证有K&lt;=N &lt;= 20，2&lt;=K&lt;=6</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

