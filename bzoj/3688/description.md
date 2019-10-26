
# Description

<div class="content"><p><span style="font-size: medium">二维平面上有n个点(xi, yi)，现在这些点中取若干点构成一个集合S，对它们按照x坐标排序，顺次连接，将会构成一些连续上升、下降的折线，设其数量为f(S)。如下图中，1-&gt;2,2-&gt;3,3-&gt;5,5-&gt;6（数字为下图中从左到右的点编号），将折线分为了4部分，每部分连续上升、下降。<br/>
 <img height="290" width="389" alt="" src="/source/bzoj/3688/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwOS9hYS5qcGc=.jpg"/><br/>
现给定k，求满足f(S) = k的S集合个数。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行两个整数n和k，以下n行每行两个数(xi, yi)表示第i个点的坐标。所有点的坐标值都在[1, 100000]内，且不存在两个点，x坐标值相等或y坐标值相等</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出满足要求的方案总数 mod 100007的结果</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 1<br/>
5 5<br/>
3 2<br/>
4 4<br/>
2 3<br/>
1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">19<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于100%的数据，n &lt;= 50000，0 &lt; k &lt;= 10<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

