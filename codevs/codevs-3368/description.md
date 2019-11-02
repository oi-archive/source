<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有N 个物品，编号为1...N.<br>用一架天平来称其中P 对物品的重量(天平2侧各放一件物品).<br>现在请你预测Q 对物品的放上天平后的情况。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行，3个数N,P,Q。<br>第2...P+1行，每行三个数K,A,B,表示物品A 和物品B 放上天平后的情况是K。<br>1表示天平向左倾斜，2表示天平向右倾斜，3表示天平平衡。<br>第P+2...P+Q+1行，每行两个数A,B,表示询问物品A 和物品B 放上天平后的情况。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个询问，输出一行。输出&ldquo;Left&rdquo;表示天平会向左倾斜，输出&ldquo;Right&rdquo;<br />表示天平会向右倾斜，输出&ldquo;Balance&rdquo;表示天平会平衡，<br />如果无法得出答案则输出&ldquo;Unknown&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3 5<br>1 1 2<br>3 1 3<br>1 4 3<br>1 2<br>1 3<br>2 3<br>1 4<br>2 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Left<br>Balance<br>Right<br>Right<br>Unknown</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=300,P&lt;=5000,Q&lt;=10^5</p>
</div>
</div>