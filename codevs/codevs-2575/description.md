<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近油荒问题闹得沸沸扬扬，各大石油公司对国际油价虎视眈眈，伺机囤积石油随时提价。现在都是有钱都没有油卖，有很多省份都已经对外地车辆限制加油了。</p>
<p>在外地旅行经常会遇到加油的问题。现在我们在一些崎岖的小路上行走，所有的路线都是单向的（就是说如果A到B有直达路线，则B到A没有直达路线，但是不排除B通过其他点绕路到达A）。每条路线我们都得消耗一定量的汽油，不过有的路线中间有加油站可以补充汽油。但是由于油荒的原因，汽油必须优先供应本地车辆，对于外地车辆，只能加一次固定容量的汽油，也就是说第二次经过加油站时就不允许再加油了。</p>
<p>现在我们已经不寄望走最短路径到底目的地，只是希望我们的能花费最少的汽油到达目的地。当然如果途经加油站的话，我们都会不失时机进行加油。有的时候我们宁愿绕多一点路，甚至兜圈子来获得更多的汽油。我们有足够的钱加油，而且加油站加的油远远少于汽车油箱的容量，因此我们无需担心不够钱加油或者油箱容量爆满。如果路线规划得好的话，说不定到达目的地之后我们还会比原来有更多的汽油呢。</p>
<p>当然，无论之前怎么绕路兜圈加油，只要一到达目的地，我们的旅程就正式结束了，即使有可能到达目的地之后再去其他地方加油兜个圈回到目的地可以获得更多汽油，我们也不会再走了。</p>
<p>现在，给出起点、终点，给出每一条单向路的耗油量和可加油量（没有加油站的路可加油量为0），请求出到底目的地的最少纯耗油量（如果所经过路段的总加油量&gt;总耗油量，则纯耗油量为负数）。</p>
<p> </p>
<p> </p>
<p>【例子】</p>
<p> 参照下面的图案，其中</p>
<p> </p>
<p>1-&gt;2 耗油 10</p>
<p>2-&gt;3 耗油 10</p>
<p>3-&gt;1 耗油 10，加油 50 </p>
<p>1-&gt;4 耗油 10</p>
<p> <img height="156" src="../../../media/image/1368508898.670.371054842126.jpg" width="257"></p>
<p>       很明显，最短路径应该是 1-&gt;4 ，耗油为10 ，但是由于 3-&gt;1有加油站，如果改走 1-&gt;2-&gt;3-&gt;1-&gt;4 的话，一共耗油为40，加油50，就是说纯耗油量为 -10 。当然，3-&gt;1的加油站只能使用一次，如果第二次走过 3-&gt;1，就得耗油 10而没有油加了，所以我们不能寄望多走一个 1-&gt;2-&gt;3-&gt;1的圈子来继续加油了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行输入两个用空格隔开的整数 n∈[2,20] ，m&gt;=1 ，其中n代表结点总数，m代表边的数目。</p>
<p>    下面一共m行，每行有四个用空格隔开的整数 a，b，k1， k2其中 a∈[1,n]，b∈[1,n]且b≠a ，k1∈[1,100]，k2∈[0,100]，代表结点a 到结点b之间存在一条直达的路径，消耗油量为k1，可以加油的油量为k2。</p>
<p>    输入数据确保路径的单向性（即 如果 a直达b ，则不会有b直达a），并且保证从结点1到结点n之间至少有一条路径。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行包含一个整数，代表从结点1到结点n的最少纯耗油量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4</p>
<p>1 2 10 0</p>
<p>2 3 10 0</p>
<p>3 1 10 50</p>
<p>1 4 10 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n∈[2,20] ，m&gt;=1 ，其中n代表结点总数，m代表边的数目。</p>
</div>
</div>