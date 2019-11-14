<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>Z城市居住着很多只跳蚤。在Z城市周六生活频道有一个娱乐节目。一只跳蚤将被请上一个高空钢丝的正中央。钢丝很长，可以看作是无限长。节目主持人会给该跳蚤发一张卡片。卡片上写有N+1个自然数。其中最后一个是M，而前N个数都不超过M，卡片上允许有相同的数字。跳蚤每次可以从卡片上任意选择一个自然数S，然后向左，或向右跳S个单位长度。而他最终的任务是跳到距离他左边一个单位长度的地方，并捡起位于那里的礼物。</span><br><span>比如当N=2，M=18时，持有卡片(10, 15, 18)的跳蚤，就可以完成任务：他可以先向左跳10个单位长度，然后再连向左跳3次，每次15个单位长度，最后再向右连跳3次，每次18个单位长度。而持有卡片(12, 15, 18)的跳蚤，则怎么也不可能跳到距他左边一个单位长度的地方。</span><br><span>当确定N和M后，显然一共有M^N张不同的卡片。现在的问题是，在这所有的卡片中，有多少张可以完成任务。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>两个整数N和M(N &lt;= 15 , M &lt;= 100000000)。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>可以完成任务的卡片数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>2 4</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>12</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>答案不超longlong</p>
</div>
</div>