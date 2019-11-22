<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>《集合论与图论》这门课程有一道作业题，要求同学们求出{1, 2, 3, 4, 5}的所有满足以下条件的子集：若x在该子集中，则2x和3x不能在该子集中。同学们不喜欢这种具有枚举性质的题目，于是把它变成了以下问题：对于任意一个正整数n，如何求出{1, 2,..., n} 的满足上述约束条件的子集的个数（只需输出对1,000,000,001取模的结果），现在这个问题就交给你了。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>只有一行，其中有一个正整数<span>n</span>，</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅包含一个正整数，表示<span lang="EN-US">{1, 2,..., n}</span>有多少个满足上述约束条件的子集。</span></p>

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

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>样例解释</strong></p>
<p>有8个集合满足要求，分别是空集，{1}，{1，4}，{2}，{2，3}，{3}，{3，4}，{4}。 </p>
<p> </p>
<p><strong>数据范围</strong></p>
<p>30%数据，n≤20</p>
<p>全部数据，n≤10<sup>5</sup></p>
</div>
</div>