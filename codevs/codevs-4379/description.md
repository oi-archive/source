<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">Quack操控一套薪传地炮套牌杀入了决赛！</span></p><p><span style="">在决赛的第一局，Quack又爆出了大量费用并且拍出了精灵喷火炮。此时，他的牌库还有n张，牌库中还有m个地。他想知道</span><span style="">现在起动精灵喷火炮的</span><span style="">异能</span><span style="">所能造成的期望伤害</span><span style="">是多少</span><span style="">（即某种情况能造成的伤害与这种情况发生的概率的乘积，对所有情况求和）。</span></p><p><span style="">Quack认为海岛是最强的地，因此他的</span><span style="">牌库中的地全都不是山脉。</span></p><p><span style="">精灵喷火炮，4，神器</span><span style=""> </span><span style="">3，横</span><span style="">置：从你的牌库顶开始展示卡牌，直到展示出一张地牌为止。精灵喷火炮对目标牌手或生物造成伤害，其数值等同于以此法展示的所有非地牌数量。如果展示的地牌是一张山脉，则精灵喷火炮改为造成两倍此数量的伤害。将展示的卡牌以任意顺序放回牌库底。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">共一行，两个数n，m。</span><span style="">表示</span><span style="">Quack的牌库数量和牌库中地的数量。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体;font-size: 14px">共一行，一个数，表示期望伤害</span><span style="font-family: 宋体;font-size: 14px">，结果保留两位小数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1.00</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于10%的数据，m=1。</span></p><p><span style="">对于30%的数据，1≤n≤10。</span></p><p><span style="">对于60%的数据，1≤n≤60。</span></p><p><span style="">对于100%的数据，1≤n≤2000000000，0≤m≤n。</span></p><p><span style="">如果牌库里面没有地，那么精灵喷火炮会展示完整个牌库，然后对目标牌手或生物造成牌库数量的伤害。</span></p>
</div>
</div>