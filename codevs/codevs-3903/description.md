<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个 n 行 n 列的螺旋矩阵可由如下方法生成：</p><p>从矩阵的左上角（第 1 行第 1 列）出发，初始时向右移动；如果前方是未曾经过的格子， 则继续前进，否则右转；重复上述操作直至经过矩阵中所有格子。根据经过顺序，在格子中 依次填入 1, 2, 3, ... , n2，便构成了一个螺旋矩阵。</p><p>下图是一个 n = 4 时的螺旋矩阵。</p><p>1  2  3  4</p><p>12  13  14  5</p><p>11  16  15  6</p><p>10  9  8  7</p><p>现给出矩阵大小 n 以及 i 和 j，请你求出该矩阵中第 i 行第 j 列的数是多少。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入共一行，包含三个整数 n，i，j，每两个整数之间用一个空格隔开，分别表示矩阵大小、待求的数所在的行号和列号。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Lucida Grande&#39;, Lucida, &#39;Lucida Sans Unicode&#39;, &#39;Lucida Sans&#39;, Tahoma, &#39;Segoe UI&#39;, Verdana, 微软雅黑, &#39;Microsoft YaHei&#39;, 宋体; font-size: 14px; line-height: 21px; background-color: rgb(255, 255, 255);">输出共一行，包含一个整数，表示相应矩阵中第 i 行第 j 列的数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于 50%的数据，1 ≤ n ≤ 100;</span><br style=""><span style="">对于 100%的数据，1 ≤ n ≤ 30,000，1 ≤ i ≤ n，1 ≤ j ≤ n。</span></p>
</div>
</div>