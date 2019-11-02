<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>箱子再分配问题需要解决如下问题：</p>
<p>（1）一共有N个物品，堆成M堆。</p>
<p>（2）所有物品都是一样的，但是它们有不同的优先级。</p>
<p>（3）你只能够移动某堆中位于顶端的物品。</p>
<p>（4）你可以把任意一堆中位于顶端的物品移动到其它某堆的顶端。若此物品是当前所有物品中优先级最高的，可以直接将之删除而不用移动。</p>
<p>（5）求出将所有物品删除所需的最小步数。删除操作不计入步数之中。</p>
<p>（6）只是一个比较难解决的问题，这里你只需要解决一个比较简单的版本：</p>
<p>        不会有两个物品有着相同的优先级，且M=2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是包含两个整数N1,N2分别表示两堆物品的个数。</p>
<p>接下来有N1行整数按照从顶到底的顺序分别给出了第一堆物品中的优先级，数字越大，优先级越高。</p>
<p>再接下来的N2行按照同样的格式给出了第二堆物品的优先级。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个数据，请输出一个整数，即最小移动步数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>1</p>
<p>4</p>
<p>5</p>
<p>2</p>
<p>7</p>
<p>3</p>

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
<p>对于20%的数据有1&lt;=N1+N2&lt;=100</p>
<p>对于40%的数据有1&lt;=N1+N2&lt;=1000</p>
<p>对于全部数据，有1&lt;=N1+N2&lt;=100000</p>
</div>
</div>