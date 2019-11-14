<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>      为了让奶牛们娱乐和锻炼，农夫约翰建造了一个美丽的池塘。这个长方形的池子被分成了M 行N 列个方格（1 ≤ M, N ≤ 30）。一些格子是坚固得令人惊讶的莲花，还有一些格子是岩石，其余的只是美丽、纯净、湛蓝的水。贝西正在练习芭蕾舞，她站在一朵莲花上，想跳到另一朵莲花上去，她只能从一朵莲花跳到另一朵莲花上，既不能跳到水里，也不能跳到岩石上。<br>      贝西的舞步很像象棋中的马步：每次总是先横向移动M1 (1 ≤ M1 ≤ 30)格，再纵向移动M2 (1 ≤ M2 ≤ 30, M1≠M2)格，或先纵向移动M1 格，再横向移动M2 格。最多时，贝西会有八个移动方向可供选择。给定池塘的布局和贝西的跳跃长度，请计算贝西从起点出发，到达目的地的最小步数，我们保证输入数据中的目的地一定是可达的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：四个用空格分开的整数：M，N，M1 和M2<br>第二行到M + 1 行：第i + 1 行有N 个用空格分开的整数，描述了池塘第i 行的状态：0 为水，1 为莲花，2 为岩石，3 为贝西所在的起点，4 为贝西想去的终点。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行：从起点到终点的最少步数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 1 2<br>1 0 1 0 1<br>3 0 2 0 4<br>0 1 2 0 0<br>0 0 0 1 0</p>

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
<p>【样例说明】<br>贝西从第二行的最左边出发，目标是第二行的最右边。<br>贝西先跳到第一行第三列的莲花上，再跳到终点，需要两步。</p>
<p><strong>之所以叫青铜莲花池，是因为这是青铜组的，而我们还有白银组、黄金组！</strong></p>
</div>
</div>