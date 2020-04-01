
# Description

<div class="content"><div>飞飞国是一个传说中的国度，国家的居民叫做飞飞侠。飞飞国是一个N×M的矩形方阵，每个格子代表一个街区。然</div>
<div>而飞飞国是没有交通工具的。飞飞侠完全靠地面的弹射装置来移动。每个街区都装有弹射装置。使用弹射装置是需</div>
<div>要支付一定费用的。而且每个弹射装置都有自己的弹射能力。我们设第i行第j列的弹射装置有Aij的费用和Bij的弹</div>
<div>射能力。并规定有相邻边的格子间距离是1。那么，任何飞飞侠都只需要在(i,j)支付Aij的费用就可以任意选择弹</div>
<div>到距离不超过Bij的位置了。如下图</div>
<p><img border="0" src="/source/bzoj/2143/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIxNDMuanBn.jpg" alt=""/></p>
<div>（从红色街区交费以后可以跳到周围的任意蓝色街区。）现在的问题很简单。有三个飞飞侠，分别叫做X，Y，Z。</div>
<div>现在它们决定聚在一起玩，于是想往其中一人的位置集合。告诉你3个飞飞侠的坐标，求往哪里集合大家需要花的</div>
<div>费用总和最低。</div></div>

# Input

<div class="content"><div>
<div>输入的第一行包含两个整数N和M，分别表示行数和列数。</div>
<div>接下来是2个N×M的自然数矩阵，为Aij和Bij</div>
<div>最后一行六个数，分别代表X，Y，Z所在地的行号和列号。</div>
<div>1&lt;=N,M&lt;=150;0&lt;=Aij&lt;=10^9;0&lt;=Bij&lt;=1000</div>
</div></div>

# Output

<div class="content"><div>第一行输出一个字符X、Y或者Z。表示最优集合地点。</div>
<div>第二行输出一个整数，表示最小费用。如果无法集合，只输出一行NO</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
0 0 0 0<br/>
1 2 2 0<br/>
0 2 2 1<br/>
0 0 0 0<br/>
5 5 5 5<br/>
5 5 5 5<br/>
5 5 5 5<br/>
5 5 5 5<br/>
2 1 3 4 2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Z<br/>
15</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

