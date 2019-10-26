
# Description

<div class="content"><div>
<pre style="white-space: normal; word-wrap: break-word; font-size: 14px; line-height: 15.333333015441895px;"><div>给出一张四连通的网格图，&#39;#&#39;代表墙,&#39;.&#39;代表空地,&#39;S&#39;代表出发点,&#39;C&#39;代表目的地，地图四周都是墙,求S到C的最短路。</div><div>走的时候可以向上下左右中的某个方向发射奇怪的东西(portals)，portals会贴在发射方向的墙上。</div><div>地图上只允许同时存在两个portals，如果已经发射了两个再发射第三个，那么你需要在之前的那两个中的选一个使它消失。</div><div>两个portals可以存在于一块墙的两面，但不能存在于一块墙的同面。</div><div>当你身边是墙且那块墙上有面向你的portals时，你可以走进那个portals，从另一个portals出来。</div><div>相邻两点距离为1，走portals距离也为1</div></pre>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行2个数R,C,表示矩形的长和宽</div>
<div>接下来R行,每行一个长为C的字符串,表示这张图</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行表示答案</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
.#.C<br/>
.#.#<br/>
....<br/>
S...</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><div><img src="/source/bzoj/3919/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC9zLnBuZw==.png" width="265" height="222" alt=""/></div><br/>
<div>对于100%的数据 1 ≤ R ≤ 1000, 1 ≤ C ≤ 1000.</div><br/>
<div>保证有解</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

