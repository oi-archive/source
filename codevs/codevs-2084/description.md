<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农夫约翰上个星期刚刚建好了他的新牛棚，他使用了最新的挤奶技术。不幸的是，由于工程问题，每个牛栏都不一样。第一个星期，农夫约翰随便地让奶牛们进入牛栏，但是问题很快地显露出来：每头奶牛都只愿意在她们喜欢的那些牛栏中产奶。上个星期，农夫约翰刚刚收集到了奶牛们的爱好的信息（每头奶牛喜欢在哪些牛栏产奶）。一个牛栏只能容纳一头奶牛，当然，一头奶牛只能在一个牛栏中产奶。</p>
<p>给出奶牛们的爱好的信息，计算最大分配方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行 两个整数，N (0 &lt;= N &lt;= 200) 和 M (0 &lt;= M &lt;= 200) 。N 是农夫约翰的奶牛数量，M 是新牛棚的牛栏数量。</p>
<p>第二行到第N+1行 一共 N 行，每行对应一只奶牛。第一个数字 (Si) 是这头奶牛愿意在其中产奶的牛栏的数目 (0 &lt;= Si &lt;= M)。后面的 Si 个数表示这些牛栏的编号。牛栏的编号限定在区间 (1..M) 中，在同一行，一个牛栏不会被列出两次。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>只有一行。输出一个整数，表示最多能分配到的牛栏的数量.</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>5 5
2 2 5
3 2 3 4
2 1 5
3 1 2 5
1 2</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

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