<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>恩爱狗邀请单身狗们答题，答题将会获得狗粮一份，你们准备好了吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="">这是一个装逼游戏，有</span>N*N<span style="">的szt站在方阵中，每个szt都有自己血量，经过一轮轮战斗，直到没有战斗发生，则战斗结束。</span></span></p><p style=""><span style=""><span style="">每一轮的战斗要求：</span></span></p><p style=""><span style=""><span style="">每一轮中，每个存活的szt可以向自己周围（顺序：左上、上、右上、左、右、左下、下、右下）任意一个存活的zq（szt）挑战，每轮只有</span>1<span style="">次发起的机会，如果自己血量大于对方的血量，则为赢。如果被挑战的人血量有相同的，则必须按照上面顺序选择最先的一个。  在本轮之后将掠夺到对方的血量三分之一，自己血量将增加掠夺到的血量（掠夺血量向上取整，例如：</span><span style="font-family: Calibri;">0.1 </span><span style="">则计算成一个血量），对方减去一半血量（向上取整</span><span style="font-family: Calibri;">0.5</span><span style="">算</span><span style="font-family: Calibri;">1</span><span style="">）。每轮结束之后进行血量评估，在本次战斗中血量为</span><span style="font-family: Calibri;">0</span><span style="">或负数的，则死亡。血量相同，则不产生战斗。</span></span></p><p style=""><span style=""> </span></p><p style=""><span style=""><span style="">为了自己的幸福（生存），你当然要选择一个最好打赢的人进行挑战，当然，如果你发现周围的都打不过，你可以选做不发起挑战。</span></span></p><p style=""><span style=""> </span></p><p style=""><span style="">输出：最后存活的szt数量，以及战场分布图，死亡的展示血量用</span><span style="">0</span><span style="">表示。</span></p><p style=""><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体; font-size: 14px;">输入：</span><span style="font-family: 宋体; font-size: 14px;">N</span><span style="font-family: 宋体; font-size: 14px;">，之后战场分布图，按照位置的</span><span style="font-size: 14px; font-family: Calibri;">N*N</span><span style="font-family: 宋体; font-size: 14px;">的战士的血量。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">3</span></p><p style=""><span style="">9</span> <span style="font-family: Calibri;">    </span><span style="">10</span><span style="font-family: Calibri;"> </span>  <span style="">9</span></p><p style=""><span style="">8</span><span style="">  </span> <span style="">9</span><span style=""> </span>  <span style="">1</span><span style="">    </span></p><p><span style="">  1</span><span style="">        </span><span style="">2</span><span style="">           </span><span style="">3</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13</p><p>0 36 0</p><p>0 0 0</p><p>0 0 3</p><p><br></p>

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