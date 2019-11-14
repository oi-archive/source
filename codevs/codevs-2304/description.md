<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>HH有个一成不变的习惯，喜欢饭后百步走。所谓百步走，就是散步，就是在一定的时间内，走过一定的距离。</p>
<p>但是同时HH又是个喜欢变化的人，所以他不会立刻沿着刚刚走来的路走回。</p>
<p>又因为HH是个喜欢变化的人，所以他每天走过的路径都不完全一样，他想知道他究竟有多少种散步的方法。</p>
<p>现在给你学校的地图（假设每条路的长度都是一样的都是1），问长度为t，从给定地点A走到给定地点B共有多少条符合条件的路径。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：五个整数N，M，t，A，B。其中N表示学校里的路口的个数，M表示学校里的路的条数，t表示HH想要散步的距离，A表示散步的出发点，而B则表示散步的终点。</p>
<p>接下来M行，每行一组Ai，Bi，表示从路口Ai到路口Bi有一条路。数据保证Ai≠ Bi，但不保证任意两个路口之间至多只有一条路相连接。</p>
<p>路口编号从0到N − 1。</p>
<p>同一行内所有数据均由一个空格隔开，行首行尾没有多余空格。没有多余空行。</p>
<p>答案模45989。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，表示答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 3 0 0</p>
<p>0 1</p>
<p>0 2</p>
<p>0 3</p>
<p>2 1</p>
<p>3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，N ≤ 4，M ≤ 10，t ≤ 10。</p>
<p>对于100%的数据，N ≤ 20，M ≤ 60，t ≤ 2<sup>30</sup>，0 ≤ A,B&lt;N，0 ≤ Ai,Bi &lt;N。</p>
</div>
</div>