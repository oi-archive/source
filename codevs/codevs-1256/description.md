<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>鼹鼠是一种很喜欢挖洞的动物，但每过一定的时间，它还是喜欢把头探出到地面上来透透气的。</p>
<p>根据这个特点阿<span style="font-family: 'Times New Roman';">Q</span><span style="">编写了一个打鼹鼠的游戏：在一个</span><span style="font-family: 'Times New Roman';">n*n</span><span style="">的网格中，在某些时刻鼹鼠会在某一个网格探出头来透透气。你可以控制一个机器人来打鼹鼠，如果</span><span style="font-family: 'Times New Roman';">i</span><span style="">时刻鼹鼠在某个网格中出现，而机器人也处于同一网格的话，那么这个鼹鼠就会被机器人打死。而机器人每一时刻只能够移动一格或停留在原地不动。机器人的移动是指从当前所处的网格移向相邻的网格，即从坐标为（</span><span style="font-family: 'Times New Roman';">i,j</span><span style="">）的网格移向</span><span style="font-family: 'Times New Roman';">(i-1, j),(i+1, j),(i,j-1),(i,j+1)</span><span style="">四个网格，机器人不能走出整个</span><span style="font-family: 'Times New Roman';">n*n</span><span style="">的网格。游戏开始时，你可以自由选定机器人的初始位置。</span></p>
<p><span style="">现在你知道在一段时间内，鼹鼠出现的时间和地点，希望你编写一个程序使机器人在这一段时间内打死尽可能多的鼹鼠。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>你将从文件<span style="">中读入数据，文件第一行为</span><span style="font-family: 'Times New Roman';">n</span><span style="">（</span><span style="font-family: 'Times New Roman';">n&lt;=1000</span><span style="">）</span><span style="font-family: 'Times New Roman';">, m</span><span style="">（</span><span style="font-family: 'Times New Roman';">m&lt;=10000</span><span style="">），其中</span><span style="font-family: 'Times New Roman';">m</span><span style="">表示在这一段时间内出现的鼹鼠的个数，接下来的</span><span style="font-family: 'Times New Roman';">m</span><span style="">行每行有三个数据</span><span style="font-family: 'Times New Roman';">time,x,y</span><span style="">表示有一只鼹鼠在游戏开始后</span><span style="font-family: 'Times New Roman';">time</span><span style="">个时刻，在第</span><span style="font-family: 'Times New Roman';">x</span><span style="">行第</span><span style="font-family: 'Times New Roman';">y</span><span style="">个网格里出现了一只鼹鼠。</span>Time<span style="">按递增的顺序给出。注意同一时刻可能出现多只鼹鼠，但同一时刻同一地点只可能出现一只鼹鼠。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件<span style="font-family: 宋体;">中仅包含一个正整数，表示被打死鼹鼠的最大数目。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2</p>
<p>1 1 1</p>
<p>2 2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>