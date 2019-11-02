<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>很久以前，魔塔里住着一个恶魔。一天，我们伟大的英雄Doctor为了打败恶魔进入了魔塔。不幸的是，他被里面的怪物抓住了，并被投入了牢房。他在牢房中得到巫师的帮助，打开了房门，并且得到了牢房那一层的地图。巫师告诉Doctor，恶魔已经打算封锁这一层的出口，让里面的人饿死在牢房中。为了尽早以最佳状态逃出这一层。返回魔塔，Doctor带着地图一路向出口走去。</p>
<p> </p>
<p>【战斗过程】</p>
<p>Doctor和怪物分别具有能量、攻击力、防御力三种属性。怪物在地图中用数字[0到4]标示，怪物不会移动。</p>
<p>当Doctor遇到怪物时，则发生战斗，由Doctor开始攻击怪物，战斗过程如下：</p>
<p>1）怪物每次扣减能量值=Doctor-&gt;攻击力 减去 怪物-&gt;防御力，最小值为0</p>
<p>2）Doctor每次扣减能量值=怪物-&gt;攻击力 减去 Doctor-&gt;防御力，最小值为0</p>
<p>3）如果怪物能量值&gt;0 且 Doctor 能量值&gt;0，则怪物扣减能量值</p>
<p>4）如果怪物能量值&gt;0 且 Doctor 能量值&gt;0，则Doctor扣减能量值</p>
<p>5）返回第三步，直到一方能量值&lt;=0为止</p>
<p>6）如果Doctor能量值&gt;0，则Doctor胜利，否则怪物胜利</p>
<p> </p>
<p>【恢复物品】</p>
<p>恢复物品有三种，在地图中用 [A]、[B]、[C] 标示，在地图中最多出现1个，只能使用一次，当Doctor走到恢复物品时，</p>
<p>[A] 能量 + P<br>        [B] 攻击力 + Q<br>        [C] 防御力 + R</p>
<p>【地图标示】</p>
<p>  [#] 表示一堵墙（Doctor是不会穿墙术的）<br>          [.] 表示一块空地。<br>          [S] 表示Doctor的初始位置。<br>          [E] 表示出口<br>          [0 - 4] 表示各怪物。<br>          [A - C] 表示属性增加地点。</p>
<p>【移动】</p>
<p> Doctor 每次可以向上、下、左、右四个方向移动一格，消耗一个单位时间，Doctor在战斗时不消耗额外时间。</p>
<p>Doctor不能移动到墙壁，也不能移动到地图之外。</p>
<p>如果无法战胜怪物，则Doctor不能向那个怪物移动。怪物被消灭后不会再生，其所在格子变为空地。</p>
<p> </p>
<p>【目标】</p>
<p>Doctor需要尽快达到出口，且需要保留较大能量应付接下去的战斗。其指标为到达出口后， 能量 / 时间 为最大值。</p>
<p> </p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> </p>
<p> </p>
<p>第一行有六个整数W (1 &lt;= W &lt;= 20), H (1 &lt;= H &lt;= 20), P (1 &lt;= P &lt;= 10), Q (1&lt;= Q &lt;= 10), R (1 &lt;= R &lt;= 10), M (0 &lt;= M &lt;= 5). 迷宫是由一个W*H的矩形区域构成（W为竖排数目，H为横排数目）。M表示怪物的数量。</p>
<p>其后一行有三个整数，表示Andy的能量，攻击力，和防御力。</p>
<p>其后M行，每行有四个整数，表示怪物的编号，和这个怪物的能量，攻击力，和防御力。</p>
<p>人物和怪物的属性整数范围为[ 0 , 10000 ]</p>
<p>输入数据保证Doctor能到达出口。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 10px;">&nbsp; 输出 Doctor 到达出口时的能量和所需时间，中间用空格隔开。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 5 10 10 10 1</p>
<p>#####</p>
<p>#SAB#</p>
<p>#0###</p>
<p>#C.E#</p>
<p>#....#</p>
<p>#####</p>
<p>10 1 1</p>
<p>0 10 10 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>W (1 &lt;= W &lt;= 20),</p>
<p>H (1 &lt;= H &lt;= 20),</p>
<p>P (1 &lt;= P &lt;= 10),</p>
<p>Q (1&lt;= Q &lt;= 10),</p>
<p>R (1 &lt;= R &lt;= 10),</p>
<p>M (0 &lt;= M &lt;= 5)</p>
</div>
</div>