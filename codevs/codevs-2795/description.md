<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个大考场里，有<span style="font-family: Times New Roman;">n</span><span style="">行</span><span style="font-family: Times New Roman;">m</span><span style="">列</span>个考生，这时有一部分考生在作弊，当然，监考老师能发现他们。但是只有一个监考老师，他由于高度近视，只能发现与他同行同列的作弊者，而且由于监考老师年老体弱，在考试过程中无法移动。</p>
<p>现在已知<span style="font-family: Times New Roman;">n*m</span><span style="">个考生中谁在作弊，请帮监考老师找一个位置，可以发现最多的作弊者（监考老师可以和某个考生在同一位置）。如果监考老师</span>所在的位置上的考生在作弊，那么监考老师先前后看，发现他作弊，再左右看，又发现他作弊，算做发现<span style="font-family: Times New Roman;">2</span><span style="">个考生作弊</span>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个数<span style="font-family: Times New Roman;">n,m,</span><span style="">表示</span>考场是<span style="font-family: Times New Roman;">n</span>行m列。</p>
<p>接下来是<span style="font-family: Times New Roman;">n*m</span><span style="">的矩阵，</span><span style="font-family: Times New Roman;">1</span><span style="">表示作弊，</span><span style="font-family: Times New Roman;">0</span><span style="">表示不作弊。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一行一个整数，表示最多可以发现多少作弊者。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5</p>
<p>1 0 1 0 0</p>
<p>0 0 1 0 0</p>
<p>1 1 1 1 1</p>
<p>0 0 1 0 0</p>
<p>0 0 1 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>50%<span style="">的数据满足：</span>n,m≤100；</p>
<p>100%<span style="">的数据满足：</span>n,m≤1000<span style="">。</span></p>
</div>
</div>
</div>