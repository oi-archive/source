<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>打地鼠是这样的一个游戏：地面上有一些地鼠洞，地鼠们会不时从洞里探出头来很短时间后又缩回洞中。玩家的目标是在地鼠伸出头时，用锤子砸其头部，砸到的地鼠越多分数也就越高。</p>
<p>游戏中的锤子每次只能打一只地鼠，如果多只地鼠同时探出头，玩家只能通过多次挥舞锤子的方式打掉所有的地鼠。你认为这锤子太没用了，所以你改装了锤子，增加了锤子与地面的接触面积，使其每次可以击打一片区域。如果我们把地面看做m*n的方阵，其每个元素都代表一个地鼠洞，那么锤子可以覆盖R*C区域内的所有地鼠洞。但是改装后的锤子有一个缺点：每次挥舞锤子时，对于这R*C的区域中的所有地洞，锤子会打掉恰好一只地鼠。也就是说锤子覆盖的区域中，每个地洞必须至少有1只地鼠，且如果某个地洞中地鼠的个数大于1，那么这个地洞只会有1只地鼠被打掉，因此每次挥舞锤子时，恰好有R*C只地鼠被打掉。由于锤子的内部结构过于精密，因此在游戏过程中你不能旋转锤子（即不能互换R和C）。</p>
<p>你可以任意更改锤子的规格（即你可以任意规定R和C的大小），但是改装锤子的工作只能在打地鼠前进行（即你不可以打掉一部分地鼠后，再改变锤子的规格）。你的任务是求出要想打掉所有的地鼠，至少需要挥舞锤子的次数。</p>
<p>Hint：由于你可以把锤子的大小设置为1*1，因此本题总是有解的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数m和n；</p>
<p>下面m行每行n个正整数描述地图，每个数字表示相应位置的地洞中地鼠的数量。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="NOI">输出一个整数，表示最少的挥舞次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3<br>1 2 1<br>2 4 2<br>1 2 1 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>使用2*2的锤子，分别在左上、左下、右上、右下挥舞一次。<br><br></p>
<p>对于30%的数据，m,n≤5；</p>
<p>对于60%的数据，m,n≤30；</p>
<p>对于100%的数据，m,n≤100，其他数据不小于0，不大于10<sup>5</sup>。</p>
<p> </p>
</div>
</div>