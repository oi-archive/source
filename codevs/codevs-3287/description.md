<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>A 国有 n 座城市，编号从 1 到 n，城市之间有 m 条双向道路。每一条道路对车辆都有重量限制，简称限重。现在有 q 辆货车在运输货物，司机们想知道每辆车在不超过车辆限重的情况下，最多能运多重的货物。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个用一个空格隔开的整数 n，m，表示 A 国有 n 座城市和 m 条道路。<br>接下来 m 行每行 3 个整数 x、y、z，每两个整数之间用一个空格隔开，表示从 x 号城市到 y 号城市有一条限重为 z 的道路。注意：x 不等于 y，两座城市之间可能有多条道路。<br>接下来一行有一个整数 q，表示有 q 辆货车需要运货。<br>接下来 q 行，每行两个整数 x、y，之间用一个空格隔开，表示一辆货车需要从 x 城市运输货物到 y 城市，注意：x 不等于 y。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共有 q 行，每行一个整数，表示对于每一辆货车，它的最大载重是多少。如果货车不能到达目的地，输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 <br>1 2 4 <br>2 3 3 <br>3 1 1 <br>3<br>1 3 <br>1 4 <br>1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br>-1<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30%的数据，0 &lt; n &lt; 1,000，0 &lt; m &lt; 10,000，0 &lt; q &lt; 1,000； <br>对于 60%的数据，0 &lt; n &lt; 1,000，0 &lt; m &lt; 50,000，0 &lt; q &lt; 1,000； <br>对于 100%的数据，0 &lt; n &lt; 10,000，0 &lt; m &lt; 50,000，0 &lt; q &lt; 30,000，0 ≤ z ≤ 100,000。</p>
</div>
</div>