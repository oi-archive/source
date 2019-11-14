
# Description

<div class="content"><div>在Byteland的首都，有一个矩形围栏围起来的公园。在这个公园里树和访客都以一个圆形表示。公园有四个出入口</div>
<div>，每个角落一个（1=左下角，2=右下角，3=右上角，4=左上角）。访客能通过这些出入口进出公园。访客在同时碰</div>
<div>到一个角落的两条边时就可以通过该角落进出公园。访客在公园里可以自由地移动，但他们不能和树和围栏相交。</div>
<div>对于每个访客，给定他们进入公园的出入口，你的任务是计算他们能在哪个出入口离开公园。</div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行包含两个整数：n,m:树的数量和访客的数量。</div>
<div>第二行包含两个整数：w,h:公园的宽和高。左下角的坐标是（0,0），右上角的坐标是（w,h）。</div>
<div>接下来的n行描述每棵树。</div>
<div>每行包含3个整数：x,y,r:树的圆心是（x,y），半径是r。每棵树都不会和其他树和围栏相交。</div>
<div>最后m行描述每个访客。每行包含2个整数：r,e：访客的半径和他们进入公园的出入口。</div>
<div>数据保证没有一棵树会和每个角落的2k*2k的方形区域相交，k是最大的访客半径。</div>
<div>1&lt;=N&lt;=2000</div>
<div>1&lt;=M&lt;=100000</div>
<div>4k&lt;w,h&lt;=10^9</div>
<p></p></div>

# Output

<div class="content"><div>对于每个访客你要输出一行，包含了他们能在哪些出入口离开公园，以从小到大的顺序输出，不需要空格分隔。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
16 11<br/>
11 8 1<br/>
6 10 1<br/>
7 3 2<br/>
10 4 1<br/>
15 5 1<br/>
1 1<br/>
2 2<br/>
2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1234<br/>
2<br/>
14</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/5183/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi92djEoMSkuanBn.jpg" width="358" height="256" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

