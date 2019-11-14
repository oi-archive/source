<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>      农民John有很多牛，他想交易其中一头被Don称为The Knight的牛。这头牛有一个独一无二的超能力，在农场里像Knight一样地跳（就是我们熟悉的象棋中马的走法）。虽然这头神奇的牛不能跳到树上和石头上，但是它可以在牧场上随意跳，我们把牧场用一个x，y的坐标图来表示。</p>
<p>这头神奇的牛像其它牛一样喜欢吃草，给你一张地图，上面标注了The Knight的开始位置，树、灌木、石头以及其它障碍的位置，除此之外还有一捆草。现在你的任务是，确定The Knight要想吃到草，至少需要跳多少次。The Knight的位置用'K'来标记，障碍的位置用'*'来标记，草的位置用'H'来标记。<br><br> 这里有一个地图的例子：<br> 　　　　　　 11 | . . . . . . . . . .<br> 　　　　　　 10 | . . . . * . . . . . <br> 　　　　　　 9 | . . . . . . . . . . <br> 　　　　　　 8 | . . . * . * . . . . <br> 　　　　　　 7 | . . . . . . . * . . <br> 　　　　　　 6 | . . * . . * . . . H <br> 　　　　　　 5 | * . . . . . . . . . <br> 　　　　　　 4 | . . . * . . . * . . <br> 　　　　　　 3 | . K . . . . . . . . <br> 　　　　　　 2 | . . . * . . . . . * <br> 　　　　　　 1 | . . * . . . . * . . <br> 　　　　　　 0 ----------------------<br> 　　　　　　　　　　　　　　　　　　1 <br> 　　　　　　　　0 1 2 3 4 5 6 7 8 9 0 <br><br> The Knight 可以按照下图中的A,B,C,D...这条路径用5次跳到草的地方（有可能其它路线的长度也是5）：<br> 　　　　　　 11 | . . . . . . . . . .<br> 　　　　　　 10 | . . . . * . . . . .<br> 　　　　　　 9 | . . . . . . . . . .<br> 　　　　　　 8 | . . . * . * . . . .<br> 　　　　　　 7 | . . . . . . . * . .<br> 　　　　　　 6 | . . * . . * . . . F&lt;<br> 　　　　　　 5 | * . B . . . . . . .<br> 　　　　　　 4 | . . . * C . . * E .<br> 　　　　　　 3 | .&gt;A . . . . D . . .<br> 　　　　　　 2 | . . . * . . . . . *<br> 　　　　　　 1 | . . * . . . . * . .<br> 　　　　　　 0 ----------------------<br> 　　　　　　　　　　　　　　　　　　1<br> 　　　　　　　　0 1 2 3 4 5 6 7 8 9 0 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行： 两个数，表示农场的列数(&lt;=150)和行数(&lt;=150)<br><br> 第二行..结尾: 如题目描述的图。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp;一个数，表示跳跃的最小次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 11<br>..........<br>....*.....<br>..........<br>...*.*....<br>.......*..<br>..*..*...H<br>*.........<br>...*...*..<br>.K........<br>...*.....*<br>..*....*..</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>Hint：这类问题可以用一个简单的先进先出表（队列）来解决。</p>
</div>
</div>