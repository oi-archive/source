<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>听过化物语op ----staple stable (建议去听)的人都知道战场原很喜欢订书机。</p><p>事实上她喜欢所有金属物品。</p><p>于是显然她们家有个收藏柜，是一维的。</p><p>有一天她邀你去她家参观。</p><p>当你刚进了她家门她突然把门锁上，从里面打不开，说你如果不能帮她统计出正确的数值就要和她在一起或者被温柔的订书机XXX了。</p><p>这时候你想打电话给妈妈回家。</p><p>发现手机被她的吸铁石吸走了。</p><p>她的收藏柜每格都放置了某种刀具（0&lt;=种类代号&lt;=10^9，不同格放置的种类可能相同），共n格。</p><p>设W(x,y)表示x~y格中所有刀具所属种类形成的集合。</p><p>她会发出若干条(x,y,z)的询问（1&lt;=x&lt;=y&lt;z&lt;=n），你需要输出一个数值表示|W(x,y)∩W(y+1,z)| ，即同时出现在第x~y和第y+1~z格中的刀具种数。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个数n, Q（Q为询问数）</p><p>接下来一行，n个数，第i个数a[i]表示第i格放置的刀具种类。</p><p>接下来Q行，每行三个数x,y,z，表示一组询问</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个询问输出一行表示答案。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2</p><p>1 1 3 3 1</p><p>1 3 5</p><p>2 4 5</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br></p><p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%数据1&lt;=n,Q&lt;=1000</p><p>对于100%数据，1&lt;=n,Q&lt;=200000，0&lt;=种类代号&lt;=10^9，输入都是整数</p><p><br></p>
</div>
</div>