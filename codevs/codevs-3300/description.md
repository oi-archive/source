<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有n个旅客来到了一个旅游景点，你作为一个导游要给这n个旅客安排旅游路线。如果你安排了第i个旅客去旅游，那么你会得到xi的钱（若xi为负数，则你需要给他﹣xi的钱）。</p>
<p>对于第i个顾客，他有ki个要求。每个要求是一个二元组<span style="font-family: 'Times New Roman';">(</span>aij, bij)<span style="">，表示如果你安排了顾客</span>i去，但是没有安排顾客aij去，那么xi就要减去bij。</p>
<p>问如何安排顾客才能获得最大的收益。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个正整数n。 </p>
<p>接下来n行，每行第一个数为xi，第二个数为ki，之后有ki个二元组<span style="font-family: 'Times New Roman';">(</span>aij, bij)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">仅包含一个整数，为最大的收益。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>5 0</p>
<p>6 2 1 10 3 1</p>
<p>-10 0</p>
<p>1 2 1 10 2 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，</span>n ≤ 20<span style="">。</span></p>
<p>对于<span style="font-family: 'Times New Roman';">60%</span><span style="">的数据，</span>n ≤ 300<span style="">。</span></p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，</span>n ≤ 1000<span style="">。</span></p>
</div>
</div>