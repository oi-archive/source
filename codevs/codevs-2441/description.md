<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给一个数字串<em>s</em>和正整数<em>d</em>, 统计<em>s</em>有多少种不同的排列能被<em>d</em>整除（可以有前导0）。例如123434有90种排列能被2整除，其中末位为2的有30种，末位为4的有60种。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行是一个整数<em>T</em>，表示测试数据的个数，以下每行一组<em>s</em>和<em>d</em>，中间用空格隔开。s保证只包含数字0, 1, 2, 3, 4, 5, 6, 7, 8, 9.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每个数据仅一行，表示能被<em>d</em>整除的排列的个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>000 1</p>
<p>001 1</p>
<p>1234567890 1</p>
<p>123434 2</p>
<p>1234 7</p>
<p>12345 17</p>
<p>12345678 29</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>3</p>
<p>3628800</p>
<p>90</p>
<p>3</p>
<p>6</p>
<p>1398</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>20%的数据满足：<em>s</em>的长度不超过5, 1&lt;=<em>T</em>&lt;=5</p>
<p>50%的数据满足：<em>s</em>的长度不超过8</p>
<p>100%的数据满足：<em>s</em>的长度不超过10, 1&lt;=<em>d</em>&lt;=1000, 1&lt;=<em>T</em>&lt;=15,</p>
</div>
</div>