<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>N个人坐成一圈玩游戏。一开始我们把所有玩家按顺时针从1到N编号。首先第一回合是玩家1作为庄家。每个回合庄家都会随机（即按相等的概率）从卡牌堆里选择一张卡片，假设卡片上的数字为X，则庄家首先把卡片上的数字向所有玩家展示，然后按顺时针从庄家位置数第X个人将被处决即退出游戏。然后卡片将会被放回卡牌堆里并重新洗牌。被处决的人按顺时针的下一个人将会作为下一轮的庄家。那么经过N-1轮后最后只会剩下一个人，即为本次游戏的胜者。现在你预先知道了总共有M张卡片，也知道每张卡片上的数字。现在你需要确定每个玩家胜出的概率。</p>
<p>这里有一个简单的例子：</p>
<p>例如一共有4个玩家，有四张卡片分别写着3,4,5,6.</p>
<p>第一回合，庄家是玩家1，假设他选择了一张写着数字5的卡片。那么按顺时针数1,2,3,4,1，最后玩家1被踢出游戏。</p>
<p>第二回合，庄家就是玩家1的下一个人，即玩家2.假设玩家2这次选择了一张数字6，那么2,3,4,2,3,4，玩家4被踢出游戏。</p>
<p>第三回合，玩家2再一次成为庄家。如果这一次玩家2再次选了6，则玩家3被踢出游戏，最后的胜者就是玩家2.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包括两个整数N,M分别表示玩家个数和卡牌总数。</p>
<p>接下来一行是包含M个整数，分别给出每张卡片上写的数字。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行包含N个百分比形式给出的实数，四舍五入到两位小数。分别给出从玩家1到玩家N的胜出概率，每个概率之间用空格隔开，最后不要有空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>输入样例1：</p>
<p>5 5</p>
<p>2 3 5 7 11</p>
<p>输入样例2：</p>
<p>4 4</p>
<p>3 4 5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>输出样例1：</p>
<p>22.72%  17.12%  15.36%  25.44%  19.36%</p>
<p>输出样例2：</p>
<p>25.00%  25.00%  25.00%  25.00%</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，有1&lt;=N&lt;=10</p>
<p>对于50%的数据，有1&lt;=N&lt;=30</p>
<p>对于100%的数据，有1&lt;=N&lt;=50 1&lt;=M&lt;=50 1&lt;=每张卡片上的数字&lt;=50</p>
<p> </p>
</div>
</div>