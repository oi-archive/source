<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>斯诺克又称英式台球，是一种流行的台球运动。在球桌上，台面四角以及两长边中心位置各有一个球洞，使用的球分别为1 个白球，15 个红球和6 个彩球（黄、绿、棕、蓝、粉红、黑）共22个球。</p>
<p>击球顺序为一个红球、一个彩球直到红球全部落袋，然后以黄、绿、棕、蓝、粉红、黑的顺序逐个击球，最后以得分高者为胜。斯诺克的魅力还在于可以打防守球，可以制造一些障碍球使对方无法击打目标球而被扣分。正是因为这样，斯诺克是一项充满神奇的运动。</p>
<p>现在考虑这样一种新斯诺克，设母球（母球即是白球，用于击打其他球）的标号为M，台面上有N 个红球排成一排，每一个红球都有一个标号，他们的标号代表了他们的分数。</p>
<p>现在用母球击打这些红球，一杆击打，如果母球接触到红球，就称为“K 到红球”。我们假设，一次可以击打任意多相邻连续的红球，也可以只击打一个球。并且红球既不会落袋，也不会相互发生碰撞，而只是停留在原处。每次击打时候，要想“K 到红球”，至少要击打一个红球，如果想一次击打多个红球，那么击打的红球必须是依次连续排列的。如果一次“K 到红球”所有红球的标号之和的平均数大于母球的标号M，就获得了一个“连击”。</p>
<p>现在请你计算总共能有多少种“连击”方案。</p>
<p>注意：如果当前有标号为1、2、3 的三种红球，母球标号为0，有如下6 种获得“连击”方案：（ 1）、（ 2）、（ 3）、（ 1，2）、（ 2，3）、（ 1，2，3）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共有两行。</p>
<p>第一行是N，M (N&lt;=100000，M&lt;=10000) ，N 表示台面上一共有N 个红球，M 表示母球的标号。</p>
<p>第二行是N 个正整数，依次表示台面上N 个红球的标号，所有标号均不超过10000。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一个数，为&ldquo;连击&rdquo;的方案总数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3</p>
<p>3 7 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>请看上面。</p>
</div>
</div>