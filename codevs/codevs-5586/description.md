<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">在修建完新路后，小猴们总算可以安心入学了。今年是猴年，新入学的小<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span></span>特别多。老师们打算将N只小<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span>分成M个班级，每个班至少有1只<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span>。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">如何分班成了老师们最头疼的事情，因为开学典礼上，猴王辉就要看到小<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span>们列队的情况。每个班的小<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span>都排成一排，站在草场上。<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴王辉</span>希望队列中<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span>的高度尽可能整齐，<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴王辉</span>对队列的不整齐度有自己的要求。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">例如队列中共有t只<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span>，高度依次为A1，A2……，At。那么不整齐度为：(|A1-A2|+|A2-A3|+……+|At-1-At|)</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">2</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">。即相邻两只<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span>高度差之和的平方。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">而总体的不整齐度，就是各班不整齐度之和。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">现在，请你帮助老师们设计一下，如何分班，如何列队，才能使M个班级的不整齐度之和最小。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">第一行两个整数N和M，分别表示共有N只小<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span>，要被分成M个班级。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">第二行N个整数，表示每只小<span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">猴</span>的高度Ai。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);">输出最小的不整齐度之和，结果保证不会超过2</span><span style="position: relative; font-size: 12px; line-height: 0; vertical-align: baseline; top: -0.5em; color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; background-color: rgb(228, 240, 248);">31</span><span style="color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);">-1。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">4 2</span></p><p><span style="font-family: monospace;">4 1 3 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">【样例解释】<br><br>分成两班，4和3一个班，1和2一个班，不管怎么排，两个班的不整齐度都是1，不整齐度之和为2。</p><p><br style="font-family: 'Times New Roman';"></p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">【数据范围】<br><br>30%的数据，1&lt;=N&lt;=10；1&lt;=M&lt;=5；<br><br>80%的数据，1&lt;=N&lt;=300；1&lt;=Ai&lt;=1000；<br><br>100%的数据，1&lt;=N&lt;=10000,1&lt;=M&lt;=1000，1&lt;=Ai&lt;=1000000，保证M&lt;=N。</p><p><br></p>
</div>
</div>