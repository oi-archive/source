
# Description

<div class="content"><div><span style="font-size: medium">       为了奖励习得最短路算法的自己，和安慰在与你的比赛中成功爆零的自己，小Y决定去旅行。</span><span style="font-size: medium">       根据导游的解释，旅行的地图是一个无向连通图，可以看作两部分：大地图和小地图。在大地图中，共有N个点，M条边，其中宾馆在点1，<b>小</b><b>Y</b><b>固定从宾馆开始旅行，并在旅行后回到宾馆</b>。</span><span style="font-size: medium">       对于大地图中的每条边的两个端点u和v，对应着某个小地图中的两个点u’和v’。经过大地图中的边&lt;u,v&gt;的过程可以这么描述，从大地图中的u点到达小地图中的u’点，通过小地图再到v’点，然后回到v点。也就是说，大地图中的一条边是一个小地图。</span></div>
<div><span style="font-size: medium">       坑爹的是，由于造路的人偷工减料，导致所有的小地图都是相同的，且大地图中的每一个点，都对应着小地图中的同一个点（可能出现大地图中不同点对应小地图中同一个点的情况）。</span></div>
<div><span style="font-size: medium">       不过，优美的是，在小地图中，你总能找到一个点，使得从这个点开始，能毫不遗漏又毫不重复地走完所有的边。</span></div>
<div><span style="font-size: medium">       通过上述描述，就构成了一个全局图（图套图？）。在全局图中，两条边被认为是相同的情况只有：两条边是大地图的同一条边对应的小地图中的同一条边。</span></div>
<div><span style="font-size: medium">       小Y表示他对大地图、小地图什么的表示毫无兴趣。他只想好好地旅行。但是，经过相同的道路会让他感到很无趣。<b>所以，每当他经过一条乐趣值为</b><b>w</b><b>的边时，总乐趣值+w</b><b>，并且这条边的乐趣值会变为-w</b>。</span></div>
<div><span style="font-size: medium">       但是小Y不知道怎么样走才能使自己最快乐，即总乐趣值最高。所以他想请你帮他算一下，最高的总乐趣值。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">       第一行两个正整数N,M,P,Q分别表示大地图中的点数和边数、小地图中的点数和边数。</span></div>
<div><span style="font-size: medium">       接下来一行N个整数，第i个整数表示大地图中编号为i的点对应在小地图中的点的编号。</span></div>
<div><span style="font-size: medium">       接下来M行，每行两个整数u,v。表示大地图中有一条编号为u的点到编号为v的点的边。</span></div>
<div><span style="font-size: medium">       接下来Q行，每行三个整数x,y,w。表示小地图中有一条编号为x的点到编号为y的点的边，且初始乐趣值为w。</span></div>
<div><span style="font-size: medium">       输入数据保证：1.大地图和小地图中无自环；2.大地图中点的编号为1-N，小地图中点的编号为1-P。3.对于大地图中的任意一条边&lt;u,v&gt;，都有点u,v在小地图中对应着不同的点。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">       一行一个整数Ans，表示最高的总乐趣值。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 3 3 3<br/>
1 2 1 1<br/>
1 2<br/>
2 3<br/>
2 4<br/>
1 2 1<br/>
2 3 1<br/>
1 3 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p></p><div>100%的数据保证N&lt;=10000，1&lt;=w&lt;=10000。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

