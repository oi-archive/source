
# Description

<div class="content"><p><span style="font-size: medium">　　某校由于历史悠久，校园中有大量的名胜古迹。为了更好地保护这些古迹，学校决定用篱笆将这些古迹围起来。<br/>
　　现在已知有p个地点的古迹需要保护。这些古迹可以看做二维平面上的整数点。有n个点可以作为篱笆的端点，这些端点的坐标也为二维平面上的整数。端点用1到n的整数编号。<br/>
　　有m对端点之间可以修建篱笆。用(u,v,w)描述一段可以修建的篱笆，表示端点u和端点v之间可以花费w的代价修建一段。篱笆都看做直线段。为了方便设计，这些可以修建的篱笆都是不会相交的（只会在端点处相交）。<br/>
　　将一个古迹围起来是指存在一个由篱笆构成的简单多边形，这个古迹在该多边形内部。<br/>
　　由于经费问题，学校希望修建篱笆的花费最小。你需要输出将至少1个，2个，…，p个古迹围起来的最小花费。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　第一行包含三个正整数p,n,m表示古迹的个数，端点个数和可以修建的篱笆条数。<br/>
　　接下来p行，每行包含两个整数，表示每个古迹的坐标。<br/>
　　接下来n行，每行包含两个整数，表示每个端点的坐标。这些端点按照输入的顺序依次用1到n的整数编号。<br/>
　　最后m行，每行包含三个非负整数u,v,w，表示可以在端点u和端点v之间花w的代价修建一段篱笆。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">　　输出p行，分别表示将至少1个，2个，…，p个古迹围起来的最小花费。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 9 15<br/>
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
8 9 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">30<br/>
100<br/>
140</span></div>

# Hint

<div class="content"><p></p><p><img height="1145" width="332" alt="" src="/source/bzoj/2965/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMi8xMSg4KS5qcGc=.jpg"/></p><br/>
<p><span style="display: inline! important; float: none; word-spacing: 0px; font: 14px &#39;Times New Roman&#39;, ����; text-transform: none; color: rgb(32,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">　对于100%的数据，n≤100， m≤C(n,2)，p≤10。所有坐标位置的两维绝对值不超过10</span><sup style="font-weight: normal; word-spacing: 0px; text-transform: none; color: rgb(32,0,0); text-indent: 0px; line-height: normal; font-style: normal; font-family: &#39;Times New Roman&#39;, ����; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; font-variant: normal; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">9</sup><span style="display: inline! important; float: none; word-spacing: 0px; font: 14px &#39;Times New Roman&#39;, ����; text-transform: none; color: rgb(32,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">，u,v不超过n，w不超过10</span><sup style="font-weight: normal; word-spacing: 0px; text-transform: none; color: rgb(32,0,0); text-indent: 0px; line-height: normal; font-style: normal; font-family: &#39;Times New Roman&#39;, ����; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; font-variant: normal; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">6</sup><span style="display: inline! important; float: none; word-spacing: 0px; font: 14px &#39;Times New Roman&#39;, ����; text-transform: none; color: rgb(32,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">。</span><br style="word-spacing: 0px; font: 14px &#39;Times New Roman&#39;, ����; text-transform: none; color: rgb(32,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px"/><br/>
<span style="display: inline! important; float: none; word-spacing: 0px; font: 14px &#39;Times New Roman&#39;, ����; text-transform: none; color: rgb(32,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">　　保证可以修建的篱笆不会经过古迹。保证可以修建的两段篱笆不会在非端点处相交或重合。保证至少存在一种方案可以包围所有古迹。保证n个点互不相同。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=中国国家队清华集训 2012-2013 第四天
">中国国家队清华集训 2012-2013 第四天<br/>
</a></p></div>

