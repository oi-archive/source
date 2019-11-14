<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">从前有个飞机场，每年旅客不断。飞机场常常没位置。请编一个程序，让他合理安排位置。</span></p><p><span style="">plane.pas\c\cpp——<br></span></p><p><span style="">-代表障碍，0代表空位，1代表满位。机场是长方形，飞机是正方形O__O"…</span><br style=""><span style="">为节省资金，飞机只有在现有情况下不能停靠的情况下才能移动！</span>
</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">输入共(n+2)行。</span></span></p><p><span style="">第一行三个数据，代表飞机场的长m、宽n（m≥n）和飞机的边长1~p，<br></span></p><p><span style="">第二行是飞机的数量（1*1飞机的数量,2*2飞机的数量……p*p飞机的数量），第三行以后是飞机场。</span>
</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(34, 34, 34); font-family: 黑体, SimHei; font-size: 16px; line-height: 25px; background-color: rgb(255, 255, 255);">&nbsp;如果停得下，输出&#39;YES&#39;,并输出现在的飞机场数据，如果停不下，输&#39;NO&#39;，并输出最多能停几架飞机。</span><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1</p><p>4 2 2<br></p><p>0 1</p><p>0 1 - 0</p><p>1 0 0 -</p><p>样例2 </p><p>4 2 2</p><p>5 1</p><p>- 1 0 0 </p><p>0 0 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1</p><p>YES<br></p><p>* * - 1</p><p>* * 1 -</p><p>样例2</p><p>NO</p><p>5</p><p>/*</p><p>样例2解释：</p><p style="">- 1 * * </p><p style="">0 * * *</p><p style="">（答案不唯一）</p><p style="">*/</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">p&lt;1000;</span></p><p><span style="">n≤m≤10000;</span></p><p><span style=""><span style="">样例太水，除点（2）保证唯一解。</span></span></p><p>（实在没办法，数据传不上去了。500）</p>
</div>
</div>