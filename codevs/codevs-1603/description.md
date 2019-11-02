<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小王是公司的仓库管理员，一天，他接到了这样一个任务：从仓库中找出一根钢管。这听起来不算什么，但是这根钢管的要求可真是让他犯难了，要求如下：<br> 1、 这根钢管一定要是仓库中最长的；<br> 2、 这根钢管一定要是最长的钢管中最细的；<br> 3、 这根钢管一定要是符合前两条的钢管中编码最大的（每根钢管都有一个互不相同的编码，越大表示生产日期越近）。<br> 相关的资料到是有，可是，手工从几百份钢管材料中选出符合要求的那根…… <br> 要不，还是请你编写个程序来帮他解决这个问题吧。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件第一行为一个整数 n，表示仓库中所有钢管的数量。<br> 之后n行，每行三个整数，分别表示一根钢管的长度（以毫米为单位）、直径（以毫米为单位）和编码（一个9位整数）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一个9位整数，表示选出的那根钢管的编码。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br> 3000 50 872198442<br> 3000 45 752498124<br> 2000 60 765128742<br> 3000 45 652278122</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>752498124</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=1000</p>
</div>
</div>