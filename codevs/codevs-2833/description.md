<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>Aiden陷入了一个奇怪的梦境：他被困在一个小房子中，墙上有很多按钮，还有一个屏幕，上面显示了一些信息。屏幕上说，要将所有按钮都按下才能出去，而又给出了一些信息，说明了某个按钮只能在另一个按钮按下之后才能按下，而没有被提及的按钮则可以在任何时候按下。可是Aiden发现屏幕上所给信息似乎有矛盾，请你来帮忙判断。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行，两个数N，M，表示有编号为1...N这N个按钮，屏幕上有M条信息。</span></p>
<p><span>接下来的M行，每行两个数a</span><span>i</span><span>，b</span><span>i</span><span>，表示b</span><span>i</span><span>按钮要在</span><span>a</span><span>i</span><span>之后按下。所给信息可能有重复，保证</span><span>a</span><span>i</span><span>≠b</span><span>i。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>若按钮能全部按下，则输出&ldquo;</span><span>o(&cap;_&cap;)o</span><span>&rdquo;。</span></p>
<p class="p0"><span>若不能，第一行输出&ldquo;T_T&rdquo;，第二行输出因信息有矛盾而无法确认按下顺序的按钮的个数。输出不包括引号。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3 3</span></p>
<p><span>1 2</span></p>
<p><span>2 3</span></p>
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
<p><span>T_T</span></p>
<p><span>2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>对于30%的数据，保证0＜N≤100。</span></p>
<p><span>对于50%的数据，保证0＜N≤2000。</span></p>
<p><span>对于70%的数据，保证0＜N≤5000。</span></p>
<p><span>对于100%的数据，保证0＜N≤10000，0&lt;M≤2.5N。</span></p>
</div>
</div>