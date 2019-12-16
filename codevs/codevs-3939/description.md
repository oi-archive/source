<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有n对围棋子（4=&lt;N&lt;=30）排成一行， 开始位置为白子全部在左边，黑子全部在白子的右边，如下图。</p><p>其中Ｏ表示白子，＊表示黑子。</p><p>ＯＯＯＯＯ＊＊＊＊＊</p><p>按如下规则移动棋子：每次必须同时移动相邻的两个棋子，颜色不限，可以左移也可以右移。移动时，</p><p>必须跳过若干个棋子。最后应成为黑白相间的一行棋子：</p><p>Ｏ＊Ｏ＊Ｏ＊Ｏ＊Ｏ＊</p><p>要求输出每次移动后的状态图和达到目标的总步数。 其中， “Ｏ”表示白子，用“＊”表示黑子， 用“＿”</p><p>表示空格。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>只有一行，就是正整数N</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若干行，第一行输出初始状态，后面的按移动的顺序输出状态，每行一个状态，最后一行输出移动的总步数</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>OOOO****--</p><p>OOO--***O*</p><p>OOO*O**--*</p><p>O--*O**OO*</p><p>O*O*O*--O*</p><p>--O*O*O*O*</p><p>5</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>4&lt;=N&lt;=30</p>
</div>
</div>