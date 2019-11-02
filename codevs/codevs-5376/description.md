<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个数列a1,a2,...,an（n≤50000）.现在有4种操作：<br></p><p>1：将al,...,ar中的数平方后模4294967296。</p><p>2：求al xor ... xor ar的值。</p><p>3：求max(al,...,ar)。</p><p>4：求al and ... and ar。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数n,m(n,m≤50000）表示数列长和操作数</p><p>第二行n个整数ai，ai≤1000000</p><p>第三行到第m+2行，每行包含三个整数，表示一个操作，具体如下：</p><p>操作1：格式 1 l r<br></p><p>操作2：格式 2 l r</p><p>操作3：格式 3 l r</p><p>操作4：格式 4 l r</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Segoe UI&#39;, &#39;Lucida Grande&#39;, Helvetica, Arial, &#39;Microsoft YaHei&#39;, FreeSans, Arimo, &#39;Droid Sans&#39;, &#39;wenquanyi micro hei&#39;, &#39;Hiragino Sans GB&#39;, &#39;Hiragino Sans GB W3&#39;, FontAwesome, sans-serif; font-size: 15px; line-height: 24px; background-color: rgba(255, 255, 255, 0.8);">输出包含若干行整数，即为所有操作2、3、4的结果。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 2<br></p><p>1 1 1 1 1 1 1 1 1 1</p><p>1 1 10</p><p>3 1 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如题中所示</p>
</div>
</div>