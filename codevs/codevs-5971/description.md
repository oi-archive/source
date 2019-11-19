<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    某个地区有n(n&lt;=1000)个犯罪团伙，当地警方按照他们的危险程度由高到低给他们编号为1-n，他们有些团伙之间有直接联系，但是任意两个团伙都可以通过直接或间接的方式联系，这样这里就形成了一个庞大的犯罪集团，犯罪集团的危险程度唯一由集团内的犯罪团伙数量确定，而与单个犯罪团伙的危险程度无关（该犯罪集团的危险程度为n）。现在当地警方希望花尽量少的时间（即打击掉尽量少的团伙），使得庞大的犯罪集团分离成若干个较小的集团，并且他们中最大的一个的危险程度不超过n/2。为达到最好的效果，他们将按顺序打击掉编号1到k的犯罪团伙，请编程求出k的最小值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　  第一行一个正整数n。接下来的n行每行有若干个正整数，第一个整数表示该行除第一个外还有多少个整数，若第i行存在正整数k，表示i，k两个团伙可以直接联系。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 一个正整数，为k的最小值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> 7<br> 2 2 5<br> 3 1 3 4<br> 2 2 4<br> 2 2 3<br> 3 1 6 7<br> 2 5 7<br> 2 5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>  1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=1000</p><p> <img src="/source/codevs/codevs-5971/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01OTcxL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE3MDQxMjE5NTIwMl82MTIucG5n.png" title=""></p><p>输出1（打击掉红色团伙)<br></p>
</div>
</div>