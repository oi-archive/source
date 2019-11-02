<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>N个任务排成一个序列在一台机器上等待完成（顺序不得改变），这N个任务被分成若干批，每批包含相邻的若干任务。从时刻0开始，这些任务被分批加工，第i个任务单独完成所需的时间是Ti。在每批任务开始前，机器需要启动时间S，而完成这批任务所需的时间是各个任务需要时间的总和（同一批任务将在同一时刻完成）。每个任务的费用是它的完成时刻乘以一个费用系数Fi。请确定一个分组方案，使得总费用最小。<br>例如：S=1；T={1,3,4,2,1}；F={3,2,3,3,4}。如果分组方案是{1,2}、{3}、{4,5}，则完成时间分别为{5,5,10,14,14}，费用C={15,10,30,42,56}，总费用就是153。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是N。<br>第二行是S。<br>下面N行每行有一对数，分别为Ti和Fi，均为不大于100的正整数，表示第i个任务单独完成所需的时间是Ti及其费用系数Fi。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数，最小的总费用。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>1<br>1 3<br>3 2<br>4 3<br>2 3<br>1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>153</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=N&lt;=5000</p>
<p>0&lt;=S&lt;=50</p>
</div>
</div>