<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个神奇的小镇上有着一个特别的电车网络，它由一些路口和轨道组成，每个路口都连接着若干个轨道，每个轨道都通向一个路口（不排除有的观光轨道转一圈后返回路口的可能）。在每个路口，都有一个开关决定着出去的轨道，每个开关都有一个默认的状态，每辆电车行驶到路口之后，只能从开关所指向的轨道出去，如果电车司机想走另一个轨道，他就必须下车切换开关的状态。</p>
<p>为了行驶向目标地点，电车司机不得不经常下车来切换开关，于是，他们想请你写一个程序，计算一辆从路口<span style="font-family: Times New Roman;">A</span><span style="">到路口</span><span style="font-family: Times New Roman;">B</span><span style="">最少需要下车切换几次开关。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有<span style="font-family: Times New Roman;">3</span><span style="">个整数</span><span style="font-family: Times New Roman;">2&lt;=N&lt;=100</span><span style="">，</span><span style="font-family: Times New Roman;">1&lt;=A</span><span style="">，</span><span style="font-family: Times New Roman;">B&lt;=N</span><span style="">，分别表示路口的数量，和电车的起点，终点。</span></p>
<p>接下来有<span style="font-family: Times New Roman;">N</span><span style="">行，每行的开头有一个数字</span><span style="font-family: Times New Roman;">Ki(0&lt;=Ki&lt;=N-1)</span><span style="">，表示这个路口与</span><span style="font-family: Times New Roman;">Ki</span><span style="">条轨道相连，接下来有</span><span style="font-family: Times New Roman;">Ki</span><span style="">个数字表示每条轨道所通向的路口，开关默认指向第一个数字表示的轨道。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件只有一个数字，表示从<span style="font-family: Times New Roman;">A</span><span style="font-family: 宋体;">到</span><span style="font-family: Times New Roman;">B</span><span style="font-family: 宋体;">所需的最少的切换开关次数，若无法从</span><span style="font-family: Times New Roman;">A</span><span style="font-family: 宋体;">前往</span><span style="font-family: Times New Roman;">B</span><span style="font-family: 宋体;">，输出</span><span style="font-family: Times New Roman;">-1</span><span style="font-family: 宋体;">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2 1</p>
<p>2 2 3</p>
<p>2 3 1</p>
<p>2 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>0</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>