<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>DQ星球的世界末日就要到了，可是诺亚方舟还没有制造完成。为了制造诺亚方舟这个星球上的所有国家都站在统一战线。现在一共有n个国家，一个国家到另一个国家都有一条且仅有一条通信渠道，且这个渠道有一个距离，这样就形成了一个有向完全图。 世界末日的预兆已经来了，世界上很多东西都在遭到不明原因的破坏，包括这些通信渠道。现在为了联合制造出诺亚方舟，需要统计所有国家对（a到b和b到a是不同的）之间通信最短距离之和。即需要求出表示i国家与j国家之间的最小距离。可是每隔一段时间就有一些渠道会被破坏，现在DQ星球的首领急需要你来解决这个问题。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>对于每组数据，第一行是一个n，表示有n个国家，接下来有n行，每有n个整数。第i行第j列的数字表示国家i到国家j的通信渠道距离（距离不大于10000）。接下来是一个数字m，表示在可以预知的未来中会有m次破坏会施加到通信渠道中，每次破坏只能破坏一条渠道，一条渠道可以被破坏多次， 但是第一次破坏这条渠道就无法再发送信息。接下来有m行，每行两个整数a、b，表示国家a到国家b的通信渠道遭到破坏。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组数据，输出m行，第i行表示第i次破坏后对应的答案是多少。如果存在两个国家无法相互到达，输出INF。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>0 1 1</p>
<p>1 0 1</p>
<p>1 1 0</p>
<p>4</p>
<p>1 2</p>
<p>1 2</p>
<p>2 3</p>
<p>2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>7</p>
<p>8</p>
<p>INF</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>40%的数据中1&lt;n&lt;=50,1&lt;m&lt;=50;</p>
<p>100%的数据中1&lt;n&lt;=200,1&lt;m&lt;=200;</p>
</div>
</div>