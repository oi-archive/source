<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>已知一个 N 枚邮票的面值集合（如，{1 分，3 分}）和一个上限 K —— 表示信封上能够贴 K 张邮票。计算从 1 到 M 的最大连续可贴出的邮资。</p>
<p>例如，假设有 1 分和 3 分的邮票；你最多可以贴 5 张邮票。很容易贴出 1 到 5 分的邮资（用 1 分邮票贴就行了），接下来的邮资也不难：</p>
<pre>6 = 3 + 3
7 = 3 + 3 + 1
8 = 3 + 3 + 1 + 1
9 = 3 + 3 + 3
10 = 3 + 3 + 3 + 1
11 = 3 + 3 + 3 + 1 + 1
12 = 3 + 3 + 3 + 3
13 = 3 + 3 + 3 + 3 + 1</pre>
<p>然而，使用 5 枚 1 分或者 3 分的邮票根本不可能贴出 14 分的邮资。因此，对于这两种邮票的集合和上限 K=5，答案是 M=13。</p>
<p><br>小提示:因为14贴不出来,所以最高上限是13而不是15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行： 两个整数，K 和 N。K（1 &lt;= K &lt;= 200）是可用的邮票总数。N（1 &lt;= N &lt;= 50）是邮票面值的数量。</p>
<p>第 2 行 .. 文件末： N 个整数，每行 15 个，列出所有的 N 个邮票的面值，每张邮票的面值不超过 10000。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>第 1 行：一个整数，从 1 分开始连续的可用集合中不多于 K 张邮票贴出的邮资数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>5 2
1 3</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>13</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>上</p>
</div>
</div>