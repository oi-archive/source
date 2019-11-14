
# Description

<div class="content"><div style="margin: 0cm 0cm 0pt 0.5pt; text-indent: -0.5pt"><span style="font-size: 12pt">有个国家，它的所有城市如下图被公路连成了一个环，依次编号为</span><span style="font-size: 12pt">1..N</span><span style="font-size: 12pt">。并且在这个环内有一些笔直的公路，每条公路连接两个城市。为了不发生交通事故，任意两条公路不会在中途相交。为了使城市之间的交通更便利，城市间会建尽可能多的公路，但两个城市之间最多建一条公路。</span></div>
<div style="margin: 0cm 0cm 0pt 0.5pt; text-indent: -0.5pt"></div>
<div style="margin: 0cm 0cm 0pt 0.5pt; text-indent: -0.5pt"><span style="font-size: 12pt">    </span><span style="font-size: 12pt">现在因为有另一个国家想破坏这个国家的交通系统，所以我们需要在一些城市建堡垒，使每条公路都能被监督（在</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">城市建堡垒可以监督与</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">城市相邻的公路）。问你最少需要建多少个堡垒。</span></div>
<p><img height="314" width="343" alt="" src="/source/bzoj/2689/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwNC9hYS5qcGc=.jpg"/></p></div>

# Input

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">第一行有一个正整数</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">，表示城市数。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">接下来</span><span style="font-size: 12pt">2*N-3</span><span style="font-size: 12pt">行（环上有</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">条公路，环中有</span><span style="font-size: 12pt">N-3</span><span style="font-size: 12pt">条公路），每行两个正整数</span><span style="font-size: 12pt">u</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">v</span><span style="font-size: 12pt">，表示城市</span><span style="font-size: 12pt">u</span><span style="font-size: 12pt">与城市</span><span style="font-size: 12pt">v</span><span style="font-size: 12pt">之间有一条公路。</span></div></div>

# Output

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">仅有一行一个正整数，表示最少的堡垒数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
5 6<br/>
6 7<br/>
7 8<br/>
8 1<br/>
1 3<br/>
8 3<br/>
7 3<br/>
7 5<br/>
5 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
【样例说明】<br/><br/>
在1、3、5、7号城市建堡垒即可。<br/><br/>
【数据规模和约定】<br/><br/>
30%的数据中：N&lt;=1000。<br/><br/>
100%的数据中：N&lt;=100000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

