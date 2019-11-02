<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>司令部的将军们打算在N × M的网格地图上部署他们的炮兵部队。一个N × M的地图由N行M列组成，地图的每一格可能是山地(用"H"表示)，也可能是平原(用"P"表示)，如下图。在每一格平原地形上最多可以布置一支炮兵部队(山地上不能够部署炮兵部队)；一支炮兵部队在地图上的攻击范围如图中黑色区域所示：</p>
<p><br>如果在地图中的灰色所标识的平原上部署一支炮兵部队，则图中的黑色的网格表示它能够攻击到的区域：沿横向左右各两格，沿纵向上下各两格。图上其它白色网格均攻击不到。从图上可见炮兵的攻击范围不受地形的影响。 现在，将军们规划如何部署炮兵部队，在防止误伤的前提下(保证任何两支炮兵部队之间不能互相攻击，即任何一支炮兵部队都不在其他支炮兵部队的攻击范围内)，在整个地图区域内最多能够摆放多少我军的炮兵部队。<br>　</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个由空格分割开的正整数，分别表示N和M；<br>接下来的N行，每一行含有连续的M个字符('P'或者'H')，中间没有空格。按顺序表示地图中每一行的数据。N ≤ 100, M ≤ 10。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><br />仅一行，包含一个整数K，表示最多能摆放的炮兵部队的数量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><br>5 4<br>PHPP<br>PPHH<br>PPPP<br>PHPP<br>PHHP</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>这老经典的题了嚎~~~</p>
<p>首先，我们来看看m，（m&lt;=10),</p>
<p>这样，我们就可以考虑动态规划，</p>
<p>并且，如果我们把它划分成n层的话，那么第i层只跟第i-1层和第i-2层有关。</p>
<p>设第i层的决策状态为ki，则</p>
<p>a[i,ki,ki-1]=max(a[i-1,ki-1,ki-2]+num[ki])</p>
<p>对于每个状态，可以考虑状态压缩，</p>
<p>事先把每个状态都预处理一边，储存在二进制数里。</p>
<p>二进制数中'0'表示没有放置炮台，'1'表示放置了炮台。</p>
<p>再把每一层的地形存在二进制数里，'0'表示平原，'1'表示山地。</p>
<p>设map[i]为第i层的地形，</p>
<p>这样，对于第i（i&gt;=3)层，首先枚举ki-2,使得k[i-2] and map[i-2]=0</p>
<p>再枚举ki-1,使得k[i-1] and map[i-1]=0且k[i-2] and k[i-1]=0,</p>
<p>再枚举ki,使得k[i] and map[i]=0且k[i] and k[i-1]=0且k[i] and k[i-2]=0</p>
</div>
</div>