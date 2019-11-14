# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
Attack(李超)
</div>
<div style="text-align:center;font-size:14px;font-weight:bold;vertical-align:middle;" id="pres">
时间限制：10.0s   内存限制：512.0MB
</div>
<div id="psrc" style="margin-top:20px;display:block;">
<h3>
【试题来源】
</h3>
<div class="pdcont">
2012集训队互测-李超
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
chnlich非常喜欢玩三国志这款游戏，并喜欢用一些策略出奇制胜。现在，他要开始征服世界的旅途了。<br/>
他的敌人有N座城市和N个太守，N个城市可以看作在二维平面上的N个点。<br/>
N座城市的标号为0,1,2,……,N-1。<br/>
第i座城市的坐标为(Xi,Yi)，镇守这座城市的太守的能力值为Zi。<br/>
chnlich每次会选择一个边平行于坐标轴的矩形区域，并奇袭其中太守能力值第K小的城市(奇袭结束之后城市与太守依然存在)。<br/>
不过，他的敌人经常会偷偷交换两座城市的太守，防止弱点被chnlich发现。<br/>
现在，chnlich想要知道，每次奇袭时他的敌人的能力值。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含两个整数N,M，N表示城市与太守的个数，M表示接下来发生了M个事件。<br/>
输入的第二行到第N+1行，每行包含三个整数，第i+2行的三个整数依次表示编号为i的城市的Xi,Yi,Zi，含义如题所述。<br/>
输入的第N+2行到第N+M+1行，每行有两种可能形式：<br/>
第一种<br/>
QUERY x0 y0 x1 y1 k<br/>
表示chnlich询问一个相对顶点为(x0,y0),(x1,y1)的矩形中，第k小能力值太守的能力值。<br/>
第二种<br/>
SWAP x y<br/>
表示chnlich的敌人交换了编号为x和y两座城市的太守。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
对于每一个QUERY，输出一行。<br/>
若不存在第k小能力值的太守，输出&#34;It doesn&#39;t exist.&#34;(不包含引号)。<br/>
否则输出一个整数，表示矩形内能力值第k小太守的能力值。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
3 5<br/>
1 1 1<br/>
2 2 2<br/>
3 3 3<br/>
QUERY 1 1 3 3 3<br/>
SWAP 0 1<br/>
QUERY 2 2 4 4 1<br/>
SWAP 2 2<br/>
QUERY 2 2 3 3 3<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
3<br/>
1<br/>
It doesn&#39;t exist.<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于30%的数据，N,M&lt;=1000;<br/>
对于40%的数据，N&lt;=30000;<br/>
另有10%的数据，不存在SWAP操作;<br/>
另有10%的数据，QUERY操作次数&lt;=2;<br/>
另有10%的数据，所有城市的Y坐标都相等，且询问中矩形的Y坐标与所有城市的Y坐标均相等;<br/>
对于100%的数据，N&lt;=60000,M&lt;=10000,0&lt;=Xi,Yi,Zi&lt;=10^9,k&lt;=10^9，保证所有操作均合法。<br/>
</div>
</div>
