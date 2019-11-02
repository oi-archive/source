<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>听说公主被关押在城堡里，彭大侠下定决心：不管一路上有多少坎坷，不管城堡中的看守有多少厉害，不管救了公主之后公主会不会再被抓走，不管公主是否漂亮、是否会钟情于自己，他将义无反顾地朝着城堡前进。</span></p>
<p><span> </span><span> </span><span> </span><span> 可是，通往城堡的路上出现了一些情况。抽象地说，假象地图在二维平面的第一象限。在每个横轴的x位置上有一个高为h<sub>x</sub>的支撑点，如果彭大侠没有跳到支撑点上，那么他就会掉下去，牺牲在路途。开始时彭大侠在起点（1，h<sub>1</sub>）处，而城堡的入口在（n，h<sub>n</sub>）处。彭大侠每次可以从支撑点（x，h<sub>x</sub>）跳到支撑点（x+1，h<sub>x+1</sub>）。但是彭大侠每次的跳跃能量只有d，也就是说，每次跳跃必须满足条件|h<sub>x+1</sub>-h<sub>n</sub>|≤d。换句话说，如果两个相邻支撑点的纵向落差大于d，那么彭大侠就无法跳跃了！幸运的是，彭大侠还有一个杀手锏。在起点处，他可以花一个金币，把某个支撑点升高1个单位，或者降低1个单位。但是，起点处和城堡入口处的支撑点高度不能改变，并且一旦离开起点彭大侠就无法使用该杀手锏。</span></p>
<p><span> </span><span> </span><span> </span><span> 彭大侠被告知100个金币可兑换一单位生命。于是他希望通过少花金币来保存更多单位的生命。他终于找到了你这位热心的高手，请你帮他规划一下以便耗费尽量少的金币来到达城堡。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>文件第一行包含一个整数m(m≤5)，表示问题求解次数。接下来的2m行依次表示每次求解的输入数据块。每个输入数据块占2行，其中第一行包含两个整数n和d，分别表示从起点到城堡入口处必须经过的支撑点数和每次跳跃允许的最大纵向落差，n和d之间用空格隔开，输入数据保证2≤n≤5000，0≤d≤10</span><sup>9</sup><span>；第二行包含用空格隔开的n个非负整数h</span><sub>1</sub><span>、h</span><sub>2</sub><span>、…、h</span><sub>n</sub><span>，其中h</span><sub>i</sub><span>(1≤i≤n)表示第i个支撑点的高度，特别地，h</span><sub>1</sub><span>表示彭大侠出发时所在支撑点的高度，h</span><sub>n</sub><span>表示城堡入口所在支撑点的高度，</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>有m行，第I(1&le;I&le;m)行表示第I次求解时彭大侠到达城堡必须耗费的最少金币数量。若无论怎样使用杀手锏他都无法到达城堡，则输出impossible。输入数据保证答案在int64范围之内。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3 </span><br><span> 10 2 </span><br><span> 4 5 10 6 6 9 4 7 9 8 </span><br><span> 3 1</span><br><span> 6 4 0</span><br><span> 4 2</span><br><span> 3 0 6 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>6</span><br><span> impossible</span><br><span> 4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入数据保证对所有1≤i≤n有0≤h<sub>i</sub>≤10<sup>9</sup>。</p>
<p><span> </span><span> </span><span> </span><span> </span><span> 20% </span><span> </span><span> </span><span> </span><span> n≤100</span></p>
<p> </p>
<p><span> </span><span> </span><span> </span><span> </span><span> 40% </span><span> </span><span> </span><span> </span><span> n≤1000</span></p>
<p> </p>
<p><span> </span><span> </span><span> </span><span> </span><span> 100% </span><span> </span><span> </span><span> n≤5000</span></p>
</div>
</div>