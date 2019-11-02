<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有这么一种说法：认识6个人，你就认识全世界的人。</p>
<p><span>Aiden现在有一张关系图，上面记载了N个人之间相互认识的情况。Aiden想知道，他能否只认识6个人就能间接认识这N个人呢？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行，两个数N，M，表示有N个人，M对认识关系。</span></p>
<p><span>接下来的M行，每行两个数a</span><span>i</span><span>，b</span><span>i</span><span>，表示</span><span>a</span><span>i</span><span>与b</span><span>i</span><span>相互认识。</span></p>
<p><span>不保证认识关系不出现重复，保证</span><span>a</span><span>i</span><span>≠b</span><span>i</span><span>。</span></p>
<p><span>N个人的编号为1...N。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>若</span><span>只认识6个人就能间接认识这N个人，则输出&ldquo;^_^&rdquo;。</span></p>
<p class="p0"><span>若不行，则第一行输出&ldquo;T_T&rdquo;，第二行输出认识6个人最多能间接认识的人的个数。</span></p>
<p class="p0"><span>输出不包括引号。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">6 7</span></p>
<p><span>1 2</span></p>
<p><span>1 3</span></p>
<p><span>2 4</span></p>
<p><span>3 5</span></p>
<p><span>4 6</span></p>
<p><span>5 6</span></p>
<p><span>3 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>^_^</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>对于30%的数据，保证0＜n≤1000。</span></p>
<p><span>对于50%的数据，保证0＜n≤5000。</span></p>
<p><span>对于100%的数据，保证0＜n≤10000，m≤10*n。</span></p>
</div>
</div>