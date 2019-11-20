<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有N个任务和两台机器A与B。每个任务都需要既在机器A上执行，又在机器B上执行，第i个任务需要在机器A上执行时间A<sub>i</sub>，且需要在机器B上执行时间B<sub>i</sub>。最终的目标是所有任务在A和B上都执行完，且希望执行完所有任务的总时间尽量少。当然问题没有这么简单，有些任务对于先在机器A上执行还是先在机器B上执行有一定的限制。据此可将所有任务分为三类：</p>
<ol>
<li>任务必须先在机器A上执行完然后再在机器B上执行。</li>
<li>任务必须先在机器B上执行完然后再在机器A上执行。</li>
<li>任务没有限制，既可先在机器A上执行，也可先在机器B上执行。</li>
</ol>
<p>现在给定每个任务的类别和需要在机器A和机器B上分别执行的时间，问使所有任务都能按规定完成所需要的最少总时间是多少。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行只有一个正整数N(1≤N≤20)，表示任务的个数。接下来的N行，每行是用空格隔开的三个正整数T<sub>i</sub>, A<sub>i</sub>, B<sub>i</sub>(1≤T<sub>i</sub>≤3, 1≤A<sub>i</sub>, B<sub>i</sub>≤1000)，分别表示第i个任务的类别(类别1, 2, 3的定义如上)以及第i个任务需要在机器A和机器B上分别执行的时间。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅包含一个正整数，表示所有任务都执行完所需要的最少总时间。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>3 5 7<br>1 6 1<br>2 2 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><img height="64" src="/source/codevs/codevs-2411/img/aHR0cDovL3AxMy5mcmVlcC5jbi9wLmFzcHg_dT12MjBfcDEzX3Bob3RvXzEzMDUwMzIxNDY1OTQ3MTZfMC5wbmc=.png" width="610"></p>
<p>范围见描述</p>
</div>
</div>