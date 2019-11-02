<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;"><span style="">小</span>y<span style="">把他的</span>N只狗 排成一条直线，然后测量这些狗的高度。每个狗的高度都是一个正整数。他想要从中挑选一个连续的子序列，给这些子序列中的狗拍照，然后将照片提交给一个组委会参加评选活动。</p><p style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">但是，组委会有一个特殊的规定，提交的狗<span style="">的子序列的平均高度值不能小于某个值</span>X。他们是这么定义这个平均高度的，在序号0到k的狗中（高度已经从小到大排序），平均高度的狗<span style="">的位置在</span>ceiling(k/2)，其中ceiling表示四舍五入到整数。例如，序列[7,3,2,6]的平均高度是6，序列[5,4,8]的平均高度是5。</p><p style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;"><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">请帮助</span><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">小</span><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">y计算满足条件的连续子序列有多少种。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;"><span style="">第一行两个整数</span>N和X。</p><p style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;"><span style="">第</span>2行到第N+1行，每行一个正整数表示狗的高度。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgba(0, 0, 0, 0.870588); font-family: Lato, &#39;Helvetica Neue&#39;, Arial, Helvetica, sans-serif; font-size: 21px; line-height: 29.9985008239746px; background-color: rgb(239, 239, 239);">仅有一行一个整数，表示这样的子序列的个数。要注意这个结果可能比较大。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre style="font-family: monospace, monospace;">4  6
10
5
6
2</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre style="font-family: monospace, monospace;">7</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">1&lt;=N&lt;=100000。狗</span><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">的高度是不超过</span><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">10亿的正整数。</span></p><p><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;"><span style="font-weight: 700; font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">说明：</span><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">样例中，</span><span style="font-family: Lato, 'Helvetica Neue', Arial, Helvetica, sans-serif;">7种方案分别是：[10],[6],[10,5],[5,6],[6,2],[10,5,6],[10,5,6,2]。</span></span></p>
</div>
</div>