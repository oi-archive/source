
# Description

<div class="content"><div>有两堵墙A, B平行放置，两堵墙相隔10m远。在A墙的底部放置有一个点光源，且A墙上有n个玻璃窗，B墙上有m个玻璃窗，每个窗户都可以发生镜面反射，反射遵循光的反射定律（入射角出射角相等），但窗户的边框上不能反射光线。每个窗户都形如一个平行于坐标系的矩形，分别考虑两堵墙，看成一个平面后建立平面直角坐标系（单位长度m），x为水平方向，y为竖直方向。而每个窗户所代表的矩形用左下角坐标(x1, y1)和右上角坐标(x2, y2)给出，同一堵墙上没有任意两个窗户在边框以内的部分有交点（允许边框上有交点）。两堵墙的坐标系的原点(0, 0)相互正对。A墙底部的点光源位于A墙的(0, 0)处，保证不会在A墙的某个窗户的边界上或内部。求在A墙上有多少个窗户能接收到点光源的光线（仅通过窗户的反射）。PS.光线未经过反射前可以照射到B墙的每一个点上，而不能照射到A墙的任意一个点上。具体见样例解释。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数n, m分别代表两堵墙上的窗户数量。</div>
<div>接下来n行每行四个整数x1, y1, x2, y2，给定A墙上的n个矩形窗户。</div>
<div>接下来m行每行四个整数x1, y1, x2, y2，给定B墙上的m个矩形窗户。</div>
<p></p></div>

# Output

<div class="content"><div>第一行一个正整数ans表示有ans个窗户能接收到光线（数据保证ans &gt;= 1）。</div>
<div>第二行ans个整数表示能接收到光线的A墙窗户的编号，按照输入的顺序从1到n标号，从小到大升序输出。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
-1 2 1 4<br/>
-1 5 1 7<br/>
-3 8 -2 20<br/>
-1 1 1 2<br/>
-1 4 1 5<br/>
-1 7 1 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1 2<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/4225/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNy9mZi5QTkc=.PNG" width="688" height="758" alt=""/></p><br/>
<p><span style="text-indent: 20.5pt; font-size: 12pt; font-family: 宋体;">对于</span><span lang="EN-US" style="text-indent: 20.5pt; font-size: 12pt; font-family: Consolas;">100%</span><span style="text-indent: 20.5pt; font-size: 12pt; font-family: 宋体;">的数据，</span><span lang="EN-US" style="text-indent: 20.5pt; font-size: 12pt; font-family: Consolas;">1 &lt;= n &lt;= 600, 1 &lt;= m &lt;= 600, -1000 &lt;= x1 &lt; x2  &lt;= 1000, 0 &lt;= y1 &lt; y2 &lt;= 1000</span><span style="text-indent: 20.5pt; font-size: 12pt; font-family: 宋体;">。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

