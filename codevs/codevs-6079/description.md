<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><span style="">有一个</span>X<span style="">个点</span><span style="font-family: Calibri;">Y</span><span style="">条边的有向图，蒟蒻yx</span><span style="">可以从</span><span style="font-family: Calibri;">1</span><span style="">号点出发在图上走，并且最终需要回到</span><span style="font-family: Calibri;">1</span><span style="">号点。每个点都有lxn的强烈的气场（包括</span><span style="font-family: Calibri;">1</span><span style="">号点），每次经过一个没到的点，</span><span style="font-family: Calibri;"><span style="font-family: Calibri;"><span style="">蒟蒻yx</span></span></span><span style="">都会疯狂膜拜<span style="">lxn巨佬</span>。大</span><span style="font-family: Calibri;"><span style="font-family: Calibri;"><span style="">蒟蒻yx太想</span></span></span><span style="">膜巨佬<span style="">lxn</span>。</span></span></p><p style=""><span style=""><span style="">由于</span><span style="font-family: Calibri;">该<span style="">蒟蒻yx</span></span><span style="">膜巨佬的欲望非常强烈</span></span><span style=""><span style="">，</span></span><span style=""><span style="">所以他可以偷偷逆行一次去进行更多的膜拜（反向走一次）</span></span><span style=""><span style="">。（需要注意的是，这条边的方向不会改变）</span></span></p><p style=""><span style=""><span style="">你现在想知道</span></span><span style=""><span style="">，</span></span><span style=""><span style="">蒟蒻yx</span><span style="">最多能膜巨佬<span style="">lxn</span>多少次？</span></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="">第一行</span></span><span style="">2<span style="">个整数</span><span style="font-family: Calibri;">X</span><span style="">、</span><span style="font-family: Calibri;">Y</span><span style="">，分别表示图的点数和边数。</span></span></p><p style=""><span style="font-family: Calibri;"><span style="">第二</span></span><span style=""><span style="">行到底</span><span style="font-family: Calibri;">Y+1</span><span style="">行，每行两个整数</span><span style="font-family: Calibri;">Q,W</span><span style="">，描述一条</span><span style="font-family: Calibri;">q到w</span></span><span style=""><span style="">的有向边</span></span><span style="">。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style=";font-family:Calibri;font-size:14px"><span style="font-family:宋体">一行一个整数表示</span><span style="font-family: 宋体; font-size: 14px; text-indent: 28px;">蒟蒻yx</span><span style="font-family:宋体">最多能膜巨佬多少次</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">7 10</span></p><p><span style="">1 2</span></p><p><span style="">3 1</span></p><p><span style="">2 5</span></p><p><span style="">2 4</span></p><p><span style="">3 7</span></p><p><span style="">3 5</span></p><p><span style="">3 6</span></p><p><span style="">6 5</span></p><p><span style="">7 2</span></p><p><span style="">4 7</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">6</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="">对于</span>25%<span style="">的数据，保证</span><span style="font-family: Calibri;">X&lt;=</span></span><span style="">100</span><span style=""><span style="">，</span>Y&lt;=250<span style="">，</span></span></p><p style=""><span style=""><span style="">对于</span></span><span style="">43.75%<span style="">的数据，保证</span><span style="font-family: Calibri;">X&lt;=3</span></span><span style="">,</span><span style="">000<span style="">，</span><span style="font-family: Calibri;">Y&lt;=7</span></span><span style="">,</span><span style="">000<span style="">。</span></span></p><p style=""><span style=""><span style="">对于</span></span><span style="">100%<span style="">的数据，保证</span><span style="font-family: Calibri;">X,Y&lt;=100,000</span><span style="">。</span></span></p><p>（dfs+bfs+tarjan）</p>
</div>
</div>