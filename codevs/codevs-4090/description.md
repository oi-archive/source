<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>   小明历经千辛万苦终于到达了紫禁之巅，在即将获取紫禁之巅令牌的时候，有n个boss出来拦路，小明必须打到他们才能拿到，此时小明已经身心皆惫，剩下k瓶回复血的药剂和L瓶回复魔的药剂（每瓶回复30点），以及p个技能（每次发技能都要消耗魔）；boss也不是吃素的，小明能不能打败它们呢，如果能，输出最大剩余血量和魔力，以及击败boss的总回合数（回合数优先，再到血，最后魔力）；如果不能则输出boss剩余最少的总血量，以及总回合数。（注：小明和boss们都有护甲值R，能抵消R%的伤害，每人每回合只能进行一次行动，boss是一个一个上的。小明先手）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入：小明的技能数量，两种药剂的数量，boss的数量</p><p>第二行输入：小明的血量，魔力，攻击，护甲值，</p><p>第三行输入：小明每个技能的消耗的魔力和伤害值</p><p>第四至N行输入：boss的血量，攻击，护甲值</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行输出：小明剩余的血量和魔力或boss总剩余的血量</p><p>第二行输出：回合数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3 2 1</p><p>90 90 10 10</p><p>20 25 15 15<br></p><p>100 15 10</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12 0<br></p><p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>         小明血      魔      boss血</p><p>第一次    76.5       65       82       使用技能1<br></p><p>第二次    63         40       64       使用技能1</p><p>第三次    49.5       15       46       使用技能1</p><p>第四次    36         0        32.5     使用技能2</p><p>第五次    22.5       30       32.5     使用魔力瓶</p><p>第六次    39         30       32.5     使用血瓶</p><p>第七次    25.5       15       19       使用技能2</p><p>第八次    12          0       5.5      使用技能2</p><p>第九次    12          0        0       使用普攻（小明先手）</p><p>数据范围未知</p><p>原本还想加暴击和反弹的，可是太麻烦了，所以。。。。免了</p>
</div>
</div>