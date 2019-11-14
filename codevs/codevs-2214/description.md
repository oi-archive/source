<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Farmer John最近为奶牛们的图书馆添置了一个巨大的书架，尽管它是如此<br>的大，但它还是几乎瞬间就被各种各样的书塞满了。现在，只有书架的顶上还留<br>有一点空间。</p>
<p>所有N(1 &lt;= N &lt;= 20)头奶牛都有一个确定的身高H_i<br>(1 &lt;= H_i &lt;= 1,000,000 - 好高的奶牛&gt;_&lt;)。设所有奶牛身高的和为S。书架的<br>高度为B，并且保证1 &lt;= B &lt;= S。</p>
<p>为了够到比最高的那头奶牛还要高的书架顶，奶牛们不得不象演杂技一般，<br>一头站在另一头的背上，叠成一座“奶牛塔”。当然，这个塔的高度，就是塔中<br>所有奶牛的身高之和。为了往书架顶上放东西，所有奶牛的身高和必须不小于书<br>架的高度。</p>
<p>塔叠得越高便越不稳定，于是奶牛们希望找到一种方案，使得叠出的塔在高<br>度不小于书架高度的情况下，高度尽可能小。你也可以猜到你的任务了：写一个<br>程序，计算奶牛们叠成的塔在满足要求的情况下，最少要比书架高多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>* 第1行: 2个用空格隔开的整数：N 和 B</p>
<p>* 第2..N+1行: 第i+1行是1个整数：H_i</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>* 第1行: 输出1个非负整数，即奶牛们叠成的塔最少比书架高的高度</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 16<br>3<br>1<br>3<br>5<br>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>我们选用奶牛1、3、4、5叠成塔，她们的总高度为3 + 3 + 5 + 6 = 17。任<br>何方案都无法叠出高度为16的塔，于是答案为1。</p>
</div>
</div>