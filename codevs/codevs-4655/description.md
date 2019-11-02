<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">网上有许多题，就是给定一个序列，要你支持几种操作：A、B、C、D。一看另一道题，又是一个序列 要支持几种操作：D、C、B、A。尤其是我们这里的某人，出模拟试题，居然还出了一道这样的，真是没技术含量……这样 我也出一道题，我出这一道的目的是为了让大家以后做这种题目有一个“库”可以依靠，没有什么其他的意思。这道题目 就叫序列终结者吧。 </p><p style=""><br></p><p style=""> 给定一个长度为N的序列，每个序列的元素是一个整数（废话）。要支持以下三种操作： 1. 将[L,R]这个区间内的所有数加上V。 2. 将[L,R]这个区间翻转，比如1 2 3 4变成4 3 2 1。 3. 求[L,R]这个区间中的最大值。 最开始所有元素都是0。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行两个整数N，M。M为操作个数。 以下M行，每行最多四个整数，依次为K，L，R，V。K表示是第几种操作，如果不是第1种操作则K后面只有两个数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="OVERFLOW: hidden; MARGIN-BOTTOM: 0.6em; MARGIN-TOP: 0.6em; PADDING-BOTTOM: 0px; PADDING-TOP: 0px; PADDING-LEFT: 0px; PADDING-RIGHT: 0px; text-shadow: rgb(250, 250, 250) 0px -1px 0px">对于每个第3种操作，给出正确的回答。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;">4 4</span><br style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;"><span style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;">1 1 3 2</span><br style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;"><span style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;">1 2 4 -1</span><br style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;"><span style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;">2 1 3</span><br style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;"><span style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;">3 2 4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;">2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="FONT-FAMILY: 'Trebuchet MS', Helvetica, 'Microsoft YaHei', Georgia, sans-serif;">N&lt;=50000，M&lt;=100000。</span></p>
</div>
</div>