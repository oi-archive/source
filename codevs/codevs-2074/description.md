<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       在一个n*m的一个方块阵阵地上仅由楼房和街道组成，现在你在(x1,y1)点，伤员在(x2,y2)点，你可以向周围的８个方向移动，也可以爬上一部分楼房。而伤员因为受了伤，动弹不得，你必须背他回来。因此你所最担心的不是你的路程长短，而是你在救援中费的力气的大小。你爬上一幢高为Ｈ的楼房，或者从高为Ｈ的楼房房顶下来，都需要花费Ｈ的力气，而没有高度落差的行走是不费力的。现在你要完成救援的任务，最少要花费多少力气呢？费力最小的情况下，你最少又要走多少路呢？这里上、下楼不算走路。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入文件的第１行有两个正整数n,m(n,m&lt;=500)，第２，３行分别是(x1,y1),(x2,y2)(1&lt;=x1,x2&lt;=n,1&lt;=y1,y2&lt;=m)。接下来有n行，每行m个数，第I行，第Ｊ列为1表示此处为空地，为2表示此处为房顶，为０表示此处无法攀爬。保证起点，终点不在０上，你可以假设可攀爬的楼房高度都为１。你到了(x2,y2)就表示救援成功。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;输出文件包括两个在一行的数x,y，用一个空格隔开。Ｘ表示费力最少的情况下，路径的最短长度，Ｙ表示最少花费的力气量。若无法完成营救任务，则输出&rsquo;0 0&rsquo;（引号不输出）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre><span>3 7</span></pre>
<pre><span>1 1</span></pre>
<pre><span>3 7</span></pre>
<pre><span>2100212</span></pre>
<pre><span>2121010</span></pre>
<pre><span>2221012</span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据满足：n,m&lt;=10</p>
<p>100%的数据满足：n,m&lt;=500</p>
</div>
</div>