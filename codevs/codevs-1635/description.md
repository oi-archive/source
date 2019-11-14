<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>N<span style="">个数排成一排，你可以任意选择连续的若干个数，算出它们的和。问该如何选择才能使得和的绝对值最小。</span></p>
<p>如：<span style="font-family: 'Times New Roman';">N=8</span><span style="">时，</span><span style="font-family: 'Times New Roman';">8</span><span style="">个数如下</span><span style="font-family: 'Times New Roman';">:</span></p>
<p>1    2    3    4    5    6    7    8</p>
<p>-20   90  -30   -20   80  -70  -60   125</p>
<p>如果我们选择<span style="font-family: 'Times New Roman';">1</span><span style="">到</span><span style="font-family: 'Times New Roman';">4</span><span style="">这</span><span style="font-family: 'Times New Roman';">4</span><span style="">个数，和为</span><span style="font-family: 'Times New Roman';">20</span><span style="">，还可以选择</span><span style="font-family: 'Times New Roman';">6</span><span style="">到</span><span style="font-family: 'Times New Roman';">8</span><span style="">这</span><span style="font-family: 'Times New Roman';">3</span><span style="">个数，和为</span><span style="font-family: 'Times New Roman';">-5</span><span style="">，</span><span style="font-family: 'Times New Roman';">|-5|=5,</span><span style="">该方案获得的和的绝对值最小。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入<span style="font-family: 'Times New Roman';">N</span><span style="">，表示数字的个数。接下来</span><span style="font-family: 'Times New Roman';">N</span><span style="">行描述这</span><span style="font-family: 'Times New Roman';">N</span><span style="">个数字。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">第一行输出一个整数，表示最小绝对值的和，第二行包含两个整数表示形成该绝对值和最长序列的长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>20<br>12<br>-220<br>-195<br>-316<br>-300<br>668<br>576<br>1034<br>1055<br>972<br>-1023<br>866<br>-1469<br>492<br>857<br>1954<br>1685<br>1046<br>-1748<br>-1480</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12<br>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据说明：</p>
<p>40%<span style="">的数据 </span><span style="font-family: 'Times New Roman';">N&lt;=4000</span></p>
<p>对于许多数据，最长序列的长度唯一。</p>
<p>100%<span style="">的数据 </span><span style="font-family: 'Times New Roman';">N&lt;=100000,|</span><span style="">每个数字的值</span><span style="font-family: 'Times New Roman';">|&lt;=10^10</span></p>
</div>
</div>