<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<blockquote>
<p>有2n个棋子（n≥4）排成一行，开始为位置白子全部在左边，黑子全部在右边，如下图为n=5的情况：</p>
<p>       ○○○○○●●●●●</p>
<p>       移动棋子的规则是：每次必须同时移动相邻的两个棋子，颜色不限，可以左移也可以右移到空位上去，但不能调换两个棋子的左右位置。每次移动必须跳过若干个棋子（不能平移），要求最后能移成黑白相间的一行棋子。如n=5时，成为：</p>
<p>       ○●○●○●○●○●</p>
<p>       任务：编程打印出移动过程。</p>
</blockquote>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>n</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>编程打印出移动过程。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>step 0：ooooooo*******--</p>
<p>                                                              step 1：oooooo--******o*</p>
<p>                                                              step 2：oooooo******--o*</p>
<p>                                                              step 3：ooooo--*****o*o*</p>
<p>                                                              step 4：ooooo*****--o*o*</p>
<p>                                                              step 5：oooo--****o*o*o*</p>
<p>                                                              step 6：oooo****--o*o*o*</p>
<p>                                                              step 7：ooo--***o*o*o*o*</p>
<p>                                                              step 8：ooo*o**--*o*o*o*</p>
<p>                                                              step 9：o--*o**oo*o*o*o*</p>
<p>                                                              step 10：o*o*o*--o*o*o*o*</p>
<p>                                                              step 11：--o*o*o*o*o*o*o*</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;20</p>
</div>
</div>