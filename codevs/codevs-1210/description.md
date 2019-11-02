<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>阿米巴是小强的好朋友。<br>阿米巴和小强在草原上捉蚂蚱。小强突然想，如果蚂蚱被他们捉灭绝了，那么吃蚂蚱的小鸟就会饿死，而捕食小鸟的猛禽也会跟着灭绝，从而引发一系列的生态灾难。<br>学过生物的阿米巴告诉小强，草原是一个极其稳定的生态系统。如果蚂蚱灭绝了，小鸟照样可以吃别的虫子，所以一个物种的灭绝并不一定会引发重大的灾难。<br>我们现在从专业一点的角度来看这个问题。我们用一种叫做食物网的有向图来描述生物之间的关系：<br>一个食物网有N个点，代表N种生物，如果生物x可以吃生物y，那么从y向x连一个有向边。<br>这个图没有环。<br>图中有一些点没有连出边，这些点代表的生物都是生产者，可以通过光合作用来生存； 而有连出边的点代表的都是消费者，它们必须通过吃其他生物来生存。<br>如果某个消费者的所有食物都灭绝了，它会跟着灭绝。</p>
<p>我们定义一个生物在食物网中的“灾难值”为，如果它突然灭绝，那么会跟着一起灭绝的生物的种数。<br>举个例子：在一个草场上，生物之间的关系是：</p>
<p>        </p>
<p>如果小强和阿米巴把草原上所有的羊都给吓死了，那么狼会因为没有食物而灭绝，而小强和阿米巴可以通过吃牛、牛可以通过吃草来生存下去。所以，羊的灾难值是1。但是，如果草突然灭绝，那么整个草原上的5种生物都无法幸免，所以，草的灾难值是4。<br>给定一个食物网，你要求出每个生物的灾难值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个正整数N，表示生物的种数。生物从1标号到N。<br>接下来N行，每行描述了一个生物可以吃的其他生物的列表，格式为用空格隔开的若干个数字，每个数字表示一种生物的标号，最后一个数字是0表示列表的结束。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含N行，每行一个整数，表示每个生物的灾难值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>0<br>1 0<br>1 0<br>2 3 0<br>2 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4<br>1<br>0<br>0<br>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对50%的数据，N ≤ 10000。<br>对100%的数据，1 ≤ N ≤ 65534。<br>输入文件的大小不超过1M。保证输入的食物网没有环。</p>
</div>
</div>