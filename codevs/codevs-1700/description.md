<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>c国边防军在边境某处的阵地是由n个地堡组成的。工兵连受命来到阵地要进行两期施工。</p>
<p>第一期的任务是挖掘暗道让所有地堡互联互通。现已勘测设计了m条互不相交的暗道挖掘方案，如果这m条暗道都实施挖掘，肯定能达到互联互通的目的。事实上，适当选择其中n-1个方案挖掘，就能实现互联互通，即从每个地堡出发都能到达其他任何一个地堡（允许经过别的地堡）。</p>
<p>连长精心谋算，在m个设计规划中选取了挖掘总距离最短且能保证互联互通的若干个暗道规划实施了挖掘，完成了第一期的施工任务后又接受了第二期的施工任务，要求选择一个地堡进行扩建改造，使其能向每个地堡提供弹药。为了让弹药供应更及时、更快捷，从改扩建的地堡到最远地堡的距离（称为最远输送距离）应当尽量小。</p>
<p>你的任务是先求出第一期施工挖掘的总距离，再求改扩建地堡最远输送距离的最小值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>其中第一行是n和m，m&gt;=n</span><br><span>下面的m行每行3个数xi、yi、zi,表示xi到yi的距离是zi</span><br><span>  zi&lt;1000000且m个距离互不相等</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>共包含两行，每行一个整数，</span><br /><span>第一行是第一期的挖掘总距离，第二行是最远输送距离的最小值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 5</span><br><span>1 2 1</span><br><span>2 3 2</span><br><span>3 4 3</span><br><span>4 1 4</span><br><span>3 1 5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>6</span><br><span>3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【样例说明】</span><br><span>第一期挖掘1到2、2到3和3到4的3条暗道，第二期选择3号地堡进行改扩建，最远输送距离是3</span><br><span>【数据规模】</span><br><span>60%的数据 n&lt;10且m&lt;20</span><br><span>80%的数据 n&lt;1000且m&lt;2000</span><br><span>100%的数据 n&lt;100000且m&lt;200000</span></p>
</div>
</div>