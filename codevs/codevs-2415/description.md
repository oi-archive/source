<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>lxhgww最近迷上了一款游戏，在游戏里，他拥有很多的装备，每种装备都有2个属性，这些属性的值用[1,10000]之间的数表示。当他使用某种装备时，他只能使用该装备的某一个属性。并且每种装备最多只能使用一次。</p>
<p>游戏进行到最后，lxhgww遇到了终极boss，这个终极boss很奇怪，攻击他的装备所使用的属性值必须从1开始连续递增地攻击，才能对boss产生伤害。也就是说一开始的时候，lxhgww只能使用某个属性值为1的装备攻击boss，然后只能使用某个属性值为2的装备攻击boss，然后只能使用某个属性值为3的装备攻击boss……以此类推。</p>
<p>现在lxhgww想知道他最多能连续攻击boss多少次？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是一个整数N，表示lxhgww拥有N种装备</p>
<p>接下来N行，是对这N种装备的描述，每行2个数字，表示第i种装备的2个属性值</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行，包括1个数字，表示lxhgww最多能连续攻击的次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 2</p>
<p>3 2</p>
<p>4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>    对于30%的数据，保证N&lt;=1000</p>
<p>    对于100%的数据，保证N&lt;=1000000</p>
</div>
</div>