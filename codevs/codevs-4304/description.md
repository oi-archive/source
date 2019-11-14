<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong>（注意：2015年11月6日题目被修改，所以之前的程序不一定能通过，之前的题解也就大概没用了...）</strong></p><p>钨化磷喜欢他的女神很久了，却一直不敢告白。到了毕业时候，钨化磷做好了告白准备，带上鲜花去找他的女神，但是她的女神在S分钟后就会坐飞机离开这个城市。</p><p>然而有很多妹子喜欢钨化磷，她们听说钨化磷喜欢一个女神很久了，而且刚刚又得到了钨化磷准备告白的消息，于是她们准备阻止钨化磷告白。</p><p>已知地图上有n个点，钨化磷在第1个点，机场在第n个点，喜欢钨化磷的m个妹子们分布在<strong>所有</strong>经过这些点的道路上（即有妹子的地方一定有路，没有妹子的地方一定没路），且一条路上只有一个妹子。</p><p>现在他的妹子们计划出了T种方案，而且妹子们想竭尽全力阻止钨化磷告白，于是妹子们想选择可以拖延钨化磷最长时间的方案。</p><p>钨化磷因为赶时间，所以就算两点间有很多条道路，他还是会选择<strong>浪费时间最少(见样例1)</strong>的那条路。</p><p>因为妹子们已经很方了，于是来求你选择方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数，T和S，分别表示方案数和时间。</p><p>接下来有T组数据，对于每组数据：</p><p>第一行有两个整数，m和n，分别表示地图上的m个妹子和n个点。</p><p>接下来的m行，每行有三个整数，u、v和w，表示当前妹子在从u点到v点的道路上可以拖延w分钟。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一个整数，可以拖延的最长时间。如果拖延的最长时间不小于S，则输出“Sad”（不包含引号）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例1】</p><p>1 10</p><p>2 2</p><p>1 2 5</p><p>1 2 1</p><p><br></p><p>【样例2】</p><p>2 10</p><p>2 2</p><p>1 2 1</p><p>1 2 2</p><p>2 2</p><p>1 2 11</p><p>1 2 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例1】</p><p>1</p><p><br></p><p>【样例2】</p><p>Sad</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，n &lt;= 1000，m &lt;= 1000000，w &lt;= 1000。</p><p>对于10%的数据，T &lt;= 1。</p><p>对于20%的数据，T &lt;= 3。<br></p><p>对于100%的数据，T &lt;= 5。</p><p style="">【注】</p><p style="">由于妹子们太喜欢钨化磷了，于是有很多种极端的方案，比如完全图等。</p><p style="">（数据未完全上传）</p>
</div>
</div>