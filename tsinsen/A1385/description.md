<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　某校由于历史悠久，校园中有大量的名胜古迹。为了更好地保护这些古迹，学校决定用篱笆将这些古迹围起来。<br/>
　　现在已知有p个地点的古迹需要保护。这些古迹可以看做二维平面上的整数点。有n个点可以作为篱笆的端点，这些端点的坐标也为二维平面上的整数。端点用1到n的整数编号。<br/>
　　有m对端点之间可以修建篱笆。用(u,v,w)描述一段可以修建的篱笆，表示端点u和端点v之间可以花费w的代价修建一段。篱笆都看做直线段。为了方便设计，这些可以修建的篱笆都是不会相交的（只会在端点处相交）。<br/>
　　将一个古迹围起来是指存在一个由篱笆构成的简单多边形，这个古迹在该多边形内部。<br/>
　　由于经费问题，学校希望修建篱笆的花费最小。你需要输出将至少1个，2个，…，p个古迹围起来的最小花费。</div>
# 输入格式

<div class="pdcont">　　第一行包含三个正整数p,n,m表示古迹的个数，端点个数和可以修建的篱笆条数。<br/>
　　接下来p行，每行包含两个整数，表示每个古迹的坐标。<br/>
　　接下来n行，每行包含两个整数，表示每个端点的坐标。这些端点按照输入的顺序依次用1到n的整数编号。<br/>
　　最后m行，每行包含三个非负整数u,v,w，表示可以在端点u和端点v之间花w的代价修建一段篱笆。</div>
# 输出格式

<div class="pdcont">　　输出p行，分别表示将至少1个，2个，…，p个古迹围起来的最小花费。</div>
# 样例输入

<div class="pddata">3 9 15<br/>
-2 2<br/>
2 1<br/>
2 -1<br/>
3 0<br/>
3 2<br/>
1 2<br/>
-1 3<br/>
-3 3<br/>
-2 1<br/>
1 0<br/>
2 -2<br/>
2 -3<br/>
1 2 20<br/>
1 7 40<br/>
1 8 10<br/>
1 9 100<br/>
2 3 50<br/>
3 4 1000<br/>
3 7 10<br/>
4 5 10<br/>
4 6 10<br/>
4 7 1000<br/>
5 6 10<br/>
6 7 1000<br/>
7 8 120<br/>
7 9 10<br/>
8 9 10</div>
# 样例输出

<div class="pddata">30<br/>
100<br/>
140</div>
# 样例说明

<div class="pdcont">　　样例如下图<br/>
　　<img width="265" height="268" src="source/tsinsen/A1385/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9R3FNNTZBYm0=.do"/>.<br/>
　　保护至少1个古迹的方案<br/>
　　<img width="268" height="272" src="source/tsinsen/A1385/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9OVFNUTNybWg=.do"/>.<br/>
　　保护至少2个古迹的方案<br/>
　　<img width="271" height="274" src="source/tsinsen/A1385/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ODZiQTdiSHI=.do"/>.<br/>
　　保护至少3个古迹的方案<br/>
　　<img width="264" height="277" src="source/tsinsen/A1385/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9QTRmVEE1N0w=.do"/>.</div>
# 数据规模及约定

<div class="pdcont">　　对于100%的数据，n≤100， m≤C(n,2)，p≤10。所有坐标位置的两维绝对值不超过10<sup>9</sup>，u,v不超过n，w不超过10<sup>6</sup>。<br/>
　　保证可以修建的篱笆不会经过古迹。保证可以修建的两段篱笆不会在非端点处相交或重合。保证至少存在一种方案可以包围所有古迹。保证n个点互不相同。<br/>
　　具体每组数据的规模如下<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">编号<br/>
</td><td valign="top" style="border:solid 1.0pt">n<br/>
</td><td valign="top" style="border:solid 1.0pt">p<br/>
</td><td valign="top" style="border:solid 1.0pt">编号<br/>
</td><td valign="top" style="border:solid 1.0pt">n<br/>
</td><td valign="top" style="border:solid 1.0pt">p<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">50<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">15<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">50<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">40<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">80<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td></tr></tbody></table></div>

</div>