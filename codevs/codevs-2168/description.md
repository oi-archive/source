<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Farmer John一直努力让他的草地充满鲜美多汁的而又健康的牧草。可惜天不从人愿，他在植物大战人类中败下阵来。邪恶的乳草已经在他的农场的西北部份佔领了一片立足之地。</p>
<p>草地像往常一样，被分割成一个高度為Y, 宽度為X的直角网格。(1,1)是左下角的格（也就是说坐标排布跟一般的X,Y坐标相同）。乳草一开始佔领了格(Mx,My)。每个星期，乳草传播到已被乳草佔领的格子四面八方的每一个没有很多石头的格（包括垂直与水平相邻的和对角线上相邻的格）。1周之后，这些新佔领的格又可以把乳草传播到更多的格裡面了。</p>
<p>Bessie想要在草地被乳草完全佔领之前尽可能的享用所有的牧草。她很好奇到底乳草要多久才能佔领整个草地。如果乳草在0时刻处於格(Mx,My)，那麼还在那个时刻它们可以完全佔领入侵整片草地呢（对给定的数据总是会发生）？</p>
<p>草地由一个图片表示。"."表示草，而"*"表示大石。比如这个X=4, Y=3的例子。</p>
<p>....<br> ..*.<br> .**.</p>
<p>如果乳草一开始在左下角（第1排，第1列），那麼草地的地图将会以如下态势发展：</p>
<p>.... .... MMM. MMMM MMMM <br> ..*. MM*. MM*. MM*M MM*M <br> M**. M**. M**. M**. M**M <br>星期数 0 1 2 3 4</p>
<p>乳草会在4星期后佔领整片土地。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>* 第一行: 四个由空格隔开的整数: X, Y, Mx, My</p>
<p>* 第2到第Y+1行: 数据的第y+1行由X个字符（"."表示草地，"*"表示大石），描述草地的<br> 第(Y+2-y)行。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>* 第一行: 一个单独的整数表示最后一个不是大石块的格子被乳草佔领的星期数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 1 1<br>....<br>..*.<br>.**.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 &lt;= x, y &lt;= 100</p>
</div>
</div>