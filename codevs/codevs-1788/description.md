<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>千年虫是远古时代的生物，时隔几千万年，千年虫早已从地球上销声匿迹， 人们对其知之甚少。考古生物学家最近开始对其有了兴趣，因为一批珍贵的千年 虫化石被发现，这些化石保留了千年虫近乎完整的形态。 理论科学家们根据这些化石归纳出了千年虫的一般形态特征模型，并且据此 判定出千年虫就是蜈蚣的祖先！但科学家 J 发现了实际与理论的一些出入，他仔 细的研究了上百个千年虫化石，发现其中大部分千年虫的形态都不完全符合理论 模型，这到底是什么因素造成的呢？理论科学家 K 敏锐的指出，千年虫的形态 保存在化石中很有可能发生各种变化，即便最细微的变化也能导致它不符合模 型。 于是，摆在科学家面前的新问题诞生了：判断一个化石中的千年虫与理论模 型的差距有多大？具体来说，就是根据一个千年虫化石的形态 A，找到一个符合 理论模型的形态 B，使 得 B 是最有可能在形成化石时变成形态 A。 <br>理论学家提出的“千年虫形态特征模型” 如下（如右图所示）：躯体由头、尾、躯干、 足四大部分构成。 1.头，尾用一对平行线段表示。称平行于 头、尾的方向为 x 方向；垂直于 x 的方向为 y 方向； 2.在头尾之间有两条互不相交的折线段相 连，他们与头、尾两条线段一起围成的区域称 为躯干，两条折线段都满足以下条件：拐角 均为钝角或者平角，且包含奇数条线段，从 上往下数的奇数条垂直于 x 方向。 3.每条折线段从上往下数的第偶数条线段 的躯干的另一侧长出一条足，即一个上、下 底平行于 x 方向的梯形或矩形，且其中远离躯干一侧的边垂直于 x 方向。 注意：足不能退化成三角形（即底边的长度均大于零），躯干两侧足的数目 可以不一样。（如上图，左边有 4 条足，右边有 5 条足） <br>可见，x-y 直角坐标系内，躯干和所有足组成的实 心区域的边界均平行或垂直于坐标轴。为了方便，我 们假设所有这些边界的长度均为正整数。因此可以认 为每个千年虫的躯体都由一些单位方格拼成。每个单 位方格都由坐标(x,y)唯一确定。设头尾之间的距离为 n，则我们可以用 2×n 个整数来描述一条千年虫 B（如 右图）：将 B 沿平行 x 轴方向剖分成 n 条宽度为 1 的横条，每个横条最左边一格的 x 坐标设为 Li，最右一格的的 x 坐标设为 Ri。则 (n,L1,L2,..,Ln,R1,R2,..Rn)就确定了一条千年虫。 由于岁月的侵蚀，在实际发现的化石中，千年虫的形状并不满足上面理论模 型的规则，一些格子中的躯体已经被某些矿物质溶解腐蚀了。 地质、物理、生物学家共同研究得出： 1、腐蚀是以格子为单位的，只能一整格被腐蚀； 2、腐蚀是分步进行的，每一步只有一格被腐蚀； 3、如果去掉一个格子后躯体不连通了，那么这个格子当前不会被腐蚀； 4、如果一个格子的左边邻格和右边邻格都还没被腐蚀，那么这个格子当前 不会被腐蚀； 5、与头相邻的格子不能全部被腐蚀，与尾相邻的格子不能全部被腐蚀； 倘若满足上面五条，我们仍然可以用(n,L’1,L’2,..,L’n,R’1,R’2,..R’n)来描述一个 化石里头的千年虫的形态。其中 L’i≤R’i。 </p>
<p>现在你的任务是，输入一个化石里的千年虫的描述 A&lt;n,L’,R’&gt;，找一个满足 理论模型的千年虫的描述 B&lt;n,L,R&gt;，使得 B 可以通过腐蚀过程得以变为 A，且 由 B 转化为 A 的代价(须被腐蚀的格子数)最少。输出此最小代价。</p>

<img src="/source/codevs/codevs-1788/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzg4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc4OC5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个整数 n；</p>
<p> 以下 n 行，每行两个整数，其中第 i 行为两个整数 L’i,R’i，用一个空格分开；</p>
<p>保证输入数据合法。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，为一个整数，表示最少代价。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>4 4</p>
<p>3 4  </p>
<p>3 5</p>
<p>1 3</p>
<p>2 2</p>
<p>2 4</p>
<p>3 3 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据 n≤100, 0≤L’i≤R’i≤100</p>
<p>50%的数据 n≤1000, 0≤L’i≤R’i≤1000</p>
<p>70%的数据 n≤100000, 0≤L’i≤R’i≤1000</p>
<p>100%的数据 n≤1000000, 0≤L’i≤R’i≤1000000</p>
</div>
</div>