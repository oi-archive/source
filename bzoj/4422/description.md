
# Description

<div class="content"><div>一个10^6行10^6列的网格图，上面有一些牛、花和一些矩形围栏，围栏在格子的边界上，牛和花在格子里，牛只能向下或向右走，牛也不能穿过围栏和地图边界，求每头牛它能到达的花的数量。注意栅栏不会相交</div>
<div><img width="486" height="492" alt="" src="/source/bzoj/4422/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMy9hYS5wbmc=.png"/></div>
<div></div>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><div>第一行一个数f表示矩形围栏的数量。</div>
<div>接下来f行，每行四个数x1,y1,x2,y2，表示(x1,y1)在围栏内部矩形的左上角，(x2,y2)在右下角。</div>
<div>接下来一行一个数m表示花的数量。</div>
<div>接下来m行每行两个数x,y，表示在(x,y)处有一朵花。</div>
<div>接下来一行一个数n表示牛的数量。</div>
<div>接下来n行每行两个数x,y，表示在(x,y)处有一头牛。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>总共n行，每行一个数ans，第i个数表示第i头牛能到ans个花。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 2 8 4<br/>
1 9 4 10<br/>
6 7 9 9<br/>
3 3 7 3<br/>
9<br/>
3 4<br/>
8 4<br/>
11 5<br/>
10 7<br/>
10 8<br/>
9 8<br/>
2 8<br/>
4 11<br/>
9 11<br/>
8<br/>
1 1<br/>
5 10<br/>
6 9<br/>
3 7<br/>
7 1<br/>
4 2<br/>
7 5<br/>
3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1<br/>
0<br/>
1<br/>
3<br/>
1<br/>
3<br/>
0</span></div>

# Hint

<div class="content"><p></p><div style="font-family: &#39;lucida Grande&#39;, Verdana, &#39;Microsoft YaHei&#39;; font-size: 14px; line-height: 19.16666603088379px;">0&lt;=f&lt;=<span style="border-bottom-width: 1px; border-bottom-style: dashed; border-bottom-color: rgb(204, 204, 204); z-index: 1;" data="200000" t="7">200000</span></div><br/>
<div style="font-family: &#39;lucida Grande&#39;, Verdana, &#39;Microsoft YaHei&#39;; font-size: 14px; line-height: 19.16666603088379px;">0&lt;=m&lt;=<span style="border-bottom-width: 1px; border-bottom-style: dashed; border-bottom-color: rgb(204, 204, 204); z-index: 1;" data="200000" t="7">200000</span></div><br/>
<div style="font-family: &#39;lucida Grande&#39;, Verdana, &#39;Microsoft YaHei&#39;; font-size: 14px; line-height: 19.16666603088379px;">1&lt;=n&lt;=<span style="border-bottom-width: 1px; border-bottom-style: dashed; border-bottom-color: rgb(204, 204, 204); z-index: 1; position: static;" data="200000" t="7">200000</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

