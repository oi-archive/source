
# Description

<div class="content"><p><span style="font-size: medium">要求在平面直角坐标系下维护两个操作： <br/>
1.在平面上加入一条线段。记第i条被插入的线段的标号为i。 <br/>
2.给定一个数k,询问与直线 x = k相交的线段中，交点最靠上的线段的编号。  <br/>
</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium"> <br/>
第一行一个整数n，表示共n 个操作。 <br/>
接下来n行，每行第一个数为0或1。 <br/>
 <br/>
若该数为 0，则后面跟着一个正整数 k，表示询问与直线  <br/>
x = ((k +lastans–1)%39989+1)相交的线段中交点（包括在端点相交的情形）最靠上的线段的编号，其中%表示取余。若某条线段为直线的一部分，则视作直线与线段交于该线段y坐标最大处。若有多条线段符合要求，输出编号最小的线段的编号。 <br/>
若该数为 1，则后面跟着四个正整数 x0, y0, x 1, y 1，表示插入一条两个端点为 <br/>
((x0+lastans-1)%39989+1,(y0+lastans-1)%10^9+1)和((x<br/>
1+lastans-1)%39989+1,(y1+lastans-1)%10^9+1) 的线段。 <br/>
其中lastans为上一次询问的答案。初始时lastans=0。 <br/>
 <br/>
 </span></p></div>

# Output

<div class="content"><p><span style="font-size: large;">对于每个 0操作，输出一行，包含一个正整数，表示交点最靠上的线段的编</span><font size="4">号。若不存在与直线相交的线段，答案为0。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 <br/>
1 8 5 10 8<br/>
1 6 7 2 6<br/>
0 2<br/>
0 9<br/>
1 4 7 6 7<br/>
0 5<br/>
 </span></div>

# Sample Output

<div class="content"><span class="sampledata">2 <br/>
0 3 <br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，1 ≤ n ≤ 10^5 , 1 ≤  k, x0, x1 ≤ 39989, 1 ≤ y0 ≤ y1 ≤ 10^9。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

