<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">Alice </span><span style="">和 Bob 总喜欢聚在一起玩游戏（T­_T），今天他（她）们玩的是一款新型的取石子游戏。游戏一开始有N堆石子，Alice 和 Bob 轮流取出石子。在每次操作中，游戏者必须选择其中的一堆石子，并作出下列的其中一种操作：</span></p><p style=""><span style="">(1)</span><span style="">移去整堆石子</span></p><p style=""><span style="">(2)</span><span style="">假设石子堆中有X颗石子，取出Y颗石子，其中1&lt;=Y&lt;X,并且X和Y的最大公约数是1。 </span></p><p style=""><br></p><p style=""><span style="">游戏结束的条件是：取出最后一颗石子的人胜出。众所周知，Alice和Bob都是绝顶聪明的，假设他们在游戏中都采取最优的策略，问最后谁会胜出游戏呢？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行包含一个整数</span><span style="">T</span><span style="">，表示测试数据的组数。</span></p><p style=""><span style="">接下来</span><span style="">T</span><span style="">组测试数据，在每组数据中，第一行包含一个整数N，表示有多少堆石子。第二行N个正整数，分别表示每堆有多少颗石子。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每组测试数据输出一行，表示获胜者的名字（Alice 或者 Bob）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>3</p><p>3 5 6</p><p>4</p><p>2 3 6 9</p><p>5</p><p>3 2 1 1000000 999999</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Alice</p><p>Bob</p><p>Alice</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>20%<span style="">的数据，</span>N&lt;=5<span style="">，</span><span style="">每堆石子数量少于</span>10</p><p>100%<span style="">的数据，</span>T&lt;=100<span style="">，</span>N&lt;=100<span style="">，每堆石子数量不大于</span>1,000,000</p><p><br></p>
</div>
</div>