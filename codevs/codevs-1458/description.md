<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">写一个程序，可以供两个玩家玩的游戏，玩纸牌。有52张卡：2,3,4,5,6,7,8,9,10 ，J ,Q,K ,A 每样四张. 其中J,Q,K,A这四张被称为高分牌。洗牌后将牌面朝下扣在桌上，玩家A翻开最上面的牌，并把它放在一堆;然后玩家B翻开剩下最上面的牌，并把它放在那一堆。 A和B轮流这样，直到没牌为止。比赛得分方法如下：</p><p style="">如果玩家翻开A，要再翻4张牌，如果接下来的4张牌都不是高分牌，该玩家得4分</p><p style="">如果玩家翻开K，要再翻3张卡，如果接下来的3张牌都不是高分牌，该玩家得3分</p><p style="">如果玩家翻开Q，要再翻2张卡，如果接下来的2张牌都不是高分牌，该玩家得2分</p><p style="">如果玩家翻开J，要再翻1张卡，如果接下来的1张牌都不是高分牌，该玩家得1分</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件将包含52行，每一行为一张牌的名称（小写字母）。第一行是指第一张卡；下一行的时下一张牌。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-align:left;">每当有玩家得分，像这样打印：</p><p style="text-align:left;">Player X scores n point(s).</p><p>其中X是玩家的名字（A或B）而N是得了多少分（1，2，3，4）。在结束时打印</p><p>游戏的总成绩，打印每个球员的分数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">three</p><p style="">seven</p><p style="">queen</p><p style="">eight</p><p style="">five</p><p style="">ten</p><p style="">king</p><p style="">eight</p><p style="">jack</p><p style="">queen</p><p style="">six</p><p style="">queen</p><p style="">jack</p><p style="">eight</p><p style="">seven</p><p style="">three</p><p style="">ten</p><p style="">four</p><p style="">king</p><p style="">nine</p><p style="">six</p><p style="">seven</p><p style="">ace</p><p style="">four</p><p style="">jack</p><p style="">ace</p><p style="">ten</p><p style="">nine</p><p style="">ten</p><p style="">queen</p><p style="">ace</p><p style="">king</p><p style="">seven</p><p style="">two</p><p style="">five</p><p style="">two</p><p style="">five</p><p style="">nine</p><p style="">three</p><p style="">king</p><p style="">six</p><p style="">eight</p><p style="">jack</p><p style="">six</p><p style="">five</p><p style="">four</p><p style="">two</p><p style="">ace</p><p style="">four</p><p style="">three</p><p style="">two</p><p style="">nine</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">Player A scores 2 point(s).</p><p style="">Player A scores 1 point(s).</p><p style="">Player A scores 3 point(s).</p><p style="">Player B scores 3 point(s).</p><p style="">Player A scores 1 point(s).</p><p style="">Player B scores 4 point(s).</p><p style="">Player A: 7 point(s).</p><p>Player B: 7 point(s).</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>无</p>
</div>
</div>