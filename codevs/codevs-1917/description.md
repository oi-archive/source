<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>深海资源考察探险队的潜艇将到达深海的海底进行科学考察。潜艇内有多个深海机器<br>人。潜艇到达深海海底后，深海机器人将离开潜艇向预定目标移动。深海机器人在移动中还<br>必须沿途采集海底生物标本。沿途生物标本由最先遇到它的深海机器人完成采集。每条预定<br>路径上的生物标本的价值是已知的，而且生物标本只能被采集一次。本题限定深海机器人只<br>能从其出发位置沿着向北或向东的方向移动，而且多个深海机器人可以在同一时间占据同一<br>位置。</p>
<p> </p>
<p>用一个P´Q 网格表示深海机器人的可移动位置。西南角的坐标为（0,0），东北角的坐<br>标为 (Q,P)。<br>给定每个深海机器人的出发位置和目标位置，以及每条网格边上生物标本的价值。计算<br>深海机器人的最优移动方案，使深海机器人到达目的地后，采集到的生物标本的总价值最高。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1 行为深海机器人的出发位置数a，和目的地<br>数b，第2 行为P和Q 的值。接下来的P+1 行，每行有Q 个正整数，表示向东移动路径上<br>生物标本的价值，行数据依从南到北方向排列。再接下来的Q+1 行，每行有P 个正整数，<br>表示向北移动路径上生物标本的价值，行数据依从西到东方向排列。接下来的a行，每行有<br>3 个正整数k,x,y，表示有k个深海机器人从(x,y)位置坐标出发。再接下来的b行，每行有3<br>个正整数r,x,y，表示有r个深海机器人可选择(x,y)位置坐标作为目的地。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>程序运行结束时，将采集到的生物标本的最高总价值输出</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 1<br>2 2<br>1 2<br>3 4<br>5 6<br>7 2<br>8 10<br>9 3<br>2 0 0<br>2 2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>42</p>

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