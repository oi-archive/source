<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>坚果保龄球是植物大战僵尸中的一个小游戏。现在疯狂戴夫只给了<span style="font-family: 'Times New Roman';">lxhgww</span><span style="">一些最普通的坚果，让</span><span style="font-family: 'Times New Roman';">lxhgww</span><span style="">像保龄球一样把坚果扔出去，砸死院子里的僵尸。</span></span></p>
<p><span>院子一共由<span style="font-family: 'Times New Roman';">N</span><span style="">条轨道组成，从上到下依次编号从</span><span style="font-family: 'Times New Roman';">1</span><span style="">到</span><span style="font-family: 'Times New Roman';">N</span><span style="">，每条轨道又被分成若干格。院子里一共有</span><span style="font-family: 'Times New Roman';">M</span><span style="">只僵尸，每只僵尸站在某个格子内，并且可以认为它的位置不会变化。游戏可以分成</span><span style="font-family: 'Times New Roman';">K</span><span style="">个回合，在每个回合中，你可以选择一条轨道，把一个坚果扔出去。被扔出去的坚果首先会沿着轨道直线的从左往右滚动，直到撞到第一只僵尸之后，它开始沿着</span><span style="font-family: 'Times New Roman';">45</span><span style="">度的斜线滚动，并且向中心的一侧滚动（即前</span><span style="font-family: 'Times New Roman';">N/2</span><span style="">行的向右下滚动，后</span><span style="font-family: 'Times New Roman';">N/2</span><span style="">行的向右上滚动，题目保证</span><span style="font-family: 'Times New Roman';">N</span><span style="">是偶数）。院子的两边是围墙。斜着走的坚果撞到围墙或者僵尸会反弹，即从往右上走变成往右下走，或者反过来。直到坚果不再能打到任何僵尸之后，该回合结束。注意：多只僵尸可能站在同一格，这个时候坚果每次只会撞死该格子的其中一只僵尸。</span></span></p>
<p><span>为了砸死尽量多的僵尸，现在<span style="font-family: 'Times New Roman';">lxhgww</span><span style="">决定在每回合的开始，选择在当前情况下可以砸死最多僵尸的一条路线扔出坚果。在出现相同的情况时，他会选择编号最小的轨道扔出。为了了解这个做法的效果，现在</span><span style="font-family: 'Times New Roman';">lxhgww</span><span style="">需要你帮助他计算这个方法可以砸死的僵尸数目。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入的第一行有<span style="font-family: 'Times New Roman';">3</span><span style="">个整数，</span><span style="font-family: 'Times New Roman';">N</span><span style="">，</span><span style="font-family: 'Times New Roman';">M</span><span style="">，</span><span style="font-family: 'Times New Roman';">K</span><span style="">。</span></span></p>
<p><span>接下来<span style="font-family: 'Times New Roman';">M</span><span style="">行，每行两个整数</span><span style="font-family: 'Times New Roman';">X</span></span><span>i</span><span>, Y</span><span>i</span><span>，表示第<span style="font-family: 'Times New Roman';">i</span><span style="">个僵尸位于第</span><span style="font-family: 'Times New Roman';">Y</span></span><span>i</span><span>条轨道，从左数第<span style="font-family: 'Times New Roman';">X</span></span><span>i</span><span>个格子中。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>输出数据包括<span style="font-family: 'Times New Roman';">K+1</span><span style="font-family: 宋体;">行。</span></span></p>
<p class="p0"><span>前<span style="font-family: 'Times New Roman';">K</span><span style="font-family: 宋体;">行，每行</span><span style="font-family: 'Times New Roman';">2</span><span style="font-family: 宋体;">个数据</span><span style="font-family: 'Times New Roman';">A</span></span><span>i</span><span>,&nbsp;B</span><span>i</span><span>，表示在第<span style="font-family: 'Times New Roman';">i</span><span style="font-family: 宋体;">个回合，从第</span><span style="font-family: 'Times New Roman';">A</span></span><span>i</span><span>条轨道扔出坚果，这个坚果在运行过程中打到了<span style="font-family: 'Times New Roman';">B</span></span><span>i</span><span>个僵尸。</span></p>
<p class="p0"><span>最后一行是一个数字，表示被打到的僵尸总数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><br><span> 4 2 1</span><br><br><span> 1 2</span><br><br><span> 5 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>2 2</span><br><br><span> 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，保证： N&lt;=200，M&lt;=500，K&lt;=200，Xi&lt;=200；</p>
<p><span style="">对于50%的数据，保证： N&lt;=200，M&lt;=200000，K&lt;=200，Xi&lt;=1000000；</span></p>
<p><span style="">对于100%的数据，保证： N&lt;=20000，M&lt;=200000，K&lt;=100000，Xi&lt;=1000000；</span></p>
<p><span style="">对于所有的数据，保证：1&lt;=Yi&lt;=N</span></p>
</div>
</div>