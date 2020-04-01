<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><strong style="">欢迎访问“JL”题库更多题目，搜索框输入“JL”即可</strong></span></p><p style="">读程序写结果（普及组）</p><p style=""><span style="font-family: 'Microsoft YaHei';">const</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">u: array[0..2] of integer = (1, -3, 2);</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">v: array[0..1] of integer = (-2, 3);</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">var</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">i, n, sum: integer;</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">function g(n: integer): integer;</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">var i, sum: integer;</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">begin</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">sum := 0;</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">for i := 1 to n do inc(sum, u[i mod 3] * i);</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">g := sum;</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">end;</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">begin</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">sum := 0;</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">read(n);</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">for i := 1 to n do inc(sum, v[i mod 2] * g(i));</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">writeln(sum);</span><br style="font-family: 'Microsoft YaHei';"><span style="font-family: 'Microsoft YaHei';">end.</span></p><p style=""><span style="font-family: 'Microsoft YaHei';"><span style="">输入：103</span></span></p><p style=""><span style="font-family: 'Microsoft YaHei';">编写一个程序，输出这个输入对应的结果</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>NONE</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>NONE</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>NONE</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>NONE</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>NONE</p>
</div>
</div>