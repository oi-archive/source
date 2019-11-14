<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>N<span style="">个人坐成一圈玩游戏。一开始我们把所有玩家按顺时针从</span>1<span style="">到</span>N<span style="">编号。首先第一回合是玩家</span>1<span style="">作为庄家。每个回合庄家都会随机（即按相等的概率）从卡牌堆里选择一张卡片，假设卡片上的数字为</span>X<span style="">，则庄家首先把卡片上的数字向所有玩家展示，然后按顺时针从庄家位置数第</span>X<span style="">个人将被处决即退出游戏。然后卡片将会被放回卡牌堆里并重新洗牌。被处决的人按顺时针的下一个人将会作为下一轮的庄家。那么经过</span>N-1<span style="">轮后最后只会剩下一个人，即为本次游戏的胜者。现在你预先知道了总共有</span>M<span style="">张卡片，也知道每张卡片上的数字。<span style="">现在你需要确定每个玩家</span><strong><span style="">胜出的概率</span></strong><span style="">。</span></span></p><p><span style=""><br></span></p><p><span style="">这里有一个简单的例子：</span></p><p><span style="">例如一共有</span>4<span style="">个玩家，有四张卡片分别写着</span>3,4,5,6.</p><p><span style="">第一回合，庄家是玩家</span>1<span style="">，假设他选择了一张写着数字</span>5<span style="">的卡片。那么按顺时针数</span>1,2,3,4,1<span style="">，最后玩家</span>1<span style="">被踢出游戏。</span></p><p><span style="">第二回合，庄家就是玩家</span>1<span style="">的下一个人，即玩家</span>2.<span style="">假设玩家</span>2<span style="">这次选择了一张数字</span>6<span style="">，那么</span>2,3,4,2,3,4<span style="">，玩家</span>4<span style="">被踢出游戏。</span></p><p><span style="">第三回合，玩家</span>2<span style="">再一次成为庄家。如果这一次玩家</span>2<span style="">再次选了</span>6<span style="">，则玩家</span>3<span style="">被踢出游戏，最后的胜者就是玩家</span>2.</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行包括两个整数</span>N,M<span style="">分别表示玩家个数和卡牌总数。</span></p><p><span style="">接下来一行是包含</span>M<span style="">个整数，分别给出每张卡片上写的数字。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">输出一行包含</span>N<span style="font-family:宋体">个百分比形式给出的实数，四舍五入到两位小数。分别给出从玩家</span>1<span style="font-family:宋体">到玩家</span>N<span style="font-family: 宋体">的胜出概率，每个概率之间用空格隔开。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New';">5 5<br> 2 3 5 7 11</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New';">22.72% 17.12% 15.36% 25.44% 19.36%</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于</span>20%<span style="">的数据，有</span>1&lt;=N&lt;=10 1&lt;=M&lt;=50 1&lt;=<span style="">每张卡片上的数字</span>&lt;=50</p><p><span style="">对于</span>40%<span style="">的数据，有</span>1&lt;=N&lt;=30 1&lt;=M&lt;=50 1&lt;=<span style="">每张卡片上的数字</span>&lt;=50</p><p><span style="">对于</span><span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，有</span><span style="font-family: 'Times New Roman';">1&lt;=N&lt;=50 1&lt;=M&lt;=50 1&lt;=</span><span style="">每张卡片上的数字</span><span style="font-family: 'Times New Roman';">&lt;=50</span></p><p><br></p>
</div>
</div>