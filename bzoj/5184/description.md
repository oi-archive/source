
# Description

<div class="content"><div>一个大小为(2n+1)*(2n+1)的方格按照如下方法构造。数字1放在正方形的中间，数字2放在1的右边，接下来的数字</div>
<div>按照逆时针的顺序填充这个方格。你需要计算q个询问的答案，每个询问查询一个矩形内的数的和，结果对10^9+7</div>
<div>取模。比如n=2的方格中，灰色区域的数的和是74：</div>
<div> <img src="source/bzoj/5184/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi92djIucG5n.png" width="213" height="215" alt=""/></div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行包含2个整数n,q:方格的大小和询问的数量。</div>
<div>接下来的q行每行包含4个整数x1,y1,x2,y2(-n&lt;=x1&lt;=x2&lt;=n,-n&lt;=y1&lt;=y2&lt;=n)。</div>
<div>表示你要计算的矩形区域的两个角落的坐标为（x1,y1）(x2,y2)</div>
<div>1&lt;=N&lt;=10^9</div>
<div>1&lt;=q&lt;=100</div>
<p></p></div>

# Output

<div class="content"><div>每个询问输出一行答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
0 -2 1 1<br/>
-1 0 1 0<br/>
1 2 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">74<br/>
9<br/>
14</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

