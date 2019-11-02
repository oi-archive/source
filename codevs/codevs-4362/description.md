<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在《三体》第三部《死神永生》中，云天明在蓝星留给程心与关一帆一个小宇宙。小宇宙的形状是一个小型四维超球面，所以从任意一点出发向任意方向直行都可以回到原点。也就是说，虽然它看起来无边无际，但却是同一片区域的单调重复。<br></p><p>（以下开始胡扯）</p><p>云天明早就料到三体第二舰队不会放弃清理地球人。为了防止心爱的“圣母”（作者表示：呵呵）被牵连，云天明表面上将小宇宙的掌控权交给了三体第二舰队，但实际上放置了一些神奇的“量子锁眼”来限制智子的行动（作者口胡出来的，不用当真）。</p><p>现在，为了简化问题，我们把这个三维空间小宇宙看成是一个二维空间矩阵，有“量子锁眼”的区域用字符#表示，没有的则用字符.表示，智子的出发点用字符S表示（显然智子是不能经过有“量子锁眼”的区域的；智子可以向上、下、左、右移动）。现在三体第二舰队路过蓝星时把正在看书的你把你抓到了他们的舰队里，让你计算出他们的智子是不是被封锁在一个区间内（显然他们的科技树严重不完整；封锁在一个区间内的定义是：如果将四维超球面展开并单调重复式无限延伸，智子不能走到<span style="">距离起点无限远处</span>）。云天明的后裔（经作者分析，活捉神级间谍一只）用加密中子流告诉你要先博取三体人的信任。所以，不仅为了大地球的大业，而且为了保住你的小命，<span style="TEXT-DECORATION: line-through;">（而且如果你成功了，三体人会给你提供一个真人版智子233连我都不信）</span>请你替三体第二舰队计算一下他们的智子是否被封锁在一个区间内。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>有多组测试数据。</p><p>对于每一组测试数据，</p><p>第一行有两个整数n,m，分别表示矩阵的行数、列数；</p><p>第二至n+1行，每行m个字符（数据格式非常严格，没有多余的空格），表示这个矩阵。</p><p>文件末有换行符。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组测试数据，输出一行，如智子被困在一个区间内，输出Yes,否则输出No。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 4</p><p>##.#</p><p>##S#</p><p>#..#</p><p>#.##</p><p>#..#</p><p>5 4</p><p>##.#</p><p>##S#</p><p>#..#</p><p>..#.</p><p>#.##</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>No</p><p>Yes</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">第一个点。。样例。。</span></span></p><p><span style="">对于4/11的数据，N,M&lt;=20</span><br style=""><span style="">对于6/11的数据，N.M&lt;=100.</span><br style=""><span style="">对于100%的数据，N,M&lt;=1500，每个测试点不超过10组数据.</span></p><p><span style="">(p.s.这段文字的熵连我都觉得太高了。。所以有必要解释一下。。智子越界的时候会回到它的上一个位置状态在矩阵中的“对面”。eg:</span></p><p><span style=""></span></p><p style="">##.#</p><p style="">##S#</p><p style="">#..#</p><p style="">#.##</p><p style="">#..#</p><p><span style="">假如智子此时在(2,4)这个位置（这里用平面直角坐标系的标记方式来描述，以矩阵最左下角的那个字符为原点），它向上走，会“穿越”到(2,0)这个位置。</span></p><p><span style="">)</span></p>
</div>
</div>