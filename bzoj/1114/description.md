
# Description

<div class="content"><p>给出一个地图.上面有水,有故障点. 你要开着一个船走出这个地图. 问最少要多少步,否则无解. 注意这个船是关于轴对称的.</p></div>

# Input

<div class="content"><p>第一行给出数字N,代表地图的大小.N在[3,2000] 下面N行N列的字符矩阵 &#34;.&#34;代表水 &#34;X&#34;代表故障点 &#34;r&#34;代表你的船的一部分. 也就是说你的船是由多个相连的r组成的.</p></div>

# Output

<div class="content"><p>最少的步数离开这个地图.</p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
..........<br/>
..........<br/>
..r.......<br/>
.rrrX.....<br/>
rrrrr.....<br/>
.rrr......<br/>
X.r.......<br/>
.Xr.......<br/>
..........<br/>
..........</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p><p><img border="0" alt="" src="/source/bzoj/1114/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExMTQuanBn.jpg"/> </p><br/>
<p>1.当出不去的时候 要输出&#34;NIE&#34;</p><br/>
<p>2.船是关于横轴或竖轴对称的</p><br/>
<p>3.船的宽度是严格从小到大，再从大到小的</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

