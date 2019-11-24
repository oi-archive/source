<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>zgx被xqz关进了一个迷宫。他这个迷宫有n*n个方块组成。每个方块有一个字母。根据这个字母，zgx可以向一些邻近方块移动。（也有些字母会指示zgx撞墙，一定不能走）。</p><p>zgx在左上角。他想快些走到右下角。他最少要通过几个房间呢？</p><p>附：移动规则表</p><p>D:下 R:右 U:上 L:左 1:能走  0:不能走</p><p>  DRUL</p><p>A 0000</p><p>B 0001</p><p>C 0010 </p><p>D 0011</p><p>  DRUL</p><p>E 0100</p><p>F 0101</p><p>G 0110</p><p>H 0111</p><p>  DRUL</p><p>I 1000</p><p>J 1001</p><p>K 1010</p><p>L 1011</p><p>  DRUL</p><p>M 1100</p><p>N 1101</p><p>O 1110</p><p>P 1111</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，n。</p><p><br></p><p>第2~n+1行，每行n个字符，描述迷宫。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>zgx最少要通过的房间数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br></p><p>MA</p><p>FJ</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p>//M-&gt;F-&gt;J</p><p>//到达F时虽然能向左走，但会撞墙</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=200</p><p>用深搜做（你信）</p><p>超级迷宫II：5470</p>
</div>
</div>