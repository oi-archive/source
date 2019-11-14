<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><span style="">帅帅经常跟同学玩一个矩阵取数游戏：对于一个给定的</span></span><span style="">n*m</span><span style=""><span style="">的矩阵，矩阵中的每个元素</span></span><span style="">aij</span><span style=""><span style="">均为非负整数。游戏规则如下：</span></span><span style="">  </span></p><p><span style="">1.</span><span style=""><span style="">每次取数时须从每行各取走一个元素，共</span></span><span style="">n</span><span style=""><span style="">个。</span></span><span style="">m</span><span style=""><span style="">次后取完矩阵所有元素；</span></span><span style=""> </span></p><p><span style="">2.</span><span style=""><span style="">每次取走的各个元素只能是该元素所在行的行首或行尾；</span></span></p><p><span style="">3.</span><span style=""><span style="">每次取数都有一个得分值，为每行取数的得分之和，每行取数的得分</span></span><span style="">=</span><span style=""><span style="">被取走的元素值</span></span><span style="">*2</span><sup><span style="">i</span></sup><span style=""><span style="">，其中</span></span><span style="">i</span><span style=""><span style="">表示第</span></span><span style="">i</span><span style=""><span style="">次取数（从</span></span><span style="">1</span><span style=""><span style="">开始编号）；</span></span></p><p><span style="">4.</span><span style=""><span style="">游戏结束总得分为</span></span><span style="">m</span><span style=""><span style="">次取数得分之和。</span></span></p><p><span style="">  </span><span style="">  <span style="">帅帅想请你帮忙写一个程序，对于任意矩阵，可以求出取数后的最大得分。</span></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="">输入包括</span></span><span style="">n+1</span><span style=""><span style="">行：</span></span></p><p style=""><span style=""><span style="">第</span></span><span style="">1</span><span style=""><span style="">行为两个用空格隔开的整数</span></span><span style="">n</span><span style=""><span style="">和</span></span><span style="">m</span><span style=""><span style="">。</span></span></p><p><span style=""><span style="">第</span></span><span style="">2~n+1</span><span style=""><span style="">行为</span></span><span style="">n*m</span><span style=""><span style="">矩阵，其中每行有</span></span><span style="">m</span><span style=""><span style="">个用单个空格隔开的非负整数。</span></span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style=";font-family:宋体;font-size:14px"><span style="font-family:宋体">输出仅包含</span></span><span style=";font-family:宋体;font-size:14px">1</span><span style=";font-family:宋体;font-size:14px"><span style="font-family:宋体">行，为一个整数，即输入矩阵取数后的最大得分。</span></span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">2 3 </span></p><p><span style="">1 2 3 </span></p><p><span style="">3 4 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">82</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">60%</span><span style=""><span style="">的数据满足：</span></span><span style="">1&lt;=n, m&lt;=40, </span><span style=""><span style="">答案不超过</span></span><span style="">10</span><sup><span style="">16</span></sup></p><p><span style="">100%</span><span style=""><span style="">的数据满足：</span></span><span style="">1&lt;=n, m&lt;=100, 0&lt;=a[i][j]&lt;=1000</span></p><p><br></p>
</div>
</div>