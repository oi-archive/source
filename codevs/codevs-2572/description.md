<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Mr. Ling<span style="">打算好好修一下</span>学校门口的那条凹凸不平的路。按照<span style="font-family: Times New Roman;">Mr. </span>Ling的设想，修好后的路面高度应当单调上升或单调下降，也就是说，高度上升与高度下降的路段不能同时出现在修好的路中。</p>
<p>整条路被分成了<span style="font-family: Times New Roman;">N</span><span style="">段，</span><span style="font-family: Times New Roman;">N</span><span style="">个整数</span><span style="font-family: Times New Roman;">A_1</span>，…，A_N<span style="">依次描述了每一段路的高度。</span><span style="font-family: Times New Roman;">Mr.</span>Ling希望找到一个恰好含<span style="font-family: Times New Roman;">N</span><span style="">个元素的不上升或不下降序列</span><span style="font-family: Times New Roman;">B_1</span>，...，B_N<span style="">，作为修过的路中每个路段的高度。由于将每一段路垫高或挖低一个单位的花费相同，修路的总支出可以表示为：</span></p>
<p>|A_1 - B_1| + |A_2 - B_2| + ... + |A_N - B_N|</p>
<p>请你计算一下，<span style="font-family: Times New Roman;">Mr. Ling</span><span style="">在这项工程上的最小支出是多少。</span><span style="font-family: Times New Roman;">Mr. Ling</span><span style="">向你保证，这个支出不会超过</span><span style="font-family: Times New Roman;">2^31-1</span><span style="">。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第<span style="font-family: Times New Roman;">1</span><span style="">行</span>：输入<span style="font-family: Times New Roman;">1</span><span style="">个整数</span><span style="font-family: Times New Roman;">N</span>；</p>
<p>第<span style="font-family: Times New Roman;">2..N+1</span><span style="">行</span>：第<span style="font-family: Times New Roman;">i+1</span><span style="">行为</span>i个整数<span style="font-family: Times New Roman;">A_i</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">第<span style="font-family: Times New Roman;">1</span><span style="font-family: 宋体;">行</span>：输出<span style="font-family: Times New Roman;">1</span><span style="font-family: 宋体;">个正整数，表示把路修成高度不上升或高度不下降的最小花费</span>。</p>

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
<p>1</p>
<p>3</p>
<p>2</p>
<p>4</p>
<p>5</p>
<p>3</p>
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

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
<p>【样例说明】</p>
<p>将第一个高度为<span style="font-family: Times New Roman;">3</span><span style="">的路段的高度减少为</span><span style="font-family: Times New Roman;">2</span><span style="">，将第二个高度为</span><span style="font-family: Times New Roman;">3</span><span style="">的路段的高度增加到</span><span style="font-family: Times New Roman;">5</span><span style="">，总花费为</span><span style="font-family: Times New Roman;">|2-3|+|5-3| = 3</span><span style="">，并且各路段的高度为一个不下降序列</span><span style="font-family: Times New Roman;">1</span>，2，2，4，5，5，9<span style="">。</span></p>
<p>【数据范围】</p>
<p>30%<span style="">的数据：</span><span style="font-family: Times New Roman;">1&lt; N≤50</span>，0≤ A_i ≤1,000<span style="">；</span></p>
<p>100%<span style="">的数据：</span><span style="font-family: Times New Roman;">1≤ N≤2000</span>，0≤ A_i ≤1,000,000,000。</p>
<p> </p>
</div>
</div>
</div>