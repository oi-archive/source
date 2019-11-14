<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农民约翰打算建一个新的矩形谷仓。但是,矩形谷仓的4个角落不能在落在软土路基上,只能落在一些固定点上。现在,他已经找到地面上有N（4 &lt;= N &lt;= 1,000）个点,角落只可以落在这些点上。他想知道依次每加多一个点，可以建立新谷仓的方法数量,请你帮助他找到答案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：一个整数，N</p>
<p>第2行至N +1行：每行有两个被空格分隔的整数的x，y,作为一个点的坐标。</p>
<p>        所有的x,y都不会超过16,000。所有点都是不同的。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共 N 行：每行表示当前可以建立的新的谷仓的数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8</p>
<p>1 2</p>
<p>1 -2</p>
<p>2 1</p>
<p>2 -1</p>
<p>-1 2</p>
<p>-1 -2</p>
<p>-2 1</p>
<p>-2 -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>
<p>0</p>
<p>0</p>
<p>0</p>
<p>0</p>
<p>1</p>
<p>3</p>
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
<p><strong>样例解释：</strong></p>
<p>最后的答案是（1,2,6,5），（1,3,6,8），（1,4,6,7），（2,3,5,8），（2,4,5,7），（3,4,8,7）</p>
</div>
</div>