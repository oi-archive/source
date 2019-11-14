<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近，约翰的奶牛们越来越不满足于牛棚里一塌糊涂的电话服务，于是，她们要求<br>约翰把那些老旧的电话线换成性能更好的新电话线。新的电话线架设在已有的n根<br>电话线杆上，第i根电话线的高度为ℎ[i]，（1 ≤ ℎ[i] ≤ 100）。电话线总是从一根电话<br>线杆的顶端被引到相邻的那根的顶端，如果这两根电话线杆的高度ℎ[i]和ℎ[j]不同，那<br>么约翰就必须支付c∗|ℎ[i] − ℎ[j]|<br>|的费用，当然，你不能移动电话线杆，只能按照原有<br>的顺序在相邻杆间架设电话线。<br> 加高某些电话线杆能减少架设电话线的总费用，尽管这项工作也需要支付一定的<br>费用。更准确的说，如果他把一根电话线杆加高x米的话，他需要付出x^2费用。<br>请你帮约翰计算一下，如果合理的进行这两项工作，他最少要在这个电话线改造<br>工程中花多少钱。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入两个数n和c，含义如上<br>接下来n行，每行一个整数ℎ[i]</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出约翰完成电话线改造工程需要花费的最小费用</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2<br>2<br>3<br>5<br>1<br>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n ≤ 100000，c ≤ 100，h[i] ≤ 100，答案不超过maxlongint。</p>
</div>
</div>