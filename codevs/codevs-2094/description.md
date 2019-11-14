<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农夫约翰要量取 Q（1 &lt;= Q &lt;= 20,000）夸脱（夸脱，quarts，容积单位——译者注） 他的最好的牛奶，并把它装入一个大瓶子中卖出。消费者要多少，他就给多少，从不有任何误差。</p>
<p>农夫约翰总是很节约。他现在在奶牛五金商店购买一些桶，用来从他的巨大的牛奶池中量出 Q 夸脱的牛奶。每个桶的价格一样。你的任务是计算出一个农夫约翰可以购买的最少的桶的集合，使得能够刚好用这些桶量出 Q 夸脱的牛奶。另外，由于农夫约翰必须把这些桶搬回家，对于给出的两个极小桶集合，他会选择“更小的”一个，即：把这两个集合按升序排序，比较第一个桶，选择第一个桶容积较小的一个。如果第一个桶相同，比较第二个桶，也按上面的方法选择。否则继续这样的工作，直到相比较的两个桶不一致为止。例如，集合 {3，5，7，100} 比集合 {3，6，7，8} 要好。</p>
<p>为了量出牛奶，农夫约翰可以从牛奶池把桶装满，然后倒进瓶子。他决不把瓶子里的牛奶倒出来或者把桶里的牛奶倒到别处。用一个容积为 1 夸脱的桶，农夫约翰可以只用这个桶量出所有可能的夸脱数。其它的桶的组合没有这么方便。</p>
<p>计算需要购买的最佳桶集，保证所有的测试数据都至少有一个解。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>Line 1: 一个整数 Q</p>
<p>Line 2: 一个整数P（1 &lt;= P &lt;= 100），表示商店里桶的数量</p>
<p>Lines 3..P+2: 每行包括一个桶的容积（1 &lt;= 桶的容积 &lt;= 10000）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只有一行，由空格分开的整数组成：</p>
<p>为了量出想要的夸脱数，需要购买的最少的桶的数量，接着是：</p>
<p>一个排好序的列表（从小到大），表示需要购买的每个桶的容积</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>16
3
3
5
7</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>2 3 5</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>