<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>　　某校由于历史悠久，校园中有大量的名胜古迹。为了更好地保护这些古迹，学校决定用篱笆将这些古迹围起来。<br>　　现在已知有p个地点的古迹需要保护。这些古迹可以看做二维平面上的整数点。有n个点可以作为篱笆的端点，这些端点的坐标也为二维平面上的整数。端点用1到n的整数编号。<br>　　有m对端点之间可以修建篱笆。用(u,v,w)描述一段可以修建的篱笆，表示端点u和端点v之间可以花费w的代价修建一段。篱笆都看做直线段。为了方便设计，这些可以修建的篱笆都是不会相交的（只会在端点处相交）。<br>　　将一个古迹围起来是指存在一个由篱笆构成的简单多边形，这个古迹在该多边形内部。<br>　　由于经费问题，学校希望修建篱笆的花费最小。你需要输出将至少1个，2个，…，p个古迹围起来的最小花费。</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行包含三个正整数p,n,m表示古迹的个数，端点个数和可以修建的篱笆条数。</span><br><span>　　接下来p行，每行包含两个整数，表示每个古迹的坐标。</span><br><span>　　接下来n行，每行包含两个整数，表示每个端点的坐标。这些端点按照输入的顺序依次用1到n的整数编号。</span><br><span>　　最后m行，每行包含三个非负整数u,v,w，表示可以在端点u和端点v之间花w的代价修建一段篱笆。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　输出p行，分别表示将至少1个，2个，&hellip;，p个古迹围起来的最小花费。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3 9 15</span><br><span>-2 2</span><br><span>2 1</span><br><span>2 -1</span><br><span>3 0</span><br><span>3 2</span><br><span>1 2</span><br><span>-1 3</span><br><span>-3 3</span><br><span>-2 1</span><br><span>1 0</span><br><span>2 -2</span><br><span>2 -3</span><br><span>1 2 20</span><br><span>1 7 40</span><br><span>1 8 10</span><br><span>1 9 100</span><br><span>2 3 50</span><br><span>3 4 1000</span><br><span>3 7 10</span><br><span>4 5 10</span><br><span>4 6 10</span><br><span>4 7 1000</span><br><span>5 6 10</span><br><span>6 7 1000</span><br><span>7 8 120</span><br><span>7 9 10</span><br><span>8 9 10</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>30</span><br><span>100</span><br><span>140</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<div>
<p>　　样例如下图<br>　　<img height="268" src="/source/codevs/codevs-2007/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9R3FNNTZBYm0=.do" width="265"><br>　　保护至少1个古迹的方案<br>　　<img height="272" src="/source/codevs/codevs-2007/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OVFNUTNybWg=.do" width="268"><br>　　保护至少2个古迹的方案<br>　　<img height="274" src="/source/codevs/codevs-2007/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ODZiQTdiSHI=.do" width="271"><br>　　保护至少3个古迹的方案<br>　　<img height="277" src="/source/codevs/codevs-2007/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9QTRmVEE1N0w=.do" width="264"></p>
</div>
<div> </div>
<div>　　对于100%的数据，n≤100， m≤C(n,2)，p≤10。所有坐标位置的两维绝对值不超过10<sup>9</sup>，u,v不超过n，w不超过10<sup>6</sup>。<br>　　保证可以修建的篱笆不会经过古迹。保证可以修建的两段篱笆不会在非端点处相交或重合。保证至少存在一种方案可以包围所有古迹。保证n个点互不相同。<br>　　具体每组数据的规模如下</div>
</div>
<div>
<table cellpadding="2px" cellspacing="0">
<tbody>
<tr>
<td valign="top">编号</td>
<td valign="top">n</td>
<td valign="top">p</td>
<td valign="top">编号</td>
<td valign="top">n</td>
<td valign="top">p</td>
</tr>
<tr>
<td valign="top">1</td>
<td valign="top">50</td>
<td valign="top">1</td>
<td valign="top">6</td>
<td valign="top">100</td>
<td valign="top">8</td>
</tr>
<tr>
<td valign="top">2</td>
<td valign="top">100</td>
<td valign="top">1</td>
<td valign="top">7</td>
<td valign="top">100</td>
<td valign="top">9</td>
</tr>
<tr>
<td valign="top">3</td>
<td valign="top">15</td>
<td valign="top">3</td>
<td valign="top">8</td>
<td valign="top">50</td>
<td valign="top">10</td>
</tr>
<tr>
<td valign="top">4</td>
<td valign="top">40</td>
<td valign="top">4</td>
<td valign="top">9</td>
<td valign="top">80</td>
<td valign="top">10</td>
</tr>
<tr>
<td valign="top">5</td>
<td valign="top">100</td>
<td valign="top">6</td>
<td valign="top">10</td>
<td valign="top">100</td>
<td valign="top">10</td>
</tr>
</tbody>
</table>
</div>
<div> </div>
<div>来源：<span>中国国家队清华集训 2012-2013 第四天</span></div>
</div>
</div>