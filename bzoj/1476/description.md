
# Description

<div class="content"><p>给定你一块矩形板，矩形板是由n*m个1*1的单位元构成的。每次要你从板上切下一块矩形，切割的位置已知，且矩形的长宽与矩形板的长宽垂直或平行，且不会把一个单位元分开。由于可能原有的位置已经被切了很多刀了，你的任务就是每次回答把这块矩形切下来的时候，又切出了多少个连通块？</p></div>

# Input

<div class="content"><p>第1行3个数n,m,p。分别表示矩形板的大小，和你要切的刀数。 接下来p行，每行4个数：x1,y1,x2,y2。表示每次要切的矩形的位置。</p></div>

# Output

<div class="content"><p>一共p行，每行一个数，表示要切出的连通块数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 2<br/>
1 2 3 2<br/>
2 1 2 3	</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
 <br/>
在这个图中，假设灰色部分一被割下，那么如果切出红色矩形，一共切出了4块。<br/>
数据范围约定：N,m&lt;=1000,p&lt;=100000<br/>
<br/>
<img border="0" src="/source/bzoj/1476/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0NzYuanBn.jpg"/><br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

