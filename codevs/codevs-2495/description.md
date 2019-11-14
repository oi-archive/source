<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　水叮当得到了一块五颜六色的格子形地毯作为生日礼物，更加特别的是，地毯上格子的颜色还能随着踩踏而改变。</span><br><span>　　为了讨好她的偶像虹猫，水叮当决定在地毯上跳一支轻盈的舞来卖萌~~~</span></p>
<p><span><span>　　地毯上的格子有N行N列，每个格子用一个0~5之间的数字代表它的颜色。</span><br><span>　　水叮当可以随意选择一个0~5之间的颜色，然后轻轻地跳动一步，左上角的格子所在的联通块里的所有格子就会变成她选择的那种颜色。这里连通定义为：两个格子有公共边，并且颜色相同。</span><br><span>　　由于水叮当是施展轻功来跳舞的，为了不消耗过多的真气，她想知道最少要多少步才能把所有格子的颜色变成一样的。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　每个测试点包含多组数据。</span><br><span>　　每组数据的第一行是一个整数N，表示地摊上的格子有N行N列。</span><br><span>　　接下来一个N*N的矩阵，矩阵中的每个数都在0~5之间，描述了每个格子的颜色。</span><br><span>　　N=0代表输入的结束。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　<span>对于每组数据，输出一个整数，表示最少步数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>0 0 <br>0 0<br>3<br>0 1 2<br>1 1 2<br>2 2 1<br>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于30%的数据，N&lt;=5</span><br><span>　　对于50%的数据，N&lt;=6</span><br><span>　　对于70%的数据，N&lt;=7</span><br><span>　　对于100%的数据，N&lt;=8，每个测试点不多于20组数据。</span><br><br><span>第二组样例解释：</span><br><span>　　0 1 2       1 1 2       2 2 2      1 1 1</span><br><span>　　1 1 2 --&gt; 1 1 2 --&gt; 2 2 2 --&gt; 1 1 1</span><br><span>　　2 2 1       2 2 1       2 2 1      1 1 1</span></p>
<p><span><br></span></p>
<p>来源：Nescafe 21</p>
</div>
</div>