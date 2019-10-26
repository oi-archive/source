
# Description

<div class="content"><p><span style="font-size: medium"><img alt="" src="/source/bzoj/2387/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNy9lMS5qcGc=.jpg"/></span></p>
<div>格丁尼亚的中心位于Kacza河中的一座岛屿。每天清晨，成千上万辆汽车通过岛屿从西岸的住宅区（由桥连接岛的</div>
<div>西部）到东岸的工业区（由桥连接岛的东部）。该岛类似于矩形，它的边平行于主方向。故可将它看作是笛卡尔坐</div>
<div>标系中的一个A*B的矩形，它的对角分别为（0, 0）和（A, B）。岛上有n个交通节点，编号为1…n（junction, 此</div>
<div>处可理解为广义的路口），第i个节点坐标为(xi, yi)。如果一个节点的坐标为(0, y)，它就位于岛的西岸。类似</div>
<div>的，坐标为(A, y)的节点位于岛的东岸。各个节点由街道连接，每条街道用线段连接两个节点。街道有单向行驶或</div>
<div>双向行驶之分。除端点外任意两条街道都没有公共点。也没有桥梁或者隧道。你不能对道路网络形状做任何其他假</div>
<div>设。沿河岸的街道或节点可能没有入口或者出口街道。由于交通堵塞日趋严重，市长聘请你测试岛上当前的道路网</div>
<div>是否足够。要求你写一个程序确定从岛的西岸的每个节点能够到达东岸的多少个节点。</div></div>

# Input

<div class="content"><p><img alt="" src="/source/bzoj/2387/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNy9lMi5qcGc=.jpg"/></p>
<div>第1行包含4个整数n, m, A, B(1≤n≤300000, 0≤m≤900000,1≤A,B≤109)，</div>
<div>分别表示格丁尼亚市中心的节点数，街道数和岛屿的尺寸。</div>
<div>接下来的n行，每行包含两个整数xi，yi (0≤xi≤A,0≤yi≤B)，表示第i个节点的坐标。任意两个节点的坐标都不相同。</div>
<div>再往下的m行表示街道，每条街道用3个整数ci, di, ki（1≤ci, di≤n, ci≠di, ki∈{1,2}），</div>
<div>表示节点ci、di有街道连接</div>
<div>如果ki=1,表示从ci到di的街道是单向的，否则，这条街道可以双向行驶。每个无序对{ci, di}最多出现1次。</div>
<div>你可以假设西岸节点中至少有1个能够到达东岸的一些节点。</div></div>

# Output

<div class="content"><p><img height="100" alt="" width="886" src="/source/bzoj/2387/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNy9lMy5qcGc=.jpg"/></p>
<p><font size="4">为每个西岸节点输出1行，包括从这个节点出发能够到达东岸的节点数目</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 1 3<br/>
0 0<br/>
0 1<br/>
0 2<br/>
1 0<br/>
1 1<br/>
1 4 1<br/>
1 5 2<br/>
3 5 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
0<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

