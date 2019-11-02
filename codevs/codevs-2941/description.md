<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>唐僧师徒四人从长安城出发去西天取经。</p>
<p>路上有N座关卡，这些关卡的守将都不是省油的灯，不给钱就不让过。</p>
<p>从关卡i可以买去其他关卡（包括长安城）的通行证，价格为Aij。</p>
<p>终于，他们走遍了所有关卡，到了如来佛面前，他说：“请告诉我你们路上花的钱数，我相信你们聪明，一定走了最优方案。再加上你们到的最后一座关卡回家的最短路程，我就赐给你们经书。“</p>
<p>就连神通广大的孙悟空也算不出来了，他只记得路上通行证的价格，请你帮他算。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>N</p>
<p>N+1行列的邻接矩阵，Aij表示通行证（I-1)(J-1)的价格。</p>
<p>（Aij不一定等于Aji）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>答案</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>0 1 3</p>
<p>2 0 3</p>
<p>3 10 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=13</p>
</div>
</div>