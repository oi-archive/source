<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>3n+1问题是一个简单有趣而又没有解决的数学问题。这个问题是由L. Collatz在1937年提出的。克拉兹问题（Collatz problem）也被叫做hailstone问题、3n+1问题、Hasse算法问题、Kakutani算法问题、Thwaites猜想或者Ulam问题。</div>
<div>问题如下：</div>
<div>（1）输入一个正整数n；</div>
<div>（2）如果n=1则结束；</div>
<div>（3）如果n是奇数，则n变为3n+1，否则n变为n/2；</div>
<div>（4）转入第（2）步。</div>
<div>克拉兹问题的特殊之处在于：尽管很容易将这个问题讲清楚，但直到今天仍不能保证这个问题的算法对所有可能的输入都有效——即至今没有人证明对所有的正整数该过程都终止。</div>
<div> </div>
<div>题目和3038原题一样，不过数据有所加强。</div>
<div> </div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个整数T.表示输入数据的组数.</p>
<p>第二行是T个正整数n.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个正整数n，每行输出一个数s，表示n通过多少步变换会变成1，如果n无法变成1，则输出-1.</p>

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
<p>1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>
<p>1</p>
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<blockquote>
<p>1 &lt;= T &lt;= 300000</p>
<p>1 &lt;= n &lt;= 1000000000</p>
</blockquote>
</div>
</div>