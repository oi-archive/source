<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>     闷热的夏天,威斯康辛州的奶制品地区提供冷水供奶牛饮用，以此来解渴。农夫约翰将冷水通过N (3 &lt;= N &lt;= 99999; N 为奇数)个冷水管道，分别编号序号1..N从泵的位置一直送到牛棚里。当水在管道中流动时，夏天的热能使它变热。贝茜想要找到最冷的水,这样她就能比任何其他奶牛更好地享受这难得的好天气。</p>
<p>    她已经绘制了一整套完整的分支管道,并注意到这个管道系统犹如一棵树,它的根在农场,从根开始每个分支都分离出两个管道。令人惊讶的是，所有管道都有一个长度，当然这所有的N根管道连接成1条路或者和其他的管道路线连接。</p>
<p>    给出所有管道连接的地图，计算每一个分支点到牛棚的距离。贝茜将通过这些信息来找到最清凉冷水。</p>
<p>    管道的端点，可以作为分支点也可以作为管道终点，它以管道的编号命名。地图上包含C (1&lt;= C &lt;= N)个分支器，每个分支器包含3个数据，管道端点E_i (1&lt;= E_i &lt;= N)，管道端点连接的两个管道B1_i, B2_i (2&lt;= B1_i &lt;=N; 2&lt;= B2_i &lt;=N)。管道1连接到牛棚，每两个连接器之间的管道长度均为1。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    * 第 1 行: 2个用空格隔开的整数 N , C</p>
<p>    * 第 2 至 C+1 行: 3个用空格隔开的整数，分别表示连接器的编号，以及连接的2个管道的编号E_i, B1_i, B2_i</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;&nbsp;&nbsp; * 共 N 行: 分别表示每个管道到牛棚的最短距离。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>    5 2</p>
<p>    3 5 4</p>
<p>    1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>    1</p>
<p>    2</p>
<p>    2</p>
<p>    3</p>
<p>    3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>    +------+</p>
<p>    | Barn |</p>
<p>    +------+</p>
<p>    |  1</p>
<p>    *</p>
<p>    2 / \ 3</p>
<p>    *</p>
<p>       4 / \ 5</p>
</div>
</div>