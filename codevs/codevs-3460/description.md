<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><br>   在社交媒体上，经常会看到针对某一个观点同意与否的民意调查以及结果。例如，对某一观点表示支持的有1498人，反对的有902人，那么赞同与反对的比例可以简单的记为1498:902。   </p><p>   不过，如果把调查结果就以这种方式呈现出来，大多数人肯定不会满意。因为这个比例的数值太大，难以一眼看出它们的关系。对于上面这个例子，如果把比例记为5:3，虽然与真实结果有一定的误差，但依然能够较为准确地反映调查结果，同时也显得比较直观。   </p><p>  现给出支持人数A，反对人数B，以及一个上限L，请你将A比B化简为A’比B’，要求在A’和B’均不大于L且A’和B’互质（两个整数的最大公约数是1）的前提下，A’/B’ ≥ A/B且A’/B’ - A/B的值尽可能小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入共一行，包含三个整数A，B，L，每两个整数之间用一个空格隔开，分别表示支持人数、反对人数以及上限。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共一行，包含两个整数 A’，B’，中间用一个空格隔开，表示化简后的比例。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1498 902 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 100%的数据，1 ≤ A ≤ 1,000,000，1 ≤ B ≤ 1,000,000，1 ≤ L ≤ 100，A/B ≤ L。</p>
</div>
</div>