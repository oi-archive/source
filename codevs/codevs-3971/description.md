<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>B 国有N 座城市，其中1 号是这座国家的首都。 </p><p><br></p><p>N 座城市之间有M 趟双向航班。i 号点的转机次数定义为：从1 号点到i ，最少需要转机几 次。如果1 根本无法到达i ，那么i 点的转机次数是无穷大。 </p><p><br></p><p>由于天气原因，有些航班会被取消。 </p><p><br></p><p>一趟航班的取消是可容忍的，仅当这趟航班取消之后，2..N 每个点的转机次数不变或者只 增加了1。 </p><p><br></p><p>现在kAc 想知道，哪些航班的取消是可容忍的？ </p><p><br></p><p>如果这样的航班不存在，输出一行 “hehe”(不含引号) </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个正整数N, M </p><p><br></p><p>接下来M 行每行两个正整数a, b。表示当前这趟航班的两端是a,b 两座城市 ，保证a 不等于b ，且同一对a, b 只会出现一次。 </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若干整数，从小到大排序，表示所有的可容忍取消的航班序号。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 6 </p><p>1 2 </p><p>1 3 </p><p>1 4 </p><p>3 4 </p><p>2 5 </p><p>3 5 </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 </p><p>3 </p><p>4 </p><p>5 </p><p>6 </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如果1、2 两座城市间的航班被取消，2 号城市到首都原本需要0 次转机(有直达飞机) ，现 </p><p><br></p><p>在需要先到5 ，再到3 ，再到1 ，转机2 次。这是不可忍受的。 </p><p><br></p><p>对于40% ：N, M&lt;=500 </p><p><br></p><p>对于70% ：N&lt;=500 M &lt;= 50000 </p><p><br></p><p>对于100% ：N, M&lt;=200000 </p><p><br></p><p>保证初始给定图中所有点的转机次数不是无穷大。 </p><p><br></p>
</div>
</div>