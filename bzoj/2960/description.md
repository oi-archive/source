
# Description

<div class="content"><p><img height="283" alt="" width="930" src="/source/bzoj/2960/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMi8xMSg1KS5qcGc=.jpg"/></p></div>

# Input

<div class="content"><p><span style="font-size: medium">　第一行两个整数n和m，表示点与线段的数目。<br/>
　　接下来n行，每行两个整数x和y，表示第i个点的坐标，点从1到n编号。<br/>
　　接下来m行，每行四个整数p,q,V1和V2，表示存在一条从第p个点连向第q个点的线段，激活p-&gt;q这个方向的费用为V1，另一个方向费用为V2。<br/>
　　保证若两条线段相交，则交点是它们的公共端点。<br/>
</span></p></div>

# Output

<div class="content"><p><font size="4">　　输出一行一个正整数，表示最小总激活费用。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
0 0<br/>
1 0<br/>
0 1<br/>
1 1<br/>
1 2 0 0<br/>
1 3 0 3<br/>
2 3 1 0<br/>
2 4 2 0<br/>
4 3 0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p><span style="display: inline! important; float: none; word-spacing: 0px; font: 14px &#39;Times New Roman&#39;, ����; text-transform: none; color: rgb(32,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px"><img height="224" alt="" width="695" src="/source/bzoj/2960/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMi8yMigyKS5qcGc=.jpg"/></span></p><br/>
<p><span style="display: inline! important; float: none; word-spacing: 0px; font: 14px &#39;Times New Roman&#39;, ����; text-transform: none; color: rgb(32,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">　　对于100%的数据，n≤3000，区域数不超过1000，点坐标绝对值不超过1W，每条边激活费用不超过100。</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=中国国家队清华集训 2012-2013 第二天 鸣谢lydrainbowcat">中国国家队清华集训 2012-2013 第二天 鸣谢lydrainbowcat</a></p></div>

