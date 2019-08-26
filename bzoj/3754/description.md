
# Description

<div class="content"><div>Wayne在玩儿一个很有趣的游戏。在游戏中，Wayne建造了N个城市，现在他想在这些城市间修一些公路，当然并不是任意两个城市间都能修，为了道路系统的美观，一共只有M对城市间能修公路，即有若干三元组 (Ui,Vi,Ci)表示Ui和Vi间有一条长度为Ci的双向道路。当然，游戏保证了，若所有道路都修建，那么任意两城市可以互相到达。Wayne拥有恰好N-1支修建队，每支队伍能且仅能修一条道路。当然，修建长度越大，修建的劳累度也越高，游戏设定是修建长度为C的公路就会有C的劳累度。当所有的队伍完工后，整个城市群必须连通，而这些修建队伍们会看看其他队伍的劳累情况，若劳累情况差异过大，可能就会引发骚动，不利于社会和谐发展。Wayne对这个问题非常头疼，于是他想知道，这N1支队伍劳累度的标准差最小能有多少。</div>
<div>标准差的定为：设有N个数，分别为ai,它们的平均数为<img src="source/bzoj/3754/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQxMS9hYSgxKS5qcGc=.jpg" width="36" height="44" alt=""/> ,那么标准差就是</div>
<div></div>
<div><img src="source/bzoj/3754/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQxMS9iYigxKS5qcGc=.jpg" width="201" height="87" alt=""/></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行两个正整数N,M</div>
<div>接下来M行，每行三个正整数Ui,Vi,Ci</div>
</div>
<div>
<p></p>
</div></div>

# Output

<div class="content"><div>
<div>输出最小的标准差，保留四位小数。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 2 1<br/>
2 3 2<br/>
3 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.5000</span></div>

# Hint

<div class="content"><p></p><div>N&lt;=100,M&lt;=2000,Ci&lt;=100</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

