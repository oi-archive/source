<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>萨丽·斯内尔（Sally Snail，蜗牛）喜欢在N x N 的棋盘上闲逛（1 &lt; n &lt;= 120）。<br>她总是从棋盘的左上角出发。棋盘上有空的格子（用“.”来表示）和B 个路障（用“#”来表示）。<span style="">萨丽总是垂直（向上或者向下）或水平（向左或者向右）地走。她可以从出发地（总是记</span></p>
<p>作A1 ）向下或者向右走。一旦萨丽选定了一个方向，她就会一直走下去。如果她遇到棋盘<br>边缘或者路障，她就停下来，并且转过90 度。她不可能离开棋盘，或者走进路障当中。并且，<br>萨丽从不跨过她已经经过的格子。当她再也不能走的时候，她就停止散步。<br>萨丽向右走，再向下，向右，向下，然后向左，再向上，最后向右走。这时她遇到了一个<br>她已经走过的格子，她就停下来了。但是，如果她在F5 格遇到路障后选择另外一条路——向我<br>们看来是左边的方向转弯，情况就不一样了。<br>你的任务是计算并输出，如果萨丽聪明地选择她的路线的话，她所能够经过的最多格子数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包括N —棋盘的大小，和B —路障的数量（1 &lt;= B &lt;= 200）。接下来的<br>B 行包含着路障的位置信息。下面的样例输入对应着上面的示例棋盘。下面的输出文件表示问<br>题的解答。注意，当N &gt; 26 时，输入文件就不能表示Z 列以后的路障了。（这句话不用专<br>门理他。其实就是从A 的ascii 码开始向后顺延，不管是什么字母就行了。）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件应该只由一行组成，即萨丽能够经过的最多格子数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 4<br>E2<br>A6<br>G1<br>F5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>３３</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>（1 &lt; n &lt;= 120）</p>
<p>1 &lt;= B &lt;= 200</p>
</div>
</div>