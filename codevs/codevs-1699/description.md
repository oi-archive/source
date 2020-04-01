<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>熊猫喜欢吃竹子，更喜欢制作竹筒。</p>
<p>现在，熊猫有N个竹子。</p>
<p>每天醒来后，熊猫可以干3件事中的一个：</p>
<p>睡觉：熊猫睡了一个白天。</p>
<p>修建竹园：熊猫修建了一个竹园，这个竹园的建造需要S个竹子。从次日起的第i天，这个竹园将在清晨向熊猫提供A[i]根竹子。</p>
<p>制作竹筒：熊猫制作了一个超级精美的竹筒，消耗了S个竹子。注意：一旦竹子变成竹筒，熊猫就不能吃它了。</p>
<p>每天晚上，熊猫都要吃一个竹子。</p>
<p>熊猫总结自己的人生的时候，把自己的收获定为：K*竹筒数+剩下的竹子数</p>
<p>我们想知道，给熊猫T天的时间，他的收获最大是多少？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入的第一行包含四个整数，分别表示T，N，S，K。</span><br><span>接下来一行T-1个整数，表示A数组。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出一个整数，表示熊猫的最大收获。</span><br /><span>如果熊猫无法避免的被饿死，那么输出0.</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 10 5 100</span><br><span>2 3 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>103</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【样例说明】</span><br><span>一共有三天的时间。熊猫的日志如下：</span><br><span>第一天：我醒来，修建了一个竹园，晚上吃了一个竹子，还剩下4根竹子。</span><br><span>第二天：我醒来，从昨天修建的竹园里收获了2个竹子，之后制作了一个竹筒，晚上吃了一个竹子，之后就没有竹子剩下了。</span><br><span>第三天：我醒来，从前天修建的竹园里收获了3个竹子，之后又睡了。晚上吃了一个竹子，还剩2个。</span><br><span>第四天：我醒来，从大前天修建的竹园里收获了2个竹子，之后，接着睡了。晚上起来吃了一个竹子，发现还剩下3个竹子。我总结了我这4天的生活：制作了一个竹筒，剩下了三个竹子，所以收获是103。</span><br><br><span>【数据规模】</span><br><span>对30%的数据，A数组里面所有的数都是一样的。T&lt;=10</span><br><span>对60%的数据，A数组里面所有的数都是一样的。T&lt;=40，N&lt;=10，S&lt;=10</span><br><span>对所有的数据，1&lt;=T&lt;=100，1&lt;=S&lt;=500，1&lt;=N&lt;=1000，S&lt;K&lt;=100000，</span><br><span>A[i]是不超过50的自然数。</span></p>
</div>
</div>