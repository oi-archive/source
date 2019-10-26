
# Description

<div class="content"><div>《飞扬的小鸟》是一款风靡的小游戏。在游戏中，小鸟一开始位于(0,0)处，它的目标是飞到横坐标为X的某个位置</div>
<div>上。每一秒，你可以选择点击屏幕，那么小鸟会从(x,y)飞到(x+1,y+1)，或者不点击，那么小鸟会飞到(x+1,y-1)</div>
<div>。在游戏中还有n个障碍物，用三元组(x[i],a[i],b[i])描述，表示在直线x=x[i]上，y&lt;=a[i]或者y&gt;=b[i]的部分</div>
<div>都是障碍物，碰到或者擦边都算游戏失败。请求出小鸟从(0,0)飞到目的地最少需要点击多少次屏幕。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个整数n(0&lt;=n&lt;=500000),X(1&lt;=n&lt;=10^9)。</div>
<div>接下来n行，每行三个整数x[i],a[i],b[i](0&lt;x[i]&lt;X，-10^9&lt;=a[i]&lt;b[i]&lt;=10^9)。</div>
<div>数据保证x[i]&lt;x[i+1]。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>如果无论如何都飞不到目的地，输出NIE，否则输出点击屏幕的最少次数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 11<br/>
4 1 4<br/>
7 -1 2<br/>
8 -1 3<br/>
9 0 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/4723/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYxMS9mbGFoaW50LnBuZw==.png" width="314" height="187" alt=""/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

