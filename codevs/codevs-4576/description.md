<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">elfness</span><span style="">被魔王抓走了</span><span style="">，</span><span style="">这次魔王把</span><span style="">elfness</span><span style="">关在一个</span><span style="">n*m</span><span style="">的地牢里。地牢的某个地方安装了一个带锁的门，钥匙藏在地牢的另外一个地方，</span><span style="">elfness</span><span style="">想要通过这个门，就必须先走到藏钥匙的地方取钥匙。刚开始的时候</span><span style="">elfness</span><span style="">被关在</span><span style="">(sx,sy)</span><span style="">的位置，而离开地牢的门在</span><span style="">(ex,ey)</span><span style="">的位置。</span><span style="">elfness</span><span style="">每分钟只能从一个位置走到相邻四个位置中的其中一个。魔王每</span><span style="">t</span><span style="">分钟都回地牢视察一次，若发现</span><span style="">elfness</span><span style="">不在原位置便会把他拎回去。经过若干次的尝试，</span><span style="">elfness</span><span style="">已经画出了整个地牢的地图。现在请你帮他计算能否再次成功逃亡。只要在魔王下次视察之前走到出口就算离开地牢，如果魔王回来的时候还未到出口都算逃亡失败。注意，逃跑路线不一定非要通过带锁的门。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行有三个整数</span><span style="">n,m,t</span><span style="">。接下来的</span><span style="">n</span><span style="">行</span><span style="">m</span><span style="">列为地牢的地图，其中包括</span><span style="">:</span></p><p style=""><span style="">. </span><span style="">代表路</span></p><p style=""><span style="">* </span><span style="">代表墙</span></p><p style=""><span style="">@ </span><span style="">代表elfness的起始位置</span></p><p style=""><span style="">^ </span><span style="">代表地牢的出口</span></p><p style=""><span style="">A </span><span style="">代表带锁的门</span></p><p style=""><span style="">a </span><span style="">代表钥匙</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-size:16px;font-family:宋体">一行，包含一个整数。对于可以成功逃亡的情况，请输出至少需要多少分钟才能离开，如果不能则输出</span><span style="font-size:16px"> -1</span><span style="font-size:16px;font-family:宋体">。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">4 4 100</span></p><p style=""><span style="">@..A</span></p><p style=""><span style="">a.*.</span></p><p style=""><span style="">***.</span></p><p style=""><span style="">^...</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">11</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于</span><span style="">50%</span><span style="">的数据，地牢没有带锁的门和钥匙</span></p><p style=""><span style="">对于</span><span style="">100%</span><span style="">的数据，</span><span style="">2&lt;=n,m&lt;=20</span><span style="">，</span><span style="">t&gt;0</span></p><p><br></p>
</div>
</div>