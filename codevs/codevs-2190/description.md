<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>对于一个素数P，我们可以用一系列有理分数(分子、分母都是不大于N的自然数)来逼近sqrt(p)，例如P=2，N=5的时候：1/1&lt;5/4&lt;4/3&lt;sqrt(2)&lt;3/2&lt;5/3&lt;2/1。<br>任　务　：<br>给定P、N（N&gt;sqrt(p)），求X、Y、U、V，使x/y&lt;sqrt(p)&lt;u/v且x/y与sqrt(p)之间、sqrt(p)与u/v之间都不能再插入满足题意的有理分数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行为P、N</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只有一行，格式为&ldquo;X/Y U/V&rdquo;。注意，答案必须是既约的，也就是说分子、分母的最大公约数必须等于1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：<br>2 5<br>样例2：<br>5 100</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：<br>4/3 3/2</p>
<p>样例2：<br>38/17 85/38</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> P、N&lt;30000</p>
</div>
</div>