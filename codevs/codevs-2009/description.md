<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>话说退役后的生活好无聊啊，以至于shit神整天都在闭门修炼dota，但是Sure就是不会dota也不想学。有一天也Sure无聊了，就把自己设置成dota中最牛X的英雄。于是……</p>
<p>Sure成了万众瞩目的大dota英雄！！！</p>
<p>Sure手里有n种刀，并且每种刀的个数没有上限，但是Sure不想让他太厉害了，所以他约束自己同一种类的刀至多携带一把，并且要时刻保证手中刀的个数不能超过k。假设一场游戏中Sure会至多遇到m种怪，用不同的刀砍不同的怪造成的杀伤不同，砍之后这把刀就消失了，每遇到一个怪Sure可以选择装备一种刀或者去砍怪或者什么都不做（选择之后就不能对这个怪再做任何事情了），Sure想知道一场游戏下来能造成的最大杀伤是多少。开始Sure手中什么都没有(可以连续砍怪，也可以连续装备武器)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>每组case第一行为n m k，接下来n行，每行m个数表示第i种刀分别对m种怪的杀伤w，然后为q ,最后q个数字表示Sure遇到的怪顺序。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组case输出Sure能造成的最大杀伤。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 2</p>
<p>10 20 30</p>
<p>20 30 40</p>
<p>30 40 20</p>
<p>6</p>
<p>1 1 2 2 3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>110</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>20%的数据中1&lt;=n&lt;=2,1&lt;=m&lt;=10, 1&lt;=k&lt;=n ,1&lt;=q&lt;=10, 1&lt;=w&lt;=100;</p>
<p>40%的数据中1&lt;=n&lt;=4,1&lt;=m&lt;=10, 1&lt;=k&lt;=n ,1&lt;=q&lt;=100, 1&lt;=w&lt;=100;</p>
<p>100%的数据中1&lt;=n&lt;=10,1&lt;=m&lt;=1000, 1&lt;=k&lt;=n ,1&lt;=q&lt;=1000, 1&lt;=w&lt;=100;</p>
</div>
</div>