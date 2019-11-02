<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><em><span style="">（经典问题系列第四题）</span></em></p><p style=""><em>CodeVS</em> 国总统 <em>sqrt_-1</em> 最近打算在 <em>Master</em> 市修高速路，他想修 <em>N </em>个入口，其中有 <em>K</em> 个“链条”入口。如果一个入口只与另一个入口相连，那么我们称这个入口为“链条”入口。对于除了“链条”入口以外的入口，都与至少两个入口（包括“链条”入口）相连。为了让交通便捷，所以需要使相隔最远的“链条”入口最近。</p><p style="">你能帮助 <em>sqrt_-1</em> 解决这个问题吗？为了简化问题，你只用求出这个距离，不用输出方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入两个数 <em style="">N</em>, <em style="">K，</em>分别表示入口数和“链条”入口数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个数 Ans，表示这个距离。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">input1:<br></p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">3 2</pre><p style="">input2:</p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">5 3</pre><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">output1:</p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">2</pre><p style="">outpu2:</p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">3</pre><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">数据范围：</p><p style="">3 <span style="font-family: 'times new roman', sans-serif;">≤ <em>n</em> <span style="">≤ 2 * 10^5，2 <span style="">≤ <em>k</em> <span style="">≤ <em>n</em> - 1。</span></span></span></span></p><p style=""><span style="font-family: 'times new roman', sans-serif;"><span style=""><span style=""><span style="">提示：（代表连接方案）</span></span></span></span></p><p style=""><span style="font-family: 'times new roman', sans-serif;"><span style="font-family: arial, helvetica, sans-serif;">input1:</span></span></p><p style=""><span style="font-family: 'times new roman', sans-serif;"><span style=""><span style=""><span style=""></span></span></span></span></p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">1 2
2 3
(1, 3 为“链条”入口)</pre><p style=""><span style="font-family: 'times new roman', sans-serif;"><span style=""><span style=""><span style=""></span></span></span></span>input2:</p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">1 2
2 3
3 4
3 5
(1, 4, 5 为“链条”入口)</pre><p></p>
</div>
</div>