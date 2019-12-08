<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小E与小W进行一项名为“E&amp;D”游戏。游戏的规则如下：</p>
<p>桌子上有2<em>n</em>堆石子，编号为1..2<em>n</em>。其中，为了方便起见，我们将第2<em>k</em>-1堆与第2<em>k</em>堆（1 ≤ <em>k</em> ≤ <em>n</em>）视为同一组。第i堆的石子个数用一个正整数<em>S<sub>i</sub></em>表示。</p>
<p>一次分割操作指的是，从桌子上任取一堆石子，将其移走。然后分割它同一组的另一堆石子，从中取出若干个石子放在被移走的位置，组成新的一堆。操作完成后，所有堆的石子数必须保证大于0。显然，被分割的一堆的石子数至少要为2。</p>
<p>两个人轮流进行分割操作。如果轮到某人进行操作时，所有堆的石子数均为1，则此时没有石子可以操作，判此人输掉比赛。小E进行第一次分割。他想知道，是否存在某种策略使得他一定能战胜小W。因此，他求助于小F，也就是你，请你告诉他是否存在必胜策略。</p>
<p>例如，假设初始时桌子上有4堆石子，数量分别为1,2,3,1。小E可以选择移走第1堆，然后将第2堆分割（只能分出1个石子）。接下来，小W只能选择移走第4堆，然后将第3堆分割为1和2。最后轮到小E，他只能移走后两堆中数量为1的一堆，将另一堆分割为1和1。这样，轮到小W时，所有堆的数量均为1，则他输掉了比赛。故小E存在必胜策略。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个正整数<em>T</em>（<em>T </em>≤ 20），表示测试数据数量。接下来有<em>T</em>组数据。</p>
<p>对于每组数据，第一行是一个正整数<em>N</em>，表示桌子上共有<em>N</em>堆石子。其中，输入数据保证<em>N</em>是偶数。</p>
<p>第二行有<em>N</em>个正整数<em>S</em><sub>1</sub>..<em>S<sub>N</sub></em>，分别表示每一堆的石子数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含<em>T</em>行。对于每组数据，如果小E必胜，则输出一行&rdquo;YES&rdquo;，否则输出&rdquo;NO&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>4</p>
<p>1 2 3 1</p>
<p>6</p>
<p>1 1 1 1 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>YES</p>
<p>NO</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，<em>N </em>= 2；</p>
<p>对于另外20%的数据，<em>N </em>≤ 4，<em>S<sub>i</sub></em> ≤ 50；<br>对于100%的数据，<em>N </em>≤ 2×10<sup>4</sup>，<em>S<sub>i</sub></em> ≤ 2×10<sup>9</sup></p>
</div>
</div>