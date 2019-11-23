<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农民约翰在喂奶牛的时候被另一个问题卡住了。他的所有N(1 &lt;= N &lt;= 100,000)个奶牛在他面前排成一行(按序号1..N的顺序)，按照它们的社会等级排序。奶牛#1有最高的社会等级，奶牛#N最低。每个奶牛同时被指定了一个不唯一的附加值，这个数在0..2^21 - 1的范围内。</p><p>帮助农民约翰找出应该从哪一头奶牛开始喂，使得从这头奶牛开始的一个连续的子序列上，奶牛的附加值的异或最大。</p><p>如果有多个这样的子序列，选择结尾的奶牛社会等级最高的。如果还不唯一，选择最短的。如果还不唯一，选择靠前的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行:一个单独的整数N。</p><p>第2到N + 1行:N个0..2^21 - 1之间的整数，代表每头奶牛的被赋予的数。第j行描述了社会等级j - 1的奶牛。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第 1 行: 3个空格隔开的整数，分别为：最大的异或值，序列的起始位置、终止位置。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>5
1
0
5
4
2</pre><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>6 4 5</pre><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>最大异或值为6，从第4个开始喂，到第5个结束。</p><p>4 异或 2 = 6</p><p>(100) 异或 (010) = (110)</p>
</div>
</div>