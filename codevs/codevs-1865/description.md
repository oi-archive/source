<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong>某地区有m座煤矿，其中第i号矿每年产量为a<sub>i</sub>吨，现有火力发电厂一个，每年需用煤b吨，每年运行的固定费用（包括折旧费，不包括煤的运费）为h元，每吨原煤从第i号矿运到原有发电厂的运费为C<sub>i0</sub>（i=1，2，…，m）。</strong><strong></strong></p>
<p><strong> </strong></p>
<p><strong>现规划新建一个发电厂，m座煤矿每年开采的原煤将全部供给这两座发电厂。现有n个备选的厂址。若在第j号备选厂址建新厂，每年运行的固定费用为h<sub>j</sub>元。每吨原煤从第i号矿运到j号备选厂址的运费为C<sub>ij</sub>（i=1，2，…，m；j=1，2，…，n）。</strong><strong></strong></p>
<p><strong> </strong></p>
<p><strong>试问：应把新厂厂址选取在何处？m座煤矿开采的原煤应如何分配给两个发电厂，才能使每年的总费用（发电厂运行费用与原煤运费之和）为最小。 </strong><strong></strong></p>
<div><strong><br></strong></div>
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
<p><strong>第1行：      m  b  h  n</strong></p>
<p><strong>第2行：      a<sub>1</sub>  a<sub>2</sub> …  a<sub>m</sub> </strong><strong>（0&lt;=a<sub>i</sub>&lt;=500, a<sub>1</sub>+a<sub>2</sub>+...+a<sub>n</sub>&gt;=b</strong><strong>）</strong><strong></strong></p>
<p><strong>第3行：      h<sub>1</sub>  h<sub>2</sub> …  h<sub>n</sub> </strong><strong>（0&lt;=h<sub>i</sub>&lt;=100</strong><strong>）</strong><strong></strong></p>
<p><strong>第4行：      C<sub>10</sub> C<sub>20</sub> … C<sub>m0</sub> </strong><strong>（0&lt;=Cij&lt;=50</strong><strong>）</strong></p>
<p><strong>第5行：      C<sub>11</sub> C<sub>21</sub> … C<sub>m1</sub></strong></p>
<p><strong>                              …   …</strong></p>
<p><strong>第</strong><strong>n+4行：C<sub>1n</sub> C<sub>2n</sub> … C<sub>mn</sub></strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><strong>第1行：新厂址编号，如果有多个编号满足要求，输出最小的。</strong></p>
<p><strong>第2行：总费用&nbsp;</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 2 7 9 </span><br><span> 3 1 10 3 </span><br><span> 6 3 7 1 10 2 7 4 9 </span><br><span> 1 2 4 3 </span><br><span> 6 6 8 2 </span><br><span> 4 10 8 4 </span><br><span> 10 2 9 2 </span><br><span> 7 6 6 2 </span><br><span> 9 3 7 1 </span><br><span> 2 1 6 9 </span><br><span> 3 1 10 9 </span><br><span> 4 2 1 8 </span><br><span> 2 1 3 4 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>8 </span><br><span> 49 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong><span>对于所有数据, n&lt;=50, m&lt;=50000, b&lt;=10000 </span></strong></p>
</div>
</div>