<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一条没有分岔的高速公路上有n个关口，相邻两个关口之间的距离都是10km。所有车辆在这条高速公路上的最低速度为60km/h，最高速度为120km/h，并且只能在关口处改变速度。</p>
<p>巡逻的方式是在某个时刻T<sub>i</sub>从第n<sub>i</sub>个关口派出一辆巡逻车匀速驶抵第(n<sub>i</sub>+1)个关口，路上耗费的时间为t<sub>i</sub>秒。</p>
<p>两辆车相遇是指它们之间发生超车或者两车同时到达某关口（同时出发不算相遇）。</p>
<p>巡逻部门想知道一辆于6点整从第1个关口出发去第n个关口的车（称为目标车）最少会与多少辆巡逻车相遇，请编程计算之。假设所有车辆到达关口的时刻都是整秒。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入文件第一行为两个用空格隔开的整数，分别为关口数<span>n</span>和巡逻车数<span>m</span>。接下来的<span>m</span>行每一行为一辆巡逻车的信息（按出发位置递增排序），格式为<span>n<sub>i</sub></span>　<span>T<sub>i</sub></span>　<span>t<sub>i</sub></span>，三项用空格隔开，分别表示第<span>i</span>辆巡逻车的出发位置、出发时刻和路上耗费的时间，其中<span>n<sub>i</sub></span>和<span>t<sub>i</sub></span>为整数，<span>T<sub>i</sub></span>形如<span>hhmmss</span>，表示时、分、秒，采用<span>24</span>小时制，不足两位的数用前置<span>0</span>补齐。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件第一行为目标车与巡逻车相遇次数。第二行为目标车与巡逻车相遇次数最少时最早到达第n个关口的时刻（格式同输入中的T<sub>i</sub>）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2</p>
<p>1 060000 301</p>
<p>2 060300 600</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>
<p>061301</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>1&lt;n&lt;50,1&lt;m&lt;300</span></p>
<p><span><span>1&lt;=n<sub>i</sub>&lt;n,05:00:00&lt;=T<sub>i</sub>&lt;=23:00:00,300&lt;=t<sub>i</sub>&lt;=600</span></span></p>
</div>
</div>