<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Loi_imcy 又搞了个搞基数据结构，Loi_DQS 听说后，拿来一眼看穿，说：“这TM不是线段树嘛233。”然后 2 分钟打了个线段树交上去发现只有 90，被Loi_imcy大肆嘲讽，于是DQS就绑♂架了你，命令你A掉这个题。</p><p>    弄一个搞基数据结构，支持单点修改，查询最大值。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有一个n，表示序列长度，第二行n个数，表示初始的序列，之后一个m，表示一共m次操作，对于每一次操作，输入一个操作种类ins ， ins = 1 时 ，后跟 a , b两个整数，表示序列 a 位置增加 b，ins = 2 时 ，询问 1 到 n 的最大值。<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>许多行，每行对应一次询问 1 到 n 的最大值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p>1 2 3 4 5</p><p>3</p><p>1 1 3</p><p>1 1 4</p><p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30％ 的数据，1 &lt;= n,m &lt;= 10000;</p><p>对于 90％ 的数据，1 &lt;= n,m &lt;= 1000000;</p><p>对于 100％ 的数据， 1 &lt;= n,m &lt;= 10000000 , b &gt;= 0;</p><p>你也许需要一个读入优化。</p>
</div>
</div>