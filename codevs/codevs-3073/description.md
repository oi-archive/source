<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小哀想去穿越，穿越之前要和所有家人和朋友告别，她想知道这一个过程需要多长时间，请你帮她计算一下。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个n，表示亲朋个数</p>
<p>2—n+1行，每行一个字符串（大、小写字母）和一个数字f，表示亲朋姓名和重要程度。（姓名与重要程度间空格隔开）</p>
<p>与亲朋的告别时间=（姓名中大写字母在字母表中第几个*姓名中第几个-姓名中小写字母在字母表中第几个*2）*重要程度</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>1行，一个数字，表示总告别时间</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>Wx -2</p>
<p>MiSs 5</p>
<p>ZzZf 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>520</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>姓名长度&lt;10</p>
<p>-100≤f≤100</p>
</div>
</div>