<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一只猴子找到了很多香蕉树，这些香蕉树都种在同一直线上，而猴子则在这排香蕉树的第一棵树上。这只猴子当然想吃尽量多的香蕉，但它又不想在地上走，只想从一棵树跳到另一棵树上.同时猴子的体力有限，它不能一次跳得太远或跳得次数太多，每当他跳到一棵树上，就会把那棵树上的香蕉都吃掉。那么，它最多能吃多少个香蕉呢？  </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行为三个整数，分别是香蕉树的棵数N,猴子每次跳跃的最大距离D，最多跳跃次数M.<br>　　下面N行每行包括两个整数，ai,bi分别表示每棵香蕉树上的香蕉数，以及这棵树到猴子所在树的距离。输入保证这些树按照从近到远排列，并且没有两棵树在同一位置。b0总是为0
.<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，包含一个整数，为猴子最多能吃到的香蕉数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5 2<br>6 0<br>8 3<br>4 5<br>6 7<br>9 10<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table cellpadding="0" cellspacing="0" height="0"><tbody><tr><td style="" valign="top" width="10"><br></td><td style="" valign="top" width="702">ai&lt;=10000,d&lt;=10000<br>对于30%的数据，有M&lt;N&lt;=10,bi&lt;=100<br>对于50%的数据，有M&lt;N&lt;=30,bi&lt;=1000<br>对于100%的数据，有M&lt;N&lt;=100,bi&lt;=10000<br></td></tr></tbody></table><p><br></p>
</div>
</div>