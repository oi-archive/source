
# Description

<div class="content"><div>
<div>最近，小栋在无向连通图的生成树个数计算方面有了惊人的进展，他发现：</div>
<div>·n个结点的环的生成树个数为n。</div>
<div>·n个结点的完全图的生成树个数为n^(n-2)。这两个发现让小栋欣喜若狂，由此更加坚定了他继续计算生成树个数的</div>
<div>想法，他要计算出各种各样图的生成树数目。一天，小栋和同学聚会，大家围坐在一张大圆桌周围。小栋看了看，</div>
<div>马上想到了生成树问题。如果把每个同学看成一个结点，邻座（结点间距离为1）的同学间连一条边，就变成了一</div>
<div>个环。可是，小栋对环的计数已经十分娴熟且不再感兴趣。于是，小栋又把图变了一下：不仅把邻座的同学之间连</div>
<div>一条边，还把相隔一个座位（结点间距离为2）的同学之间也连一条边，将结点间有边直接相连的这两种情况统称</div>
<div>为有边相连，如图1所示。</div>
</div>
<div><img src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8xKDEpLnBuZw==.png" width="312" height="367" alt=""/></div>
<div><img src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8xLnBuZw==.png" width="0" height="0" alt=""/></div>
<div>
<div>小栋以前没有计算过这类图的生成树个数，但是，他想起了老师讲过的计算任意图的生成树个数的一种通用方法：</div>
<div>构造一个n×n的矩阵A={aij},其中</div>
</div>
<div><img src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8yKDMpLnBuZw==.png" width="267" height="92" alt=""/></div>
<div><img src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8yKDIpLnBuZw==.png" width="0" height="0" alt=""/></div>
<div><img src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8yKDEpLnBuZw==.png" width="0" height="0" alt=""/></div>
<div><img src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8yLnBuZw==.png" width="0" height="0" alt=""/></div>
<div>
<div>其中di表示结点i的度数。与图1相应的A矩阵如下所示。为了计算图1所对应的生成数的个数，只要去掉矩阵A的最</div>
<div>后一行和最后一列，得到一个(n-1)×(n-1)的矩阵B，计算出矩阵B的行列式的值便可得到图1的生成树的个数所以</div>
<div>生成树的个数为|B|=3528。小栋发现利用通用方法，因计算过于复杂而很难算出来，而且用其他方法也难以找到更</div>
<div>简便的公式进行计算。于是，他将图做了简化，从一个地方将圆桌断开，这样所有的同学形成了一条链，连接距离</div>
<div>为1和距离为2的点。例如八个点的情形如下：</div>
</div>
<div><img src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8zKDIpLnBuZw==.png" width="469" height="94" alt=""/></div>
<div><img src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMi8zKDEpLnBuZw==.png" width="0" height="0" alt=""/></div>
<div></div>
<div></div>
<div>
<div>这样生成树的总数就减少了很多。小栋不停的思考，一直到聚会结束，终于找到了一种快捷的方法计算出这个图的</div>
<div>生成树个数。可是，如果把距离为3的点也连起来，小栋就不知道如何快捷计算了。现在，请你帮助小栋计算这类</div>
<div>图的生成树的数目。</div>
</div>
<div></div></div>

# Input

<div class="content"><p>包含两个整数k,n，由一个空格分隔。k表示要将所有距离不超过k（含k）的结点连接起来，n表示有n个结点。</p></div>

# Output

<div class="content"><p>输出一个整数，表示生成树的个数。由于答案可能比较大，所以你 只要输出答案除65521 的余数即可。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">75</span></div>

# Hint

<div class="content"><p></p><p><img border="0" src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0OTRfNC5qcGc=.jpg" alt=""/> <img border="0" src="/source/bzoj/1494/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0OTRfNS5qcGc=.jpg" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

