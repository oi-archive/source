<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>JYY最近迷上了拼图游戏。作为一个计算机科学家，JYY有一套黑白色的拼图，他希望通过合理的拼接，使得拼出的最终图案中，能包含面积最大的全白色子矩形。</p>
<p>JYY一共有S块拼图，并且由1到S编号。编号为i的拼图是一个N行 Wi列的方格矩形，每个方格都为黑色或者白色。 </p>
<p>一开始JYY将他的这S块拼图按照编号顺序左右相连依次放在桌上拼成了一个大矩形。 </p>
<p>之后JYY发现，可以通过改变这S块拼图的连接次序，使得拼成的大矩形中，最大全白子矩形面积变大。 </p>
<p>现在JYY想知道，怎么拼才能得到最大的全白子矩形呢？请你帮助他计算出最佳的拼接方案。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>每个输入文件中包含多组测试数据。输入文件第一行包含一个整数T，代表测试数据的组数，接下来按顺序描述了每组测试数据。 </p>
<p>每组测试数据的第一行包含两个整数S和N。 </p>
<p>接下来S组输入，第i组对应编号为i的拼图。 </p>
<p>在第i组输入中，第一行包含一个整数 Wi； </p>
<p>接下来N行描述一个N行Wi 列的0/1矩形； </p>
<p>其中第x行y列为0则表示该拼图对应位置的颜色是白色，反之则为黑色。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>对于每组数据输出一行包含一个整数</span><span>ans</span><span>，表示最大可能的全白色子矩形的面积。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 </p>
<p>3 4 </p>
<p>4 </p>
<p>1001 </p>
<p>0000 </p>
<p>0010 </p>
<p>1001 </p>
<p>3 </p>
<p>000 </p>
<p>010 </p>
<p>000 </p>
<p>011 </p>
<p>2 </p>
<p>00 </p>
<p>10 </p>
<p>01 </p>
<p>00 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据满足S,N,Wi≤10^5，T≤3，N≤10^5。</p>
</div>
</div>