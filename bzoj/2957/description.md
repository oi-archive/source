
# Description

<div class="content"><p><span style="font-size: medium">　　小A的楼房外有一大片施工工地，工地上有N栋待建的楼房。每天，这片工地上的房子拆了又建、建了又拆。他经常无聊地看着窗外发呆，数自己能够看到多少栋房子。<br/>
　　为了简化问题，我们考虑这些事件发生在一个二维平面上。小A在平面上(0,0)点的位置，第i栋楼房可以用一条连接(i,0)和(i,Hi)的线段表示，其中Hi为第i栋楼房的高度。如果这栋楼房上任何一个高度大于0的点与(0,0)的连线没有与之前的线段相交，那么这栋楼房就被认为是可见的。<br/>
　　施工队的建造总共进行了M天。初始时，所有楼房都还没有开始建造，它们的高度均为0。在第i天，建筑队将会将横坐标为Xi的房屋的高度变为Yi(高度可以比原来大---修建，也可以比原来小---拆除，甚至可以保持不变---建筑队这天什么事也没做)。请你帮小A数数每天在建筑队完工之后，他能看到多少栋楼房？<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　第一行两个正整数N,M<br/>
　　接下来M行，每行两个正整数Xi,Yi<br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">　　M行，第i行一个整数表示第i天过后小A能看到的楼房有多少栋<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3 4<br/>
2 4<br/>
3 6<br/>
1 1000000000<br/>
1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
1<br/>
1<br/>
1<br/>
2<br/>
数据约定<br/>
　　对于所有的数据1&lt;=Xi&lt;=N，1&lt;=Yi&lt;=10^9<br/>
N,M&lt;=100000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=中国国家队清华集训 2012-2013 第一天">中国国家队清华集训 2012-2013 第一天</a></p></div>

