
# Description

<div class="content"><div><span style="font-size: medium">       Up主家终于买电脑了，但是接下来有各种问题要处理。首要解决的问题就是网络问题。他要从移动公司开始，通过一些基站来传递网络到他家。</span></div>
<div><span style="font-size: medium">       为了简化问题，我们假设移动公司，所有的基站，up主家位于同一条直线上，他们都位于这一条直线上的某一点x，这些点不会重合。每个基站发射和接收的范围都是一个切于地面的圆，发射的半径r1是固定的，接收半径r2是可调的的。如下图：</span></div>
<div><span style="font-size: medium"><img height="270" alt="" width="537" src="source/bzoj/3006/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwMS8xLmpwZw==.jpg"/></span></div>
<div></div>
<div><span style="font-size: medium">       一个点i如果能从另一个点j接收到信号(当且仅当x[j] &lt; x[i])，必须满足i的接收范围与j的发射范围相切，并且需要付sqrt(r2[i])的额外费用。同时启动每一个点i都需要费用v[i].</span></div>
<div><span style="font-size: medium">       当然一个点如果能够发射的up主家只需要这个点的发射范围与up主家所在的竖线相切或相交即可，如下图：</span></div>
<div><span style="font-size: medium"><img height="262" alt="" width="373" src="source/bzoj/3006/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwMS8yLmpwZw==.jpg"/></span></div>
<div></div>
<div><span style="font-size: medium">当然费用越少就越好咯，于是up主想要请你帮他的忙。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">       第一行两个整数n,m.表示基站个数(包括移动公司)，up主家的坐标。(保证大等于所以基站的坐标)</span></div>
<div><span style="font-size: medium">       记下来n行，每行三个整数x[i],r1[i],v[i],表示每个基站的坐标，发射范围以及费用。</span></div>
<div><span style="font-size: medium">       X[i]是按照坐标从小到大输入的，移动公司位于最小的那个坐标。</span></div>
<div><span style="font-size: medium">       R为1..n的排列。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">       一个实数，保留小数点后三位。</span></div>
<div><span style="font-size: medium"><b> </b></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">10 33<br/>
5 4 660<br/>
10 2 2040<br/>
11 6 3207<br/>
14 5 2006<br/>
18 3 6130<br/>
19 9 3363<br/>
22 1 1265<br/>
25 8 2836<br/>
27 10 7961<br/>
29 7 9075<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3501.000<br/>
 <br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据 n&lt;=5*1000000,x[i],m &lt;= 10^12,v[i] &lt;= 10000<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

