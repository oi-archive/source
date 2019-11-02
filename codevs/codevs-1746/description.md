<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>传说中的九头龙是一种特别贪吃的动物。虽然名字叫“九头龙”，但这只是<br>说它出生的时候有九个头，而在成长的过程中，它有时会长出很多的新头，头的<br>总数会远大于九，当然也会有旧头因衰老而自己脱落。<br>有一天，有M 个脑袋的九头龙看到一棵长有N 个果子的果树，喜出望外，<br>恨不得一口把它全部吃掉。可是必须照顾到每个头，因此它需要把N 个果子分<br>成M组，每组至少有一个果子，让每个头吃一组。<br>这M个脑袋中有一个最大，称为“大头”，是众头之首，它要吃掉恰好K个<br>果子，而且K个果子中理所当然地应该包括唯一的一个最大的果子。果子由N-1<br>根树枝连接起来，由于果树是一个整体，因此可以从任意一个果子出发沿着树枝<br>“走到”任何一个其他的果子。<br>对于每段树枝，如果它所连接的两个果子需要由不同的头来吃掉，那么两个<br>头会共同把树枝弄断而把果子分开；如果这两个果子是由同一个头来吃掉，那么<br>这个头会懒得把它弄断而直接把果子连同树枝一起吃掉。当然，吃树枝并不是很<br>舒服的，因此每段树枝都有一个吃下去的“难受值”，而九头龙的难受值就是所<br>有头吃掉的树枝的“难受值”之和。<br>九头龙希望它的“难受值”尽量小，你能帮它算算吗？<br>例如图 1 所示的例子中，果树包含8 个果子，7 段树枝，各段树枝的“难受<br>值”标记在了树枝的旁边。九头龙有两个脑袋，大头需要吃掉4个果子，其中必<br>须包含最大的果子。即N=8，M=2，K=4：<br>图一描述了果树的形态，图二描述了最优策略。<br>大头吃4个果子，用实心点标识；<br>小头吃4个果子，用空心点标识；<br>九头龙的难受值为4，因为图中用细边标<br>记的树枝被大头吃掉了。</p>

<img src="/source/codevs/codevs-1746/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzQ2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc0Ni5ibXA=.bmp" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件dragon.in的第1行包含三个整数N (1&lt;=N&lt;=300)，M (2&lt;=M&lt;=N)，<br>K (1&lt;=K&lt;=N)。 N 个果子依次编号1,2,...,N，且最大的果子的编号总是1。第2<br>行到第N行描述了果树的形态，每行包含三个整数a (1&lt;=a&lt;=N)，b (1&lt;=b&lt;=N)，<br>c (0&lt;=c&lt;=105)，表示存在一段难受值为c的树枝连接果子a和果子b。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件dragon.out 仅有一行，包含一个整数，表示在满足&ldquo;大头&rdquo;的要求<br />的前提下，九头龙的难受值的最小值。如果无法满足要求，输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 2 4<br>1 2 20<br>1 3 4<br>1 4 13<br>2 5 10<br>2 6 12<br>3 7 15<br>3 8 5</p>

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
<p>该样例对应于题目描述中的例子。</p>
</div>
</div>