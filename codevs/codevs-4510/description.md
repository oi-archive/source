<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">幻方是一种很神奇的</span>N<span style="font-family: 'MS Mincho';">∗</span>N<span style="">矩阵：它由数字</span> 1,2,3, … … ,N<span style="font-family: 'MS Mincho';">∗</span>N<span style="">构成，且每行、每列及两条对角线上的数字之和都相同。</span></p><p><span style="">当</span>N<span style="">为奇数时，我们可以通过以下方法构建一个幻方：</span></p><p><span style="">首先将</span> 1<span style="">写在第一行的中间。之后，按如下方式从小到大依次填写每个数</span>(K= 2,3, … ,N<span style="font-family: 'MS Mincho';">∗</span>N )<span style="">：</span></p><p>1.<span style="">若</span> (K−1)<span style="">在第一行但不在最后一列，则将</span> <span style="">填在最后一行</span>,(K−1)<span style="">所在列的右一列；</span></p><p>2.<span style="">若</span> (K−1)<span style="">在最后一列但不在第一行，则将填在第一列，</span>( K−1)<span style="">所在行的上一行；</span></p><p>3.<span style="">若</span> ( K−1)<span style="">在第一行最后一列，则将填在</span>(K −1)<span style="">的正下方；</span></p><p>4.<span style="">若</span> (K−1)<span style="">既不在第一行，也不在最后一列，如果</span>( K−1)<span style="">的右上方还未填数，</span></p><p><span style="">则将</span> K<span style="">填在</span>( K−1)<span style="">的右上方，否则将填在</span>( K− 1)<span style="">的正下方。</span></p><p><span style="">现给定</span>N<span style="">，请按上述方法构造</span>N<span style="font-family: 'MS Mincho';">∗</span>N<span style="">的幻方。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件只有一行，包含一个整数，即幻方的大小。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">输出文件包含</span>N<span style="font-family:宋体">行，每行</span>N<span style="font-family: 宋体">个整数，即按上述方法构造出的</span>N<span style="font-family:&#39;MS Mincho&#39;">∗</span>N<span style="font-family:宋体">的幻方。相邻两个整数之间用单个空格隔开。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8 1 6</p><p>3 5 7</p><p>4 9 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于</span> 100%<span style="">的数据，</span>1 ≤ N ≤ 39<span style="">且为奇数。</span></p><p><br></p>
</div>
</div>