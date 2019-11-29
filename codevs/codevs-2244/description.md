<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>沫沫最近在玩一个二维的射箭游戏，如下图1所示，这个游戏中的x轴在地面，第一象限中有一些竖直线段作为靶子，任意两个靶子都没有公共部分，也不会接触坐标轴。</p>
<p>沫沫控制一个位于(0,0)的弓箭手，可以朝0至90°中的任意角度（不包括0°和90°），以任意大小的力量射出带有穿透能力的光之箭。由于游戏中没有空气阻力，并且光之箭没有箭身，箭的轨迹会是一条标准的抛物线，被轨迹穿过的所有靶子都认为被沫沫射中了，包括那些只有端点被射中的靶子。</p>
<p>这个游戏有多种模式，其中沫沫最喜欢的是闯关模式。在闯关模式中，第一关只有一个靶子，射中这个靶子即可进入第二关，这时在第一关的基础上会出现另外一个靶子，若能够一箭双雕射中这两个靶子便可进入第三关，这时会出现第三个靶子。依此类推，每过一关都会新出现一个靶子，在第K关必须一箭射中前K关出现的所有K个靶子才能进入第K+1关，否则游戏结束。</p>
<p>沫沫花了很多时间在这个游戏上，却最多只能玩到第七关“七星连珠”，这让她非常困惑。</p>
<p>于是她设法获得了每一关出现的靶子的位置，想让你告诉她，最多能通过多少关。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行是一个正整数<span>N</span>，表示一共有<span>N</span>关。</span></p>
<p><span>接下来有<span> N</span>行，第<span>i+1</span>行是用空格隔开的三个正整数<span>x</span></span><sub><span>i</span></sub><span>，<span>y</span></span><sub><span>i1</span></sub><span>，<span>y</span></span><sub><span>i2</span></sub><span>(y</span><sub><span>i1</span></sub><span>&lt;y</span><sub><span>i2</span></sub><span>)</span><span>，表示第<span>i</span>关出现的靶子的横坐标是<span>x</span></span><sub><span>i</span></sub><span>，纵坐标的范围是从<span>y</span></span><sub><span>i1</span></sub><span>到<span>y</span></span><sub><span>i2</span></sub><span>。 </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅包含一个整数，表示最多的通关数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>2 8 12<br>5 4 5<br>3 8 10<br>6 2 3<br>1 3 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong><span>样例说明</span></strong></p>
<p><span>如图，可射到前三关的靶子。</span></p>
<p><span><img height="497" src="/source/codevs/codevs-2244/img/aHR0cDovL3AxMy5mcmVlcC5jbi9wLmFzcHg_dT12MjBfcDEzX3Bob3RvXzEzMDUwMTEwNDcyMTkxMDhfMC5qcGc=.jpg" width="284"></span></p>
<p><strong><span>数据范围</span></strong></p>
<p><span>30%</span><span>的数据满足<span>N≤100</span>，<span>50%</span>的数据满足<span>N≤5000</span>，<span>100%</span>的数据满足<span>N≤100000</span>且给出的所有坐标不超过<span>10</span></span><sup><span>9</span></sup><span>。</span></p>
</div>
</div>