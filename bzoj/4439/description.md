
# Description

<div class="content"><div>FJ有一块N*M的矩形田地，有两种地形高地（用‘#’表示）和低地（用‘.’表示）</div>
<div>FJ需要对每一行田地从左到右完整开收割机走到头，再对每一列从上到下完整走到头，如下图所示</div>
<div> <img src="/source/bzoj/4439/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMS8xMTExKDEpLnBuZw==.png" width="582" height="541" alt=""/></div>
<div>对于一个4*4的田地，FJ需要走8次。</div>
<div>收割机是要油的，每次从高地到低地或从低地到高地需要支付A的费用。</div>
<div>但是FJ有黑科技，可以高地与低地的互变，都只需要一个支付B的费用。</div>
<div>询问FJ需要支付最小费用。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含四个整数N,M,A,B，意义如上文所述。</div>
<div>接下来是一个N*M的字符串矩阵，表示农田的地形，’#’表示高地，’.’表示低地。</div>
<p></p></div>

# Output

<div class="content"><div>只包含一个正整数，表示最小费用。</div>
<div><span style="font-family: arial, verdana, helvetica, sans-serif;">1&lt;=N,M&lt;=50</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">1&lt;=A,B&lt;=100000</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4 1000 2000<br/>
...#<br/>
#..#<br/>
...#<br/>
##..<br/>
###.</span></div>

# Sample Output

<div class="content"><span class="sampledata">11000<br/>
样例解释：<br/>
把（2,1）的高地变成低地花费2000，燃料花费9000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

